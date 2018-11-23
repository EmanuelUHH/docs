---
layout: base
title:  'Statistics of parataxis in UD_German-PUD'
udver: '2'
---

## Treebank Statistics: UD_German-PUD: Relations: `parataxis`

This relation is universal.

68 nodes (0%) are attached to their parents as `parataxis`.

68 instances of `parataxis` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 12.3676470588235.

The following 13 pairs of parts of speech are connected with `parataxis`: <tt><a href="de_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="de_pud-pos-VERB.html">VERB</a></tt> (37; 54% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt> (5; 7% instances), <tt><a href="de_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt> (5; 7% instances), <tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_pud-pos-VERB.html">VERB</a></tt> (4; 6% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-VERB.html">VERB</a></tt> (4; 6% instances), <tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt> (3; 4% instances), <tt><a href="de_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt> (3; 4% instances), <tt><a href="de_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="de_pud-pos-PROPN.html">PROPN</a></tt> (2; 3% instances), <tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-SYM.html">SYM</a></tt> (1; 1% instances), <tt><a href="de_pud-pos-PRON.html">PRON</a></tt>-<tt><a href="de_pud-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="de_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_pud-pos-VERB.html">VERB</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 12 parataxis	color:blue
1	Ich	ich	PRON	PRP	Case=Nom|Number=Sing|Person=1	9	nsubj	_	_
2	werde	werden	AUX	VBC	Mood=Ind|Number=Sing|Person=1|Tense=Pres	9	aux	_	_
3	so	so	ADV	RB	Degree=Pos	9	advmod	_	_
4	oder	oder	CCONJ	CC	_	5	cc	_	_
5	so	so	ADV	RB	Degree=Pos	3	conj	_	_
6	in	in	ADP	APPR	_	8	case	_	_
7	das	der	DET	ART	Case=Acc|Definite=Def|Gender=Neut|Number=Sing|Person=3	8	det	_	_
8	Gefängnis	Gefängnis	NOUN	NN	Case=Acc|Gender=Neut|Number=Sing|Person=3	9	obl	_	_
9	kommen	kommen	VERB	VB	_	0	root	_	SpaceAfter=No
10	,	,	PUNCT	,	_	12	punct	_	_
11	ich	ich	PRON	PRP	Case=Nom|Number=Sing|Person=1	12	nsubj	_	_
12	hoffe	hoffen	VERB	VBC	Mood=Ind|Number=Sing|Person=1|Tense=Pres	9	parataxis	_	SpaceAfter=No
13	,	,	PUNCT	,	_	17	punct	_	_
14	das	der	DET	DT	Case=Nom|Definite=Def|Gender=Neut|Number=Sing|Person=3	17	nsubj	_	_
15	war	sein	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Past	17	cop	_	_
16	es	es	PRON	PRP	Case=Acc|Gender=Neut|Number=Sing|Person=3	17	obj	_	_
17	wert	wert	ADJ	JJ	Degree=Pos	12	ccomp	_	SpaceAfter=No
18	.	.	PUNCT	.	_	9	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 9 parataxis	color:blue
1	Es	es	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3	5	nsubj	_	_
2	ist	sein	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	5	cop	_	_
3	natürlich	natürlich	ADV	RB	Degree=Pos	5	advmod	_	_
4	die	der	DET	DT	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|Person=3	5	det	_	_
5	Wahl	Wahl	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	0	root	_	SpaceAfter=No
6	,	,	PUNCT	,	_	9	punct	_	_
7	nicht	nicht	ADV	RB	Degree=Pos|Polarity=Neg	9	advmod	_	_
8	„	„	PUNCT	``	_	9	punct	_	SpaceAfter=No
9	Game	Game	NOUN	NN	Case=Nom|Number=Sing|Person=3	5	parataxis	_	Proper=True
10	of	of	ADP	IN	_	11	case	_	Proper=True
11	Thrones	Throne	NOUN	NN	Number=Plur|Person=3	9	nmod	_	Proper=True|SpaceAfter=No
12	“	“	PUNCT	''	_	9	punct	_	SpaceAfter=No
13	.	.	PUNCT	.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 19	bgColor:blue
# visual-style 19	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 19 parataxis	color:blue
1	„	„	PUNCT	``	_	5	punct	_	SpaceAfter=No
2	Ich	ich	PRON	PRP	Case=Nom|Number=Sing|Person=1	5	nsubj	_	_
3	muss	müssen	AUX	VBC	Mood=Ind|Number=Sing|Person=1|Tense=Pres	5	aux	_	_
4	Andy	Andy	PROPN	NNP	Case=Dat|Gender=Masc|Number=Sing|Person=3	5	iobj	_	_
5	gratulieren	gratulieren	VERB	VB	_	22	ccomp	_	SpaceAfter=No
6	;	;	PUNCT	:	_	19	punct	_	_
7	die	der	DET	DT	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|Person=3	8	det	_	_
8	Nummer	Nummer	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	19	csubj	_	_
9	1	1	NUM	CD	NumType=Card	8	nummod	_	_
10	in	in	ADP	IN	_	12	case	_	_
11	der	der	DET	DT	Case=Dat|Definite=Def|Gender=Fem|Number=Sing|Person=3	12	det	_	_
12	Welt	Welt	NOUN	NN	Case=Dat|Gender=Fem|Number=Sing|Person=3	8	nmod	_	_
13	zu	zu	PART	RP	_	8	mark	_	_
14	werden	werden	AUX	VB	_	8	cop	_	SpaceAfter=No
15	,	,	PUNCT	,	_	8	punct	_	_
16	ist	sein	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	19	cop	_	_
17	eine	ein	DET	DT	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing|Person=3	19	det	_	_
18	unglaubliche	unglaublich	ADJ	JJ	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing|Person=3	19	amod	_	InflectionType=Mixed
19	Leistung	Leistung	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	5	parataxis	_	SpaceAfter=No
20	“	“	PUNCT	''	_	5	punct	_	SpaceAfter=No
21	,	,	PUNCT	,	_	5	punct	_	_
22	sagte	sagen	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	_
23	der	der	DET	DT	Case=Nom|Definite=Def|Gender=Masc|Number=Sing|Person=3	24	det	_	_
24	Amerikaner	Amerikaner	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	22	nsubj	_	Proper=True|SpaceAfter=No
25	.	.	PUNCT	.	_	22	punct	_	_

~~~


