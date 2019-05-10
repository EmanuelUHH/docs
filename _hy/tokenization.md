---
layout: base
title:  'Tokenization'
udver: '2'
---

# Tokenization

The low-level tokenization of the Eastern Armenian UD treebank follows the tokenization of the
[ՀայՇտեմ - Eastern Armenian Dependency Treebank 1.0](http://armtreebank.yerevann.com/) (ArmDT-East):

* In general, tokens are delimited by whitespace.
* Punctuation (recognized by the corresponding Unicode property) that is conventionally written adjacent to the preceding or following word is separated during tokenization.
  Some special cases worth mentioning:
  * An abbreviation marked by a period, as in *թ.* “year”, becomes two tokens, *<b>թ</b>* and *<b>.</b>* .
  * A compound containing a hyphen becomes three tokens (two words and the hyphen), as in *անգլո-ամերիկյան* “anglo-american”, *պատմա-բանասիրական* “historical-philological”.
    In these cases, the first token is a special form of adjective that never occurs independently.
    Compounds without a hyphen are not split, thus _ռազմածովային_ “navy” is one token but _հասարակական-քաղաքական_ “civic-social” would be three tokens.
    Another common case of splitting-on-hyphen are reduplicative or echo words as in *մեծ-մեծ* “very big”, *շուն-մուն* “dog or something”.
  * Inflectional bound morphemes and hypens after phrases or sentences used as names in quotation marks or after abbreviations marked by a period, as in *«Երկիր Նաիրի»-ից* “from “Yerkir Nairi” or *1937 թ.-ին* “in year 1937” are split and are considered as separate tokens: {&nbsp;*<b>«</b>* *<b>Երկիր</b>* *<b>Նաիրի</b>* *<b>»</b>* *<b>-</b>* *<b>ից</b>*&nbsp;} and {&nbsp;*<b>1937</b>* , *<b>թ</b>* , *<b>.</b>* , *<b>-</b>* , *<b>ին</b>*&nbsp;} .
  The word before the hypen is the head and the bound morpheme is linked with a `dep`. Tokenizing and segmenting this way seems easier for parsing.  
  * The words that contain “infixed” punctuation (question, exclamation, emphasis and Armenian abbreviation marks), as in *ինչո՞ւ* “why?”, are considered multi-word tokens and become two tokens, *<b>ինչու</b>* and *<b>՞</b>* . EXCEPTION is the apostrophe, as in *Ժաննա դ՚Արկ* “Joan of Arc”, which is split and belongs to the preceding word, {&nbsp;*<b>Ժաննա</b>* , *<b>դ՚</b>* , *<b>Արկ</b>*&nbsp;}.
  * Numerical expressions (including dates) are treated as single words as long as they do not contain spaces, for example, *<b>355,089.40</b>* , *<b>01.01.1970</b>* , *<b>01/01/1970</b>* , *<b>11:00</b>* , *<b>11.00</b>* , *<b>1937-1938</b>* , *<b>10-15</b>* . Decimal numbers are also kept as one token, e.g. *<b>2.1</b>* , *<b>2,1</b>* , *<b>0.5-1.5</b>* .
  * Numerical expressions with hyphen and Armenian endings (e.g. *<b>1-ին</b>* “1st”, *<b>3-ով</b>* “3.Ins”) as well as adjectives and other non-numerals which contain digits (e.g. *<b>1000-ական</b>* “by 1000”, *<b>1950-ականներին</b>* “in 1950s”, *<b>20-ամյակ</b>* “20th anniversary”, *<b>1700-ամյա</b>* “1700-year-old”, *<b>ՆԱՏՕ-ական</b>* “belonging-to-NATO, *<b>ՏՈՒ-154Մ</b>* “TU-154M”) are treated as single tokens.
  * Generally, every punctuation character constitutes a token of its own. Thus *»,—* will become three tokens.
  * Exceptions are conventional multi-character punctuation marks: *<b>...</b>* , *<b>....</b>* , and emojis and smileys: *<b>:)</b>* , *<b>^_^</b>* , *<b>։Ճ</b>* etc.
  Conventional non-armenian multi-character punctuation marks and terms are tokenized as single tokens: *<b>?!</b>* .
* Special symbols before and after numerical expressions, as in *$250* , *4,81%* , *+32°С* , are tokenised separately (so, the tokens are {&nbsp;*<b>$</b>* , *<b>250</b>*&nbsp;} , {&nbsp;<b>4,81</b> , <b>%</b>&nbsp;} , {&nbsp;<b>+</b> , <b>32</b> , <b>°С</b>&nbsp;}).
* Email addresses, URLs, and tweet-style names are treated as single tokens: muster@muster.am , https://github.com , @gov_am .

### Multi-word tokens

See above, the “infixed” punctuation.

### Pronouns and adverbs

* Indefinite pronouns and adverbs like *ինչ-որ, փոքր-ինչ, դույզն-ինչ, ինչ-ինչ* “something, somewhat”, etc. are splitted as compounds containing a hyphen and become three tokens (two words and the hyphen).

### Verb forms, analytical grammatical forms, negation

* the forms of necessitative mood, analytical causative, complex tenses, complex comparatives, etc. are splitted
according to the orthographic principle: {&nbsp;*<b>պիտի</b>* , *<b>վազեն</b>*&nbsp;} “they must run”, {&nbsp;*<b>գրել</b>* , *<b>տվեց</b>*&nbsp;} “made write”, {&nbsp;*<b>վազում</b>* , *<b>եմ</b>*&nbsp;} “I run”, {&nbsp;*<b>ավելի</b>* , *<b>լուրջ</b>*&nbsp;} “more serious”.
* *<b>մի</b>* and *<b>ոչ</b>* used as negation markers with verbs, adjectives, pronouns and other words are tokenized according to the orthographic rules: {&nbsp;*<b>մի</b>* , *<b>գրիր</b>*&nbsp;} “don't write”, {&nbsp;*<b>ոչ</b>* , *<b>պաշտոնական</b>*&nbsp;} “unofficial”, {&nbsp;*<b>ոչ</b>* , *<b>մի</b>* , *<b>կերպ</b>*&nbsp;} “in no way”.

# Sentence splitting

Each sentence contains only one root.
Splitting is usually performed after an end-of-sentence full stop or after a dot, ellipsis or colon when these punctuation marks separate unrelated subparts of a sentence. Items in a list may sometimes be rendered as separate sentences.
