---
layout: base
title:  'Statistics of aux in UD_Russian-SynTagRus'
udver: '2'
---

## Treebank Statistics: UD_Russian-SynTagRus: Relations: `aux`

This relation is universal.
There are 1 language-specific subtypes of `aux`: <tt><a href="ru_syntagrus-dep-aux-pass.html">aux:pass</a></tt>.

2446 nodes (0%) are attached to their parents as `aux`.

1577 instances of `aux` (64%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.64636140637776.

The following 10 pairs of parts of speech are connected with `aux`: <tt><a href="ru_syntagrus-pos-VERB.html">VERB</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (1190; 49% instances), <tt><a href="ru_syntagrus-pos-VERB.html">VERB</a></tt>-<tt><a href="ru_syntagrus-pos-AUX.html">AUX</a></tt> (923; 38% instances), <tt><a href="ru_syntagrus-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (180; 7% instances), <tt><a href="ru_syntagrus-pos-ADV.html">ADV</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (80; 3% instances), <tt><a href="ru_syntagrus-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (55; 2% instances), <tt><a href="ru_syntagrus-pos-PRON.html">PRON</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (8; 0% instances), <tt><a href="ru_syntagrus-pos-DET.html">DET</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (4; 0% instances), <tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (3; 0% instances), <tt><a href="ru_syntagrus-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ru_syntagrus-pos-PART.html">PART</a></tt> (2; 0% instances), <tt><a href="ru_syntagrus-pos-NUM.html">NUM</a></tt>-<tt><a href="ru_syntagrus-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 aux	color:blue
1	-	-	PUNCT	_	_	3	punct	3:punct	_
2	Я	я	PRON	_	Case=Nom|Number=Sing|Person=1	3	nsubj	3:nsubj	_
3	хотел	хотеть	VERB	_	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin|Voice=Act	0	root	0:root	_
4	бы	бы	PART	_	Mood=Cnd	3	aux	3:aux	_
5	вернуться	вернуться	VERB	_	Aspect=Perf|VerbForm=Inf|Voice=Mid	3	xcomp	3:xcomp	SpaceAfter=No
6	,	,	PUNCT	_	_	11	punct	11:punct	_
7	пока	пока	SCONJ	_	_	11	mark	11:mark	_
8	еще	еще	ADV	_	Degree=Pos	10	advmod	10:advmod	_
9	не	не	PART	_	_	10	advmod	10:advmod	_
10	очень	очень	ADV	_	Degree=Pos	11	advmod	11:advmod	_
11	много	много	ADV	_	Degree=Pos	5	advmod	5:advmod	_
12	машин	машина	NOUN	_	Animacy=Inan|Case=Gen|Gender=Fem|Number=Plur	11	obl	11:obl	SpaceAfter=No
13	.	.	PUNCT	_	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 aux	color:blue
1	Не	не	PART	_	_	3	advmod	3:advmod	_
2	будем	быть	AUX	_	Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	3	aux	3:aux	_
3	копировать	копировать	VERB	_	Aspect=Imp|VerbForm=Inf|Voice=Act	0	root	0:root	_
4	американский	американский	ADJ	_	Animacy=Inan|Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	6	amod	6:amod	_
5	"	"	PUNCT	_	_	6	punct	6:punct	SpaceAfter=No
6	Шаттл	шаттл	NOUN	_	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	3	obj	3:obj	SpaceAfter=No
7	"	"	PUNCT	_	_	6	punct	6:punct	SpaceAfter=No
8	!	!	PUNCT	_	_	6	punct	6:punct	SpaceAfter=No
9	"	"	PUNCT	_	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 aux	color:blue
1	Это	это	PRON	_	Animacy=Inan|Case=Nom|Gender=Neut|Number=Sing	4	nsubj	4:nsubj	_
2	было	быть	AUX	_	Aspect=Imp|Gender=Neut|Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin|Voice=Act	4	cop	4:cop	_
3	бы	бы	PART	_	Mood=Cnd	4	aux	4:aux	_
4	смешно	смешной	ADJ	_	Degree=Pos|Gender=Neut|Number=Sing|Variant=Short	0	root	0:root	SpaceAfter=No
5	.	.	PUNCT	_	_	4	punct	4:punct	_

~~~


