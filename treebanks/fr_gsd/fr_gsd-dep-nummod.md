---
layout: base
title:  'Statistics of nummod in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `nummod`

This relation is universal.

3779 nodes (1%) are attached to their parents as `nummod`.

3682 instances of `nummod` (97%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.10240804445621.

The following 15 pairs of parts of speech are connected with `nummod`: <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (3184; 84% instances), <tt><a href="fr_gsd-pos-SYM.html">SYM</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (407; 11% instances), <tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (53; 1% instances), <tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt> (36; 1% instances), <tt><a href="fr_gsd-pos-X.html">X</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (33; 1% instances), <tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (26; 1% instances), <tt><a href="fr_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (10; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (8; 0% instances), <tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (6; 0% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-ADJ.html">ADJ</a></tt> (5; 0% instances), <tt><a href="fr_gsd-pos-SYM.html">SYM</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (5; 0% instances), <tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="fr_gsd-pos-X.html">X</a></tt> (2; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-SYM.html">SYM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 8 nummod	color:blue
1	Il	il	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Prs	4	nsubj	_	_
2	ne	ne	ADV	_	Polarity=Neg	4	advmod	_	_
3	sera	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Fut|VerbForm=Fin	4	cop	_	_
4	présent	présent	ADJ	_	Gender=Masc|Number=Sing	0	root	_	_
5	que	que	ADV	_	_	10	advmod	_	_
6	durant	durant	ADP	_	_	10	case	_	_
7	les	le	DET	_	Definite=Def|Gender=Fem|Number=Plur|PronType=Art	10	det	_	_
8	10	10	NUM	_	_	10	nummod	_	_
9	premières	premier	ADJ	_	Gender=Fem|Number=Plur	10	amod	_	_
10	parties	partie	NOUN	_	Gender=Fem|Number=Plur	4	obl	_	SpaceAfter=No
11	.	.	PUNCT	_	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nummod	color:blue
1	Ce	ce	DET	_	Gender=Masc|Number=Sing|PronType=Dem	2	det	_	_
2	taux	taux	NOUN	_	Gender=Masc|Number=Sing	3	nsubj	_	_
3	atteint	atteindre	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
4	même	même	ADV	_	_	5	advmod	_	_
5	50	50	NUM	_	_	6	nummod	_	SpaceAfter=No
6	%	%	SYM	_	_	3	obj	_	_
7	dans	dans	ADP	_	_	9	case	_	_
8	certains	certain	DET	_	Gender=Masc|Number=Plur	9	det	_	_
9	centres	centre	NOUN	_	Gender=Masc|Number=Plur	3	obl:mod	_	SpaceAfter=No
10	.	.	PUNCT	_	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 nummod	color:blue
1	Le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	2	det	_	_
2	restaurant	restaurant	NOUN	_	Gender=Masc|Number=Sing	4	nsubj	_	_
3	se	se	PRON	_	Person=3|PronType=Prs	4	expl:pass	_	_
4	trouve	trouver	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
5	à	à	ADP	_	_	8	case	_	_
6	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	8	det	_	_
7	289	289	NUM	_	_	8	nummod	_	_
8	Boul	Boul	PROPN	_	_	4	obl:arg	_	_
9	Curé	curé	NOUN	_	Gender=Masc|Number=Sing	8	appos	_	_
10	Labelle	Labelle	PROPN	_	_	9	appos	_	_
11	SAINTE	SAINTE	PROPN	_	_	9	nmod	_	_
12	ROSE	ROSE	PROPN	_	_	11	flat:name	_	SpaceAfter=No
13	.	.	PUNCT	_	_	4	punct	_	_

~~~


