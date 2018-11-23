---
layout: base
title:  'Statistics of csubj in UD_Italian-PoSTWITA'
udver: '2'
---

## Treebank Statistics: UD_Italian-PoSTWITA: Relations: `csubj`

This relation is universal.

209 nodes (0%) are attached to their parents as `csubj`.

135 instances of `csubj` (65%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.89473684210526.

The following 14 pairs of parts of speech are connected with `csubj`: <tt><a href="it_postwita-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (83; 40% instances), <tt><a href="it_postwita-pos-VERB.html">VERB</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (59; 28% instances), <tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (47; 22% instances), <tt><a href="it_postwita-pos-ADV.html">ADV</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (5; 2% instances), <tt><a href="it_postwita-pos-PRON.html">PRON</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (4; 2% instances), <tt><a href="it_postwita-pos-VERB.html">VERB</a></tt>-<tt><a href="it_postwita-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="it_postwita-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_postwita-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_postwita-pos-INTJ.html">INTJ</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_postwita-pos-SYM.html">SYM</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-PROPN.html">PROPN</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-SYM.html">SYM</a></tt>-<tt><a href="it_postwita-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-VERB.html">VERB</a></tt>-<tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="it_postwita-pos-VERB.html">VERB</a></tt>-<tt><a href="it_postwita-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 15 csubj	color:blue
1	'	'	PUNCT	FB	_	2	punct	_	_
2	dicono	dire	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	che	che	SCONJ	CS	_	5	mark	_	_
4	è	essere	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	cop	_	_
5	vero	vero	ADJ	A	Gender=Masc|Number=Sing	2	ccomp	_	_
6	che	che	SCONJ	CS	_	15	mark	_	_
7	quando	quando	SCONJ	CS	_	9	mark	_	_
8	si	si	PRON	PC	Clitic=Yes|Person=3|PronType=Prs	9	expl:impers	_	_
9	muore	morire	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	15	advcl	_	SpaceAfter=No
10	,	,	PUNCT	FF	_	9	punct	_	_
11	poi	poi	ADV	B	_	15	advmod	_	_
12	non	non	ADV	BN	PronType=Neg	15	advmod	_	_
13	ci	ci	PRON	PC	Clitic=Yes|Number=Plur|Person=1|PronType=Prs	15	expl	_	_
14	si	si	PRON	PC	Clitic=Yes|Person=3|PronType=Prs	15	expl:impers	_	_
15	vede	vedere	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	csubj	_	_
16	più'	più'	ADV	B	_	15	advmod	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 4 csubj	color:blue
1	RT	retweet	NOUN	S	_	8	dep	_	_
2	@user	@user	SYM	SYM	_	8	vocative:mention	_	SpaceAfter=No
3	:	:	PUNCT	FC	_	2	punct	_	_
4	avere	avere	VERB	V	VerbForm=Inf	8	csubj	_	_
5	un	uno	DET	RI	Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	6	det	_	_
6	carattere	carattere	NOUN	S	Gender=Masc|Number=Sing	4	obj	_	_
7	forte	forte	ADJ	A	Number=Sing	6	amod	_	_
8	ha	avere	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
9	molto	molto	DET	DI	PronType=Ind	10	det	_	_
10	lati	lato	NOUN	S	Gender=Masc|Number=Plur	8	obj	_	_
11	negativi	negativo	ADJ	A	Gender=Masc|Number=Plur	10	amod	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 5 csubj	color:blue
1	MARIO	mario	PROPN	SP	_	10	vocative	_	_
2	MONTI	MONTI	PROPN	SP	_	1	flat:name	_	_
3	MASSONE	massone	NOUN	S	Gender=Masc|Number=Sing	1	nmod	_	SpaceAfter=No
4	,	,	PUNCT	FF	_	1	punct	_	_
5	SERVIRE	servire	VERB	V	VerbForm=Inf	10	csubj	_	_
6	LE	il	DET	RD	Definite=Def|Gender=Fem|Number=Plur|PronType=Art	7	det	_	_
7	BANCHE	banca	NOUN	S	Gender=Fem|Number=Plur	5	obj	_	_
8	LA	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	10	det	_	_
9	TUA	tuo	DET	AP	Gender=Fem|Number=Sing|Poss=Yes|PronType=Prs	10	det:poss	_	_
10	PROFESSIONE	professione	NOUN	S	Gender=Fem|Number=Sing	0	root	_	_
11	NTA	NTA	X	X	_	10	dep	_	_

~~~


