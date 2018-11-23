---
layout: base
title:  'Statistics of aux in UD_English-LinES'
udver: '2'
---

## Treebank Statistics: UD_English-LinES: Relations: `aux`

This relation is universal.
There are 1 language-specific subtypes of `aux`: <tt><a href="en_lines-dep-aux-pass.html">aux:pass</a></tt>.

2441 nodes (3%) are attached to their parents as `aux`.

2432 instances of `aux` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.66816878328554.

The following 19 pairs of parts of speech are connected with `aux`: <tt><a href="en_lines-pos-VERB.html">VERB</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (2094; 86% instances), <tt><a href="en_lines-pos-VERB.html">VERB</a></tt>-<tt><a href="en_lines-pos-VERB.html">VERB</a></tt> (130; 5% instances), <tt><a href="en_lines-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (91; 4% instances), <tt><a href="en_lines-pos-AUX.html">AUX</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (58; 2% instances), <tt><a href="en_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (41; 2% instances), <tt><a href="en_lines-pos-PRON.html">PRON</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (8; 0% instances), <tt><a href="en_lines-pos-ADV.html">ADV</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (3; 0% instances), <tt><a href="en_lines-pos-ADP.html">ADP</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="en_lines-pos-AUX.html">AUX</a></tt>-<tt><a href="en_lines-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="en_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_lines-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="en_lines-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="en_lines-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_lines-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-DET.html">DET</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_lines-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-NUM.html">NUM</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-PRON.html">PRON</a></tt>-<tt><a href="en_lines-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_lines-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="en_lines-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="en_lines-pos-VERB.html">VERB</a></tt>-<tt><a href="en_lines-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 aux	color:blue
1	The	the	DET	DEF	Definite=Def|PronType=Art	4	det	_	_
2	SQL	sql	PROPN	SG-NOM	Number=Sing	4	compound	_	_
3	Server	server	NOUN	SG-NOM	Number=Sing	2	flat	_	_
4	database	database	NOUN	SG-NOM	Number=Sing	7	nsubj	_	_
5	must	must	AUX	PRES-AUX	VerbForm=Fin	7	aux	_	_
6	be	be	AUX	INF	VerbForm=Inf	7	aux	_	_
7	running	run	VERB	ING	Tense=Pres|VerbForm=Part	0	root	_	_
8	on	on	ADP	_	_	12	case	_	_
9	a	a	DET	IND-SG	Definite=Ind|PronType=Art	12	det	_	_
10	Windows	window	PROPN	SG-NOM	Case=Nom	12	compound	_	_
11	NT	nt	PROPN	SG-NOM	Case=Nom	10	flat	_	_
12	platform	platform	NOUN	SG-NOM	Number=Sing	7	obl	_	SpaceAfter=No
13	.	.	PUNCT	Period	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 aux	color:blue
1	How	how	ADV	WH	PronType=Int	5	advmod	_	_
2	do	do	VERB	PRES	Mood=Ind|Tense=Pres|VerbForm=Fin	5	aux	_	_
3	you	you	PRON	PERS-P2	_	5	nsubj	_	_
4	English	English	ADJ	POS	Degree=Pos	3	amod	_	_
5	say	say	VERB	INF	VerbForm=Inf	0	root	_	SpaceAfter=No
6	,	,	PUNCT	_	_	9	punct	_	_
7	eh	eh	INTJ	_	_	5	parataxis	_	SpaceAfter=No
8	?	?	PUNCT	QuestionMark	_	5	punct	_	_
9	Good-by	good-bye	INTJ	_	_	5	appos	_	SpaceAfter=No
10	.	.	PUNCT	Period	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 4 aux	color:blue
1	Such	such	ADJ	ADJ	_	3	amod	_	_
2	intelligent	intelligent	ADJ	POS	Degree=Pos	3	amod	_	_
3	discussion	discussion	NOUN	SG-NOM	Number=Sing	8	nsubj	_	_
4	has	have	AUX	PRES-AUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	8	aux	_	SpaceAfter=No
5	n't	not	PART	NEG	_	8	advmod	_	_
6	always	always	ADV	_	_	8	advmod	_	_
7	been	be	AUX	PERF	Tense=Past|VerbForm=Part	8	cop	_	_
8	wrong	wrong	ADJ	POS	Degree=Pos	0	root	_	SpaceAfter=No
9	.	.	PUNCT	Period	_	8	punct	_	_

~~~


