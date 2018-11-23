---
layout: base
title:  'Statistics of root in UD_Czech-CAC'
udver: '2'
---

## Treebank Statistics: UD_Czech-CAC: Relations: `root`

This relation is universal.

24709 nodes (5%) are attached to their parents as `root`.

24709 instances of `root` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.49249261402728.

The following 14 pairs of parts of speech are connected with `root`: -<tt><a href="cs_cac-pos-VERB.html">VERB</a></tt> (17046; 69% instances), -<tt><a href="cs_cac-pos-ADJ.html">ADJ</a></tt> (3846; 16% instances), -<tt><a href="cs_cac-pos-NOUN.html">NOUN</a></tt> (2688; 11% instances), -<tt><a href="cs_cac-pos-ADV.html">ADV</a></tt> (420; 2% instances), -<tt><a href="cs_cac-pos-DET.html">DET</a></tt> (261; 1% instances), -<tt><a href="cs_cac-pos-PROPN.html">PROPN</a></tt> (174; 1% instances), -<tt><a href="cs_cac-pos-NUM.html">NUM</a></tt> (114; 0% instances), -<tt><a href="cs_cac-pos-SYM.html">SYM</a></tt> (55; 0% instances), -<tt><a href="cs_cac-pos-PRON.html">PRON</a></tt> (45; 0% instances), -<tt><a href="cs_cac-pos-PART.html">PART</a></tt> (24; 0% instances), -<tt><a href="cs_cac-pos-SCONJ.html">SCONJ</a></tt> (13; 0% instances), -<tt><a href="cs_cac-pos-CCONJ.html">CCONJ</a></tt> (10; 0% instances), -<tt><a href="cs_cac-pos-INTJ.html">INTJ</a></tt> (7; 0% instances), -<tt><a href="cs_cac-pos-AUX.html">AUX</a></tt> (6; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 4 root	color:blue
1	Zvýšené	zvýšený	ADJ	AANS4----1A----	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	2	amod	2:amod	LDeriv=zvýšit
2	úsilí	úsilí	NOUN	NNNS4-----A----	Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos	4	obj	4:obj	_
3	budeme	být	AUX	VB-P---1F-AA---	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Tense=Fut|VerbForm=Fin|Voice=Act	4	aux	4:aux	_
4	věnovat	věnovat	VERB	Vf--------A----	Aspect=Imp|Polarity=Pos|VerbForm=Inf	0	root	0:root	_
5	zavádění	zavádění	NOUN	NNNS3-----A----	Case=Dat|Gender=Neut|Number=Sing|Polarity=Pos	4	iobj	4:iobj	LDeriv=zavádět
6	nových	nový	ADJ	AAIP2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	7	amod	7:amod	_
7	poznatků	poznatek	NOUN	NNIP2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur|Polarity=Pos	5	nmod	5:nmod	_
8	do	do	ADP	RR--2----------	AdpType=Prep|Case=Gen	9	case	9:case	LId=do-1
9	praxe	praxe	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	5	nmod	5:nmod	SpaceAfter=No
10	.	.	PUNCT	Z:-------------	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 9 root	color:blue
1	Stav	stav	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos	9	nsubj	9:nsubj	_
2	a	a	CCONJ	J^-------------	_	3	cc	3:cc	LId=a-1
3	využívání	využívání	NOUN	NNNS1-----A----	Case=Nom|Gender=Neut|Number=Sing|Polarity=Pos	1	conj	1:conj|9:nsubj	LDeriv=využít
4	půdního	půdní	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	5	amod	5:amod	_
5	fondu	fond	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	1	nmod	1:nmod|3:nmod	_
6	jsou	být	AUX	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	9	cop	9:cop	_
7	u	u	ADP	RR--2----------	AdpType=Prep|Case=Gen	8	case	8:case	LId=u-1
8	nás	já	PRON	PP-P2--1-------	Case=Gen|Number=Plur|Person=1|PronType=Prs	9	obl	9:obl	_
9	neuspokojivé	uspokojivý	ADJ	AAIP1----1N----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Neg	0	root	0:root	SpaceAfter=No
10	.	.	PUNCT	Z:-------------	_	9	punct	9:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 1 root	color:blue
1	Vypracování	vypracování	NOUN	NNNS4-----A----	Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos	0	root	0:root	LDeriv=vypracovat
2	nových	nový	ADJ	AAIP2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	3	amod	3:amod	_
3	principů	princip	NOUN	NNIP2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur|Polarity=Pos	1	nmod	1:nmod	_
4	regulace	regulace	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	3	nmod	3:nmod	_
5	vodního	vodní	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	6	amod	6:amod	_
6	režimu	režim	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	4	nmod	4:nmod	_
7	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	8	case	8:case	LId=v-1
8	půdě	půda	NOUN	NNFS6-----A----	Case=Loc|Gender=Fem|Number=Sing|Polarity=Pos	6	nmod	6:nmod	SpaceAfter=No
9	.	.	PUNCT	Z:-------------	_	1	punct	1:punct	_

~~~


