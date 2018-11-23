---
layout: base
title:  'Statistics of root in UD_Swedish-LinES'
udver: '2'
---

## Treebank Statistics: UD_Swedish-LinES: Relations: `root`

This relation is universal.

4564 nodes (6%) are attached to their parents as `root`.

4564 instances of `root` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.46801051709027.

The following 13 pairs of parts of speech are connected with `root`: -<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (3547; 78% instances), -<tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt> (493; 11% instances), -<tt><a href="sv_lines-pos-ADJ.html">ADJ</a></tt> (307; 7% instances), -<tt><a href="sv_lines-pos-PRON.html">PRON</a></tt> (80; 2% instances), -<tt><a href="sv_lines-pos-PROPN.html">PROPN</a></tt> (44; 1% instances), -<tt><a href="sv_lines-pos-ADV.html">ADV</a></tt> (39; 1% instances), -<tt><a href="sv_lines-pos-INTJ.html">INTJ</a></tt> (22; 0% instances), -<tt><a href="sv_lines-pos-AUX.html">AUX</a></tt> (14; 0% instances), -<tt><a href="sv_lines-pos-NUM.html">NUM</a></tt> (10; 0% instances), -<tt><a href="sv_lines-pos-CCONJ.html">CCONJ</a></tt> (4; 0% instances), -<tt><a href="sv_lines-pos-PART.html">PART</a></tt> (2; 0% instances), -<tt><a href="sv_lines-pos-ADP.html">ADP</a></tt> (1; 0% instances), -<tt><a href="sv_lines-pos-SYM.html">SYM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 4 root	color:blue
1	SQL	SQL	PROPN	SG-NOM	Case=Nom	2	nmod	_	_
2	Server-databasen	server-databas	NOUN	SG-DEF-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing	4	nsubj:pass	_	_
3	måste	måste	AUX	AUX	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	4	aux	_	_
4	köras	köra	VERB	INF-PASS	VerbForm=Inf|Voice=Pass	0	root	_	_
5	på	på	ADP	_	_	6	case	_	_
6	Windows	Windows	PROPN	SG-NOM	Case=Nom	4	obl	_	_
7	NT	NT	PROPN	SG-NOM	Case=Nom	6	flat	_	SpaceAfter=No
8	.	.	PUNCT	Period	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 2 root	color:blue
1	Om	om	ADP	_	_	2	case	_	_
2	XML-data	XML-data	NOUN	PL-IND-NOM	Case=Nom|Definite=Ind|Gender=Neut|Number=Plur	0	root	_	_
3	och	och	CCONJ	_	_	4	cc	_	_
4	Access	Access	PROPN	SG-NOM	Case=Nom	2	conj	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 5 root	color:blue
1	Jadå	jadå	INTJ	_	_	5	discourse	_	SpaceAfter=No
2	,	,	PUNCT	Comma	_	1	punct	_	_
3	han	han	PRON	PERS-P3SG-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing|PronType=Prs	5	nsubj	_	_
4	är	vara	AUX	PRES-ACT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	5	cop	_	_
5	smart	smart	ADJ	POS-SG-IND	Case=Nom|Definite=Ind|Degree=Pos|Number=Sing	0	root	_	SpaceAfter=No
6	.	.	PUNCT	Period	_	5	punct	_	_
7	Men	men	CCONJ	_	_	9	cc	_	_
8	han	han	PRON	PERS-P3SG-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing|PronType=Prs	9	nsubj	_	_
9	pratar	prata	VERB	PRES-ACT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	5	conj	_	_
10	för	för	ADV	_	_	11	advmod	_	_
11	mycket	mycket	ADV	_	Degree=Pos	9	advmod	_	SpaceAfter=No
12	.	.	PUNCT	Period	_	9	punct	_	_

~~~


