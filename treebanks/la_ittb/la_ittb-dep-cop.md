---
layout: base
title:  'Statistics of cop in UD_Latin-ITTB'
udver: '2'
---

## Treebank Statistics: UD_Latin-ITTB: Relations: `cop`

This relation is universal.

11210 nodes (3%) are attached to their parents as `cop`.

8244 instances of `cop` (74%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.50695807314897.

The following 17 pairs of parts of speech are connected with `cop`: <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (4404; 39% instances), <tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (4388; 39% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (1294; 12% instances), <tt><a href="la_ittb-pos-PRON.html">PRON</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (794; 7% instances), <tt><a href="la_ittb-pos-NUM.html">NUM</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (188; 2% instances), <tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (86; 1% instances), <tt><a href="la_ittb-pos-ADV.html">ADV</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (32; 0% instances), <tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (7; 0% instances), <tt><a href="la_ittb-pos-X.html">X</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (5; 0% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (3; 0% instances), <tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_ittb-pos-CCONJ.html">CCONJ</a></tt> (2; 0% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-CCONJ.html">CCONJ</a></tt> (2; 0% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-PRON.html">PRON</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-PRON.html">PRON</a></tt>-<tt><a href="la_ittb-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-NUM.html">NUM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 cop	color:blue
1	finis	finis	NOUN	C1|grn1|casA|gen1	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	nsubj	_	_
2	enim	enim	ADV	O4	_	4	advmod	_	_
3	est	sum	AUX	N3|modA|tem1|gen6	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	_
4	bonum	bonum	NOUN	B1|grn1|casA|gen3	Case=Nom|Degree=Pos|Gender=Neut|Number=Sing	0	root	_	_
5	uniuscuiusque	unusquisque	PRON	F1|grn1|casB|gen3|vgr1	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing|PronType=Ind	4	nmod	_	SpaceAfter=No
6	.	.	PUNCT	Punc	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 cop	color:blue
1	quis	qui	PRON	F1|grn1|casA|gen1|varA	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|PronType=Rel	2	det	_	_
2	modus	modus	NOUN	B1|grn1|casA|gen1	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	nsubj	_	_
3	sit	sum	AUX	N3|modB|tem1|gen6	Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	_
4	possibilis	possibilis	ADJ	C1|grn1|casA|gen1	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	0	root	_	_
5	divinae	divinus	ADJ	A1|grn1|casB|gen2	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing	6	amod	_	_
6	veritatis	veritas	NOUN	C1|grn1|casB|gen2|vgr1	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing	7	nsubj:pass	_	_
7	manifestandae	manifesto	VERB	J2|modO|grp1|casB|gen2	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|VerbForm=Gdv|Voice=Pass	2	acl	_	SpaceAfter=No
8	.	.	PUNCT	Punc	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 cop	color:blue
1	quae	qui	PRON	F1|grn1|casA|gen2|vgr1	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing|PronType=Rel	6	nsubj	_	_
2	tamen	tamen	ADV	O4	_	6	advmod	_	_
3	in	in	ADP	S4	AdpType=Prep	4	case	_	_
4	rebus	res	NOUN	E1|grn1|casO|gen2	Case=Abl|Degree=Pos|Gender=Fem|Number=Plur	6	obl	_	_
5	divinis	divinus	ADJ	A1|grn1|casO|gen2|vgr1	Case=Abl|Degree=Pos|Gender=Fem|Number=Plur	4	amod	_	_
6	deficiens	deficio	VERB	L2|modD|tem1|grp1|casA|gen2	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing|Tense=Pres|VerbForm=Part|Voice=Act	0	root	_	_
7	est	sum	AUX	N3|modA|tem1|gen6	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	6	cop	_	SpaceAfter=No
8	.	.	PUNCT	Punc	_	6	punct	_	_

~~~


