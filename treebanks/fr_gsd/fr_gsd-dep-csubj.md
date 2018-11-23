---
layout: base
title:  'Statistics of csubj in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `csubj`

This relation is universal.
There are 1 language-specific subtypes of `csubj`: <tt><a href="fr_gsd-dep-csubj-pass.html">csubj:pass</a></tt>.

42 nodes (0%) are attached to their parents as `csubj`.

32 instances of `csubj` (76%) are right-to-left (child precedes parent).
Average distance between parent and child is 7.95238095238095.

The following 5 pairs of parts of speech are connected with `csubj`: <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt> (17; 40% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt> (15; 36% instances), <tt><a href="fr_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt> (8; 19% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 csubj	color:blue
1	Mieux	mieux	ADV	_	_	2	advmod	_	_
2	vaut	valoir	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	les	le	PRON	_	Number=Plur|Person=3|PronType=Prs	4	obj	_	_
4	oublier	oublier	VERB	_	VerbForm=Inf	2	csubj	_	SpaceAfter=No
5	.	.	PUNCT	_	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 1 csubj	color:blue
1	Aller	aller	VERB	_	VerbForm=Inf	10	csubj	_	_
2	dans	dans	ADP	_	_	4	case	_	_
3	ce	ce	DET	_	Gender=Masc|Number=Sing|PronType=Dem	4	det	_	_
4	restaurant	restaurant	NOUN	_	Gender=Masc|Number=Sing	1	obl:arg	_	_
5	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	_	_
6	tout	tout	ADV	_	_	7	advmod	_	_
7	simplement	simplement	ADV	_	_	10	advmod	_	_
8	un	un	DET	_	Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	10	det	_	_
9	grand	grand	ADJ	_	Gender=Masc|Number=Sing	10	amod	_	_
10	plaisir	plaisir	NOUN	_	Gender=Masc|Number=Sing	0	root	_	_
11	!	!	PUNCT	_	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 4 csubj	color:blue
1	Seul	seul	ADJ	_	Gender=Masc|Number=Sing	2	amod	_	_
2	bémol	bémol	NOUN	_	Gender=Masc|Number=Sing	0	root	_	SpaceAfter=No
3	,	,	PUNCT	_	_	4	punct	_	_
4	trouver	trouver	VERB	_	VerbForm=Inf	11	csubj	_	_
5	une	un	DET	_	Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	6	det	_	_
6	place	place	NOUN	_	Gender=Fem|Number=Sing	4	obj	_	_
7	de	de	ADP	_	_	8	case	_	_
8	parking	parking	NOUN	_	Gender=Masc|Number=Sing	6	nmod	_	_
9	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	11	cop	_	_
10	très	très	ADV	_	_	11	advmod	_	_
11	difficile	difficile	ADJ	_	Gender=Masc|Number=Sing	2	ccomp	_	_
12	!	!	PUNCT	_	_	11	punct	_	_

~~~


