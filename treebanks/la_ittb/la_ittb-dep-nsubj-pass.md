---
layout: base
title:  'Statistics of nsubj:pass in UD_Latin-ITTB'
udver: '2'
---

## Treebank Statistics: UD_Latin-ITTB: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="la_ittb-dep-nsubj.html">nsubj</a></tt>.

6798 nodes (2%) are attached to their parents as `nsubj:pass`.

5214 instances of `nsubj:pass` (77%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.81612238893792.

The following 12 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (4222; 62% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-PRON.html">PRON</a></tt> (2204; 32% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt> (220; 3% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt> (76; 1% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-NUM.html">NUM</a></tt> (67; 1% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-ADV.html">ADV</a></tt> (2; 0% instances), <tt><a href="la_ittb-pos-ADV.html">ADV</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-X.html">X</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-X.html">X</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 nsubj:pass	color:blue
1	quis	qui	PRON	F1|grn1|casA|gen1|varA	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|PronType=Rel	2	det	_	_
2	modus	modus	NOUN	B1|grn1|casA|gen1	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	nsubj	_	_
3	sit	sum	AUX	N3|modB|tem1|gen6	Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	_
4	possibilis	possibilis	ADJ	C1|grn1|casA|gen1	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	0	root	_	_
5	divinae	divinus	ADJ	A1|grn1|casB|gen2	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing	6	amod	_	_
6	veritatis	veritas	NOUN	C1|grn1|casB|gen2|vgr1	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing	7	nsubj:pass	_	_
7	manifestandae	manifesto	VERB	J2|modO|grp1|casB|gen2	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|VerbForm=Gdv|Voice=Pass	2	acl	_	SpaceAfter=No
8	.	.	PUNCT	Punc	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 nsubj:pass	color:blue
1	quidam	quidam	PRON	F1|grn1|casJ|gen1	Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|PronType=Ind	3	nsubj:pass	_	_
2	vero	vero	ADV	B1|grn1|casG|vgr1	Degree=Pos	3	advmod	_	_
3	impediuntur	impedio	VERB	M3|modJ|tem1|gen9	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	_
4	necessitate	necessitas	NOUN	C1|grn1|casF|gen2	Case=Abl|Degree=Pos|Gender=Fem|Number=Sing	3	obl	_	_
5	rei	res	NOUN	E1|grn1|casB|gen2	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing	4	nmod	_	_
6	familiaris	familiaris	ADJ	C1|grn1|casB|gen2	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing	5	amod	_	SpaceAfter=No
7	.	.	PUNCT	Punc	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 5 nsubj:pass	color:blue
1	unde	unde	ADV	O4	_	9	advmod	_	_
2	et	et	CCONJ	O4	_	9	cc	_	_
3	in	in	ADP	S4	AdpType=Prep	4	case	_	_
4	ea	is	PRON	F1|grn1|casF|gen2	Case=Abl|Degree=Pos|Gender=Fem|Number=Sing|PronType=Dem,Prs	9	obl	_	_
5	plurima	multus	ADJ	B1|grn3|casJ|gen3	Case=Nom|Degree=Abs|Gender=Neut|Number=Plur	9	nsubj:pass	_	_
6	humanum	humanus	ADJ	B1|grn1|casD|gen1	Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	7	amod	_	_
7	sensum	sensus	NOUN	D1|grn1|casD|gen1	Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	8	obj	_	_
8	excedentia	excedo	VERB	L2|modD|tem1|grp1|casJ|gen3	Case=Nom|Degree=Pos|Gender=Neut|Number=Plur|Tense=Pres|VerbForm=Part|Voice=Act	5	acl	_	_
9	proponuntur	propono	VERB	L3|modJ|tem1|gen9	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	SpaceAfter=No
10	.	.	PUNCT	Punc	_	9	punct	_	_

~~~


