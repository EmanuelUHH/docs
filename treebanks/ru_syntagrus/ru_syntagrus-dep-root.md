---
layout: base
title:  'Statistics of root in UD_Russian-SynTagRus'
udver: '2'
---

## Treebank Statistics: UD_Russian-SynTagRus: Relations: `root`

This relation is universal.

61889 nodes (6%) are attached to their parents as `root`.

61889 instances of `root` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.85687278837919.

The following 14 pairs of parts of speech are connected with `root`: -<tt><a href="ru_syntagrus-pos-VERB.html">VERB</a></tt> (44132; 71% instances), -<tt><a href="ru_syntagrus-pos-NOUN.html">NOUN</a></tt> (6956; 11% instances), -<tt><a href="ru_syntagrus-pos-ADJ.html">ADJ</a></tt> (6291; 10% instances), -<tt><a href="ru_syntagrus-pos-ADV.html">ADV</a></tt> (2471; 4% instances), -<tt><a href="ru_syntagrus-pos-PRON.html">PRON</a></tt> (789; 1% instances), -<tt><a href="ru_syntagrus-pos-PROPN.html">PROPN</a></tt> (523; 1% instances), -<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (261; 0% instances), -<tt><a href="ru_syntagrus-pos-NUM.html">NUM</a></tt> (232; 0% instances), -<tt><a href="ru_syntagrus-pos-DET.html">DET</a></tt> (160; 0% instances), -<tt><a href="ru_syntagrus-pos-INTJ.html">INTJ</a></tt> (23; 0% instances), -<tt><a href="ru_syntagrus-pos-SYM.html">SYM</a></tt> (19; 0% instances), -<tt><a href="ru_syntagrus-pos-ADP.html">ADP</a></tt> (13; 0% instances), -<tt><a href="ru_syntagrus-pos-CCONJ.html">CCONJ</a></tt> (12; 0% instances), -<tt><a href="ru_syntagrus-pos-X.html">X</a></tt> (7; 0% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 10 root	color:blue
1	Единого	единый	ADJ	_	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing	5	amod	5:amod	_
2	"	"	PUNCT	_	_	3	punct	3:punct	SpaceAfter=No
3	истинного	истинный	ADJ	_	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing	5	amod	5:amod	SpaceAfter=No
4	"	"	PUNCT	_	_	3	punct	3:punct	_
5	определения	определение	NOUN	_	Animacy=Inan|Case=Gen|Gender=Neut|Number=Sing	10	nsubj	10:nsubj	_
6	понятия	понятие	NOUN	_	Animacy=Inan|Case=Gen|Gender=Neut|Number=Sing	5	nmod	5:nmod	_
7	"	"	PUNCT	_	_	8	punct	8:punct	SpaceAfter=No
8	алгоритм	алгоритм	NOUN	_	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	6	appos	6:appos	SpaceAfter=No
9	"	"	PUNCT	_	_	8	punct	8:punct	_
10	нет	нет	VERB	_	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	SpaceAfter=No
11	.	.	PUNCT	_	_	10	punct	10:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 1 root	color:blue
1	Определения	определение	NOUN	_	Animacy=Inan|Case=Nom|Gender=Neut|Number=Plur	0	root	0:root	_
2	алгоритма	алгоритм	NOUN	_	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing	1	nmod	1:nmod	SpaceAfter=No
3	.	.	PUNCT	_	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 2 root	color:blue
1	Алгоритм	алгоритм	NOUN	_	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	2	nsubj	2:nsubj	_
2	должен	должен	ADJ	_	Degree=Pos|Gender=Masc|Number=Sing|Variant=Short	0	root	0:root	_
3	быть	быть	AUX	_	Aspect=Imp|VerbForm=Inf|Voice=Act	4	cop	4:cop	_
4	применим	применимый	ADJ	_	Degree=Pos|Gender=Masc|Number=Sing|Variant=Short	2	xcomp	2:xcomp	_
5	к	к	ADP	_	_	7	case	7:case	_
6	разным	разный	ADJ	_	Case=Dat|Degree=Pos|Number=Plur	7	amod	7:amod	_
7	наборам	набор	NOUN	_	Animacy=Inan|Case=Dat|Gender=Masc|Number=Plur	4	obl	4:obl	_
8	исходных	исходный	ADJ	_	Case=Gen|Degree=Pos|Number=Plur	9	amod	9:amod	_
9	данных	данные	NOUN	_	Animacy=Inan|Case=Gen|Number=Plur	7	nmod	7:nmod	SpaceAfter=No
10	.	.	PUNCT	_	_	2	punct	2:punct	_

~~~


