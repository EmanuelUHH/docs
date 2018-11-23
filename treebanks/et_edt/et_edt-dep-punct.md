---
layout: base
title:  'Statistics of punct in UD_Estonian-EDT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EDT: Relations: `punct`

This relation is universal.

70959 nodes (16%) are attached to their parents as `punct`.

40227 instances of `punct` (57%) are left-to-right (parent precedes child).
Average distance between parent and child is 6.08617652447188.

The following 15 pairs of parts of speech are connected with `punct`: <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (41212; 58% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (14217; 20% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (5291; 7% instances), <tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (4077; 6% instances), <tt><a href="et_edt-pos-NUM.html">NUM</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (1978; 3% instances), <tt><a href="et_edt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (1852; 3% instances), <tt><a href="et_edt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (1590; 2% instances), <tt><a href="et_edt-pos-SYM.html">SYM</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (271; 0% instances), <tt><a href="et_edt-pos-X.html">X</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (256; 0% instances), <tt><a href="et_edt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (180; 0% instances), <tt><a href="et_edt-pos-DET.html">DET</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (11; 0% instances), <tt><a href="et_edt-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (10; 0% instances), <tt><a href="et_edt-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (6; 0% instances), <tt><a href="et_edt-pos-ADP.html">ADP</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances), <tt><a href="et_edt-pos-AUX.html">AUX</a></tt>-<tt><a href="et_edt-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances).


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 11 punct	color:blue
1	Kust	kust	ADV	D	_	2	mark	_	_
2	tuli	tulema	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
3	mõte	mõte	NOUN	S	Case=Nom|Number=Sing	2	nsubj	_	_
4	kirjutada	kirjutama	VERB	V	VerbForm=Inf	3	acl	_	_
5	ooper	ooper	NOUN	S	Case=Nom|Number=Sing	4	obj	_	_
6	"	"	PUNCT	Z	_	7	punct	_	SpaceAfter=No
7	Writing	Writing	PROPN	S	Case=Nom|Number=Sing	5	appos	_	_
8	to	to	X	Y	Abbr=Yes	7	flat	_	_
9	Vermeer	Vermeer	PROPN	S	Case=Nom|Number=Sing	7	flat	_	SpaceAfter=No
10	"	"	PUNCT	Z	_	7	punct	_	SpaceAfter=No
11	?	?	PUNCT	Z	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 9 punct	color:blue
1	Huvitav	huvitav	ADJ	A	Case=Nom|Degree=Pos|Number=Sing	2	amod	_	_
2	küsimus	küsimus	NOUN	S	Case=Nom|Number=Sing	0	root	_	_
3	on	olema	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	2	cop	_	SpaceAfter=No
4	,	,	PUNCT	Z	_	8	punct	_	_
5	millest	mis	PRON	P	Case=Ela|Number=Sing|PronType=Int,Rel	8	obl	_	_
6	need	see	DET	P	Case=Nom|Number=Plur|PronType=Dem	7	det	_	_
7	kirjad	kiri	NOUN	S	Case=Nom|Number=Plur	8	nsubj	_	_
8	jutustavad	jutustama	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	2	csubj:cop	_	SpaceAfter=No
9	?	?	PUNCT	Z	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 3 punct	color:blue
1	Nagu	nagu	SCONJ	J	_	2	mark	_	_
2	Fellini	Fellini	PROPN	S	Case=Nom|Number=Sing	9	advcl	_	SpaceAfter=No
3	,	,	PUNCT	Z	_	9	punct	_	_
4	olete	olema	AUX	V	Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	9	cop	_	_
5	te	sina	PRON	P	Case=Nom|Number=Plur|Person=2|PronType=Prs	9	nsubj:cop	_	_
6	oma	oma	PRON	P	Case=Gen|Number=Sing|Poss=Yes|PronType=Prs	7	nmod	_	_
7	filmides	film	NOUN	S	Case=Ine|Number=Plur	9	obl	_	_
8	tohutult	tohutult	ADV	D	_	9	advmod	_	_
9	erootiline	erootiline	ADJ	A	Case=Nom|Degree=Pos|Number=Sing	0	root	_	SpaceAfter=No
10	.	.	PUNCT	Z	_	9	punct	_	_

~~~


