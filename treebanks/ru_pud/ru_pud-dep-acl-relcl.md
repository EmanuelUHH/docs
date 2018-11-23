---
layout: base
title:  'Statistics of acl:relcl in UD_Russian-PUD'
udver: '2'
---

## Treebank Statistics: UD_Russian-PUD: Relations: `acl:relcl`

This relation is a language-specific subtype of <tt><a href="ru_pud-dep-acl.html">acl</a></tt>.

160 nodes (1%) are attached to their parents as `acl:relcl`.

160 instances of `acl:relcl` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.01875.

The following 12 pairs of parts of speech are connected with `acl:relcl`: <tt><a href="ru_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru_pud-pos-VERB.html">VERB</a></tt> (126; 79% instances), <tt><a href="ru_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ru_pud-pos-VERB.html">VERB</a></tt> (11; 7% instances), <tt><a href="ru_pud-pos-DET.html">DET</a></tt>-<tt><a href="ru_pud-pos-VERB.html">VERB</a></tt> (7; 4% instances), <tt><a href="ru_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ru_pud-pos-VERB.html">VERB</a></tt> (5; 3% instances), <tt><a href="ru_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru_pud-pos-ADJ.html">ADJ</a></tt> (4; 3% instances), <tt><a href="ru_pud-pos-DET.html">DET</a></tt>-<tt><a href="ru_pud-pos-PRON.html">PRON</a></tt> (1; 1% instances), <tt><a href="ru_pud-pos-NUM.html">NUM</a></tt>-<tt><a href="ru_pud-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="ru_pud-pos-PRON.html">PRON</a></tt>-<tt><a href="ru_pud-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="ru_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ru_pud-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="ru_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ru_pud-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="ru_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ru_pud-pos-PROPN.html">PROPN</a></tt> (1; 1% instances), <tt><a href="ru_pud-pos-X.html">X</a></tt>-<tt><a href="ru_pud-pos-AUX.html">AUX</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 6 acl:relcl	color:blue
1	Обычно	обычно	ADV	RB	_	3	advmod	_	_
2	это	это	DET	DT	Animacy=Inan|Case=Nom|Gender=Neut|Number=Sing	3	nsubj	_	_
3	исполнители	исполнитель	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Masc|Number=Plur	0	root	_	SpaceAfter=No
4	,	,	PUNCT	,	_	6	punct	_	_
5	которые	который	DET	WDT	Animacy=Anim|Case=Nom|Number=Plur	6	nsubj	_	_
6	хотят	хотеть	VERB	VBC	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres	3	acl:relcl	_	_
7	сделать	сделать	VERB	VB	Aspect=Perf	6	xcomp	_	_
8	кучу	куча	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Fem|Number=Sing	7	obj	_	_
9	вещей	вещь	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Fem|Number=Plur	8	nmod	_	SpaceAfter=No
10	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 12 acl:relcl	color:blue
1	В	в	ADP	IN	_	3	case	_	_
2	это	этот	DET	DT	Animacy=Inan|Case=Acc|Gender=Neut|Number=Sing	3	det	_	_
3	время	время	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Neut|Number=Sing	7	obl	_	_
4	его	его	DET	PRP$	Case=Acc|Gender[psor]=Masc|Number[psor]=Sing|Person=3|PronType=Prs	5	det	_	_
5	место	место	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Neut|Number=Sing	7	obj	_	_
6	трибуна	трибуна	NOUN	NN	Animacy=Anim|Case=Gen|Gender=Masc|Number=Sing	5	nmod	_	_
7	занимал	занимать	VERB	VBC	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Tense=Past	0	root	_	_
8	Марк	Марк	PROPN	NNP	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	7	nsubj	_	_
9	Антоний	Антоний	PROPN	NNP	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	8	flat:name	_	SpaceAfter=No
10	,	,	PUNCT	,	_	12	punct	_	_
11	который	который	DET	WDT	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	12	nsubj	_	_
12	оставался	оставаться	VERB	VBC	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Tense=Past	9	acl:relcl	_	_
13	в	в	ADP	IN	_	15	case	_	_
14	этой	этот	DET	DT	Animacy=Inan|Gender=Fem|Number=Sing	15	det	_	_
15	должности	должность	NOUN	NN	Animacy=Inan|Gender=Fem|Number=Sing	12	obl	_	_
16	до	до	ADP	IN	_	17	case	_	_
17	декабря	декабрь	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing	12	obl	_	SpaceAfter=No
18	.	.	PUNCT	.	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 acl:relcl	color:blue
1	Джордж	Джордж	PROPN	NNP	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	3	nsubj:pass	_	_
2	был	быть	AUX	VBC	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Tense=Past	3	aux:pass	_	_
3	поражен	поразить	VERB	VBN	Animacy=Anim|Aspect=Perf|Case=Nom|Gender=Masc|Number=Sing|Tense=Past|Variant=Short|Voice=Pass	0	root	_	_
4	тем	то	DET	DT	Animacy=Inan|Case=Ins|Gender=Neut|Number=Sing	3	iobj	_	SpaceAfter=No
5	,	,	PUNCT	,	_	8	punct	_	_
6	что	что	ADP	IN	_	8	mark	_	_
7	он	он	PRON	PRP	Case=Nom|Gender=Masc|Number=Sing|Person=3	8	nsubj	_	_
8	считал	считать	VERB	VBC	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Tense=Past	4	acl:relcl	_	_
9	упадком	упадок	NOUN	NN	Animacy=Inan|Case=Ins|Gender=Masc|Number=Sing	8	advmod	_	_
10	их	они	DET	PRP$	Case=Gen|Number[psor]=Plur|Person=3|PronType=Prs	11	det	_	_
11	нравов	нрав	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	9	nmod	_	SpaceAfter=No
12	.	.	PUNCT	.	_	3	punct	_	_

~~~


