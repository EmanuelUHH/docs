---
layout: base
title:  'Statistics of nummod in UD_Italian-ISDT'
udver: '2'
---

## Treebank Statistics: UD_Italian-ISDT: Relations: `nummod`

This relation is universal.

3590 nodes (1%) are attached to their parents as `nummod`.

2239 instances of `nummod` (62%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.97938718662953.

The following 14 pairs of parts of speech are connected with `nummod`: <tt><a href="it_isdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (2695; 75% instances), <tt><a href="it_isdt-pos-VERB.html">VERB</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (497; 14% instances), <tt><a href="it_isdt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (171; 5% instances), <tt><a href="it_isdt-pos-SYM.html">SYM</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (84; 2% instances), <tt><a href="it_isdt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (49; 1% instances), <tt><a href="it_isdt-pos-NUM.html">NUM</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (35; 1% instances), <tt><a href="it_isdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_isdt-pos-X.html">X</a></tt> (25; 1% instances), <tt><a href="it_isdt-pos-PRON.html">PRON</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (12; 0% instances), <tt><a href="it_isdt-pos-ADV.html">ADV</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (11; 0% instances), <tt><a href="it_isdt-pos-VERB.html">VERB</a></tt>-<tt><a href="it_isdt-pos-X.html">X</a></tt> (4; 0% instances), <tt><a href="it_isdt-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="it_isdt-pos-X.html">X</a></tt>-<tt><a href="it_isdt-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="it_isdt-pos-X.html">X</a></tt>-<tt><a href="it_isdt-pos-X.html">X</a></tt> (2; 0% instances), <tt><a href="it_isdt-pos-NUM.html">NUM</a></tt>-<tt><a href="it_isdt-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 nummod	color:blue
1	Corriere	Corriere	PROPN	SP	_	0	root	0:root	_
2	Sport	Sport	PROPN	SP	_	1	flat:name	1:flat:name	_
3	da	da	ADP	E	_	4	case	4:case	_
4	pagina	pagina	NOUN	S	Gender=Fem|Number=Sing	1	nmod	1:nmod:da	_
5	23	23	NUM	N	NumType=Card	4	nummod	4:nummod	_
6	a	a	ADP	E	_	7	case	7:case	_
7	pagina	pagina	NOUN	S	Gender=Fem|Number=Sing	1	nmod	1:nmod:a	_
8	26	26	NUM	N	NumType=Card	7	nummod	7:nummod	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 9 nummod	color:blue
1	L'	il	DET	RD	Definite=Def|Number=Sing|PronType=Art	2	det	2:det	SpaceAfter=No
2	usufruttuario	usufruttuario	NOUN	S	Gender=Masc|Number=Sing	5	nsubj	5:nsubj	_
3	deve	dovere	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	aux	5:aux	_
4	inoltre	inoltre	ADV	B	_	5	advmod	5:advmod	_
5	dare	dare	VERB	V	VerbForm=Inf	0	root	0:root	_
6	idonea	idoneo	ADJ	A	Gender=Fem|Number=Sing	7	amod	7:amod	_
7	garanzia	garanzia	NOUN	S	Gender=Fem|Number=Sing	5	obj	5:obj	_
8	(	(	PUNCT	FB	_	9	punct	9:punct	SpaceAfter=No
9	1179	1179	NUM	N	NumType=Card	5	nummod	5:nummod	SpaceAfter=No
10	)	)	PUNCT	FB	_	9	punct	9:punct	SpaceAfter=No
11	.	.	PUNCT	FS	_	5	punct	5:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 nummod	color:blue
1	Feb	Feb	PROPN	SP	_	0	root	0:root	_
2	26	26	NUM	N	NumType=Card	1	nummod	1:nummod	SpaceAfter=No
3	,	,	PUNCT	FF	_	2	punct	2:punct	_
4	2014	2014	NUM	N	NumType=Card	2	compound	2:compound	SpaceAfter=No
5	.	.	PUNCT	FS	_	1	punct	1:punct	_

~~~


