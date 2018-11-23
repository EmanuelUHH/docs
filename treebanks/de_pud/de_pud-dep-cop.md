---
layout: base
title:  'Statistics of cop in UD_German-PUD'
udver: '2'
---

## Treebank Statistics: UD_German-PUD: Relations: `cop`

This relation is universal.

335 nodes (2%) are attached to their parents as `cop`.

214 instances of `cop` (64%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.0089552238806.

The following 8 pairs of parts of speech are connected with `cop`: <tt><a href="de_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (182; 54% instances), <tt><a href="de_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (137; 41% instances), <tt><a href="de_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (7; 2% instances), <tt><a href="de_pud-pos-PRON.html">PRON</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (4; 1% instances), <tt><a href="de_pud-pos-NUM.html">NUM</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (2; 1% instances), <tt><a href="de_pud-pos-DET.html">DET</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="de_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="de_pud-pos-X.html">X</a></tt>-<tt><a href="de_pud-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 10 cop	color:blue
1	Was	was	PRON	WP	Case=Acc|Person=3	3	obj	_	_
2	sie	sie	PRON	PRP	Case=Nom|Gender=Fem|Number=Sing|Person=3	3	nsubj	_	_
3	sagt	sagen	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	0	root	_	_
4	und	und	CCONJ	CC	_	7	cc	_	_
5	was	was	PRON	WP	Case=Acc|Person=3	7	obj	_	_
6	sie	sie	PRON	PRP	Case=Nom|Gender=Fem|Number=Sing|Person=3	7	nsubj	_	_
7	tut	tun	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	3	conj	_	_
8	-	-	PUNCT	-	_	12	punct	_	_
9	eigentlich	eigentlich	ADV	RB	Degree=Pos	12	advmod	_	_
10	ist	sein	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	12	cop	_	_
11	es	es	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3	12	nsubj	_	_
12	unglaublich	unglaublich	ADJ	JJ	Degree=Pos	3	parataxis	_	SpaceAfter=No
13	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 2 cop	color:blue
1	Manchmal	manchmal	ADV	RB	Degree=Pos	6	advmod	_	_
2	ist	sein	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres	6	cop	_	_
3	das	der	DET	DT	Case=Nom|Definite=Def|Gender=Neut|Number=Sing|Person=3	6	nsubj	_	_
4	wie	wie	CCONJ	CC	_	6	cc	_	_
5	eine	ein	DET	DT	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing|Person=3	6	det	_	_
6	Superkraft	Superkraft	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	0	root	_	SpaceAfter=No
7	.	.	PUNCT	.	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 cop	color:blue
1	Ihr	Ihr|ihr	PRON	DTP$	Case=Nom|Gender=Masc|Number=Sing|Person=3|Person[psor]=3|PronType=Prs	3	nmod:poss	_	_
2	erster	erst	ADJ	JJ	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Person=3	3	amod	_	InflectionType=Mixed
3	König	König	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	nsubj	_	_
4	war	sein	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Past	5	cop	_	_
5	Mojmír	Mojmír	PROPN	NNP	Case=Nom|Gender=Masc|Number=Sing|Person=3	0	root	_	_
6	I.	I.	NOUN	NNA	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	appos	_	InflectionType=Weak|Proper=True
7	(	(	PUNCT	(	_	8	punct	_	SpaceAfter=No
8	herrschte	herrschen	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Past	5	parataxis	_	_
9	830	830	NUM	CD	NumType=Card	8	obl:tmod	_	_
10	-	-	NUM	_	NumType=Card	9	compound	_	_
11	846	846	NUM	_	NumType=Card	9	compound	_	SpaceAfter=No
12	)	)	PUNCT	)	_	8	punct	_	SpaceAfter=No
13	.	.	PUNCT	.	_	5	punct	_	_

~~~


