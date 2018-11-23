---
layout: base
title:  'Statistics of cop in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `cop`

This relation is universal.

1442 nodes (2%) are attached to their parents as `cop`.

1409 instances of `cop` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.2621359223301.

The following 13 pairs of parts of speech are connected with `cop`: <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (603; 42% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (596; 41% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (81; 6% instances), <tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (52; 4% instances), <tt><a href="en_gum-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (36; 2% instances), <tt><a href="en_gum-pos-NUM.html">NUM</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (34; 2% instances), <tt><a href="en_gum-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (21; 1% instances), <tt><a href="en_gum-pos-ADP.html">ADP</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (8; 1% instances), <tt><a href="en_gum-pos-X.html">X</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (5; 0% instances), <tt><a href="en_gum-pos-PART.html">PART</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-INTJ.html">INTJ</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-SYM.html">SYM</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 cop	color:blue
1	On	on	ADP	IN	_	3	case	_	_
2	the	the	DET	DT	Definite=Def|PronType=Art	3	det	_	_
3	floor	floor	NOUN	NN	Number=Sing	6	nmod	_	_
4	was	be	AUX	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	6	cop	_	_
5	a	a	DET	DT	Definite=Ind|PronType=Art	6	det	_	_
6	wrapper	wrapper	NOUN	NN	Number=Sing	0	root	_	_
7	from	from	ADP	IN	_	10	case	_	_
8	a	a	DET	DT	Definite=Ind|PronType=Art	10	det	_	_
9	French	French	PROPN	NNP	Number=Sing	10	compound	_	_
10	Chew	Chew	PROPN	NNP	Number=Sing	6	nmod	_	SpaceAfter=No
11	.	.	PUNCT	.	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 cop	color:blue
1	It	it	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	3	nsubj	_	_
2	was	be	AUX	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	3	cop	_	_
3	dark	dark	ADJ	JJ	Degree=Pos	0	root	_	_
4	under	under	ADP	IN	_	6	case	_	_
5	the	the	DET	DT	Definite=Def|PronType=Art	6	det	_	_
6	bleachers	bleacher	NOUN	NNS	Number=Plur	3	obl	_	SpaceAfter=No
7	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 2 cop	color:blue
1	That	that	PRON	DT	Number=Sing|PronType=Dem	10	nsubj	_	_
2	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	_	SpaceAfter=No
3	,	,	PUNCT	,	_	2	punct	_	_
4	of	of	ADP	IN	_	5	case	_	_
5	course	course	NOUN	NN	Number=Sing	10	obl	_	SpaceAfter=No
6	,	,	PUNCT	,	_	5	punct	_	_
7	if	if	SCONJ	IN	_	10	mark	_	_
8	you	you	PRON	PRP	Case=Nom|Person=2|PronType=Prs	10	nsubj	_	_
9	can	can	AUX	MD	VerbForm=Fin	10	aux	_	_
10	get	get	VERB	VB	VerbForm=Inf	0	root	_	_
11	a	a	DET	DT	Definite=Ind|PronType=Art	12	det	_	_
12	laugh	laugh	NOUN	NN	Number=Sing	10	obj	_	SpaceAfter=No
13	.	.	PUNCT	.	_	10	punct	_	_

~~~


