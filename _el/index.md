---
layout: base
title:  'Greek UD'
udver: '2'
---

# UD for Greek <span class="flagspan"><img class="flag" src="../../flags/svg/GR.svg" /></span>

## Tokenization and Word Segmentation

* Words are generally delimited by whitespace or punctuation. Exceptions:
* Numerical expressions are treated as single words and may contain punctuation or symbols:
  *15*, *2.200*, *0,05%*
* Dates are treated as nouns and in some cases may contain underscores:
  *1871/72*, *1943-44*, *2012-03-25*, *20ετίας*, *'44*, *11/24_Νοεμβρίου_1916*, *5ης_Νοεμβρίου_2001*
* Abbreviations are treated as single words and may contain punctuation: *ΕΕ*, *χλμ.*, *π.Χ.*
* There is one group of contractions that are treated as multi-word tokens and are segmented to individual syntactic words, namely combinations of the preposition *σε* and types of the definite article: *στον = σ + τον* “in/to/on the”.


## Morphology


### Tags

* Greek uses 16 universal POS categories, including particles ([PART]()). No interjections ([INTJ]()) exist in the current dataset.
* Words tagged [PART]() are the negative particles *δεν* and *μην*.
* The current set of auxiliary words ([AUX]()) include:
  * the copula *είμαι* (be)
  * the auxiliary verb *έχω* (have), which combines with the infinitive to form perfect tenses
  * the impersonal verb *πρέπει* (must)
  * the indeclinable future marker *θα*
  * the indeclinable subjunctive particle *να*
  * the indeclinable subjunctive particle *ας*
*  The tag [DET]() is used for the definite and the indefinite article. The tag [PRON]() is used for pronouns occurring as the head of a noun phrase, for pronouns preceding or following their nominal head with which they agree in gender, number and case,  or for possessives in the genitive following their head
*  Past participles used adjectivally are  mostly tagged  [ADJ]()


### Features

* Nouns have inherent [Gender]() and inflect for [Number]() (singular or plural), and [Case]() (nominative, genitive, accusative and vocative). Remnants of the dative case also exist in set phrases.
* Finite verbs of the [Ind]() mood have one of two values of [Voice](): `Act` and `Pass`; one of two values of [Tense](): `Past` and `Pres`; one of two values of [Number](): `Sing` and `Plur`; and one of three values of [Person](): `1`, `2` and `3`.   Finite verbs of the [Imp]() mood have only `2`nd [Person]().  The [Aspect]() feature has `Imp` and `Perf` values. There are three types of nonfinite forms: infinitives used to form perfect tenses, passive voice `-μένος` participles, and active voice `-[ώο]ντας` converbs.
* Adjectives agree with nouns (in both attributive and predicate position) with respect to the [Gender](), [Number]() and [Case]() features.
* Pronouns inflect for [Gender](), [Number](), [Case]() like nouns and adjectives.
* [Degree]() applies to adjectives ([ADJ]()) and adverbs ([ADV]()) and has one of three possible values: `Pos`, `Cmp`, `Sup`


## Syntax

* Nominal subjects ([nsubj]()) are in the nominative case, without adpositions.
* Objects occur in the accusative case (direct objects) or in the genitive (indirect objects).
* All prepositional objects are currently labeled with the oblique relation.
* Case marking of subjects and objects allows all possible word order variations. However, when introducing new information the most frequent word orders are SVO and VSO. OVS sentences occur when the object is topicalized and they often involve a combination of an object and an object clitic.
* The copula verb *είμαι* (be) is used in equational, attributional, locative, possessive and benefactory nonverbal clauses. Different verbs like *υπάρχω* are typically used in existential clauses.
* The following subtypes are used in Greek:
  * [acl:relcl]() for relative clauses
  * [csubj:pass]() for clausal subjects of passive verbs
  * [nsubj:pass]() for nominal subjects of passive verbs
  * [obl:agent]() for agents of passive verbs

## Treebanks

There is one Greek UD treebank:

  * [Greek-GDT](../treebanks/el_gdt/index.html)
