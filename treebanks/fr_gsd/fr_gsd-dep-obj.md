---
layout: base
title:  'Statistics of obj in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `obj`

This relation is universal.
There are 2 language-specific subtypes of `obj`: <tt><a href="fr_gsd-dep-obj-agent.html">obj:agent</a></tt>, <tt><a href="fr_gsd-dep-obj-lvc.html">obj:lvc</a></tt>.

13159 nodes (3%) are attached to their parents as `obj`.

11212 instances of `obj` (85%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.32563264685766.

The following 20 pairs of parts of speech are connected with `obj`: <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (10125; 77% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (2120; 16% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt> (651; 5% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-ADV.html">ADV</a></tt> (127; 1% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-SYM.html">SYM</a></tt> (53; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt> (26; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-X.html">X</a></tt> (17; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-ADJ.html">ADJ</a></tt> (16; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt> (5; 0% instances), <tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt> (3; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-DET.html">DET</a></tt> (3; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-SCONJ.html">SCONJ</a></tt> (3; 0% instances), <tt><a href="fr_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-INTJ.html">INTJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 11 obj	color:blue
1	Les	le	DET	_	Definite=Def|Gender=Fem|Number=Plur|PronType=Art	2	det	_	_
2	compagnies	compagnie	NOUN	_	Gender=Fem|Number=Plur	8	nsubj	_	_
3	aériennes	aérien	ADJ	_	Gender=Fem|Number=Plur	2	amod	_	_
4	à	à	ADP	_	_	6	case	_	_
5	bas	bas	ADJ	_	Gender=Masc|Number=Sing	6	amod	_	_
6	coût	coût	NOUN	_	Gender=Masc|Number=Sing	2	nmod	_	_
7	ne	ne	ADV	_	Polarity=Neg	8	advmod	_	_
8	connaissent	connaître	VERB	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
9	pas	pas	ADV	_	Polarity=Neg	8	advmod	_	_
10	la	le	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	11	det	_	_
11	crise	crise	NOUN	_	Gender=Fem|Number=Sing	8	obj	_	SpaceAfter=No
12	.	.	PUNCT	_	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 obj	color:blue
1	Pourquoi	pourquoi	ADV	_	_	6	advmod	_	SpaceAfter=No
2	,	,	PUNCT	_	_	1	punct	_	_
3	mais	mais	CCONJ	_	_	4	cc	_	_
4	pourquoi	pourquoi	ADV	_	_	1	advmod	_	_
5	Le	le	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Prs	6	obj	_	_
6	bénirais	bénir	VERB	_	Mood=Cnd|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
7	-je	je	PRON	_	Number=Sing|Person=1|PronType=Prs	6	nsubj	_	_
8	?	?	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 obj	color:blue
1	Elle	elle	PRON	_	Gender=Fem|Number=Sing|Person=3|PronType=Prs	3	nsubj	_	_
2	y	y	PRON	_	_	3	iobj	_	_
3	incarnera	incarner	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Fut|VerbForm=Fin	0	root	_	_
4	la	le	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	Poussette	Poussette	PROPN	_	_	3	obj	_	_
6	de	de	ADP	_	_	7	case	_	_
7	Manon	Manon	PROPN	_	_	5	nmod	_	_
8	peu	peu	ADV	_	_	10	det	_	MWEPOS=DET
9	de	un	DET	_	Definite=Ind|PronType=Art	8	fixed	_	_
10	temps	temps	NOUN	_	Gender=Masc|Number=Sing	3	obl	_	_
11	après	après	ADV	_	_	10	advmod	_	SpaceAfter=No
12	.	.	PUNCT	_	_	3	punct	_	_

~~~


