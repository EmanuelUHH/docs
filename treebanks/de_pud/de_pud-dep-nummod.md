---
layout: base
title:  'Statistics of nummod in UD_German-PUD'
udver: '2'
---

## Treebank Statistics: UD_German-PUD: Relations: `nummod`

This relation is universal.

192 nodes (1%) are attached to their parents as `nummod`.

174 instances of `nummod` (91%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.203125.

The following 7 pairs of parts of speech are connected with `nummod`: <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-NUM.html">NUM</a></tt> (149; 78% instances), <tt><a href="de_pud-pos-SYM.html">SYM</a></tt>-<tt><a href="de_pud-pos-NUM.html">NUM</a></tt> (22; 11% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt> (15; 8% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt> (2; 1% instances), <tt><a href="de_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="de_pud-pos-NUM.html">NUM</a></tt> (2; 1% instances), <tt><a href="de_pud-pos-ADP.html">ADP</a></tt>-<tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="de_pud-pos-DET.html">DET</a></tt>-<tt><a href="de_pud-pos-NUM.html">NUM</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nummod	color:blue
1	Die	der	DET	DT	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|Person=3	3	det	_	_
2	aktuelle	aktuell	ADJ	JJ	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing|Person=3	3	amod	_	InflectionType=Weak
3	Wartezeit	Wartezeit	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	4	nsubj	_	_
4	beträgt	betragen	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	0	root	_	_
5	acht	acht	NUM	CD	NumType=Card	6	nummod	_	_
6	Wochen	Woche	NOUN	NN	Case=Acc|Gender=Fem|Number=Plur|Person=3	4	obl:tmod	_	SpaceAfter=No
7	.	.	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 nummod	color:blue
1	5.000	5.000	NUM	CD	NumType=Card	2	nummod	_	_
2	$	$	SYM	SYM	_	0	root	_	_
3	pro	pro	ADP	IN	_	4	case	_	_
4	Person	Person	NOUN	NN	Case=Dat|Gender=Fem|Number=Sing|Person=3	2	nmod	_	SpaceAfter=No
5	,	,	PUNCT	,	_	8	punct	_	_
6	das	der	DET	DT	Case=Nom|Definite=Def|Gender=Neut|Number=Sing|Person=3	8	det	_	_
7	erlaubte	erlaubt	ADJ	JJ	Case=Nom|Degree=Pos|Gender=Neut|Number=Sing|Person=3	8	amod	_	InflectionType=Weak
8	Maximum	Maximum	NOUN	NN	Case=Nom|Gender=Neut|Number=Sing|Person=3	2	appos	_	SpaceAfter=No
9	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 12 nummod	color:blue
1	Investitionen	Investition	NOUN	NN	Case=Nom|Gender=Fem|Number=Plur|Person=3	14	nsubj	_	_
2	in	in	ADP	IN	_	4	case	_	_
3	diesem	dies	DET	DT	Case=Dat|Definite=Def|Gender=Masc|Number=Sing|Person=3	4	det	_	_
4	Bereich	Bereich	NOUN	NN	Case=Dat|Gender=Masc|Number=Sing|Person=3	1	nmod	_	_
5	sind	sein	AUX	VBC	Mood=Ind|Number=Plur|Person=3|Tense=Pres	14	aux	_	_
6	2015	2015	NUM	CD	NumType=Card	14	obl:tmod	_	_
7	um	um	ADP	IN	_	9	case	_	_
8	6	6	NUM	CD	NumType=Card	9	nummod	_	_
9	%	%	SYM	SYM	_	14	obl	_	_
10	auf	auf	ADP	IN	_	13	case	_	_
11	221	221	NUM	CD	NumType=Card	12	nummod	_	_
12	Milliarden	Milliarde	NOUN	NN	Case=Acc|Gender=Fem|Number=Plur|Person=3	13	nummod	_	_
13	Dollar	Dollar	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	14	obl	_	Proper=True
14	gestiegen	steigen	VERB	VBN	Tense=Past	0	root	_	SpaceAfter=No
15	.	.	PUNCT	.	_	14	punct	_	_

~~~


