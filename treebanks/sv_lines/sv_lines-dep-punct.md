---
layout: base
title:  'Statistics of punct in UD_Swedish-LinES'
udver: '2'
---

## Treebank Statistics: UD_Swedish-LinES: Relations: `punct`

This relation is universal.

8653 nodes (11%) are attached to their parents as `punct`.

7171 instances of `punct` (83%) are left-to-right (parent precedes child).
Average distance between parent and child is 9.03732809430255.

The following 17 pairs of parts of speech are connected with `punct`: <tt><a href="sv_lines-pos-VERB.html">VERB</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (5688; 66% instances), <tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (1412; 16% instances), <tt><a href="sv_lines-pos-ADJ.html">ADJ</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (676; 8% instances), <tt><a href="sv_lines-pos-PROPN.html">PROPN</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (195; 2% instances), <tt><a href="sv_lines-pos-ADV.html">ADV</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (184; 2% instances), <tt><a href="sv_lines-pos-PRON.html">PRON</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (159; 2% instances), <tt><a href="sv_lines-pos-INTJ.html">INTJ</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (148; 2% instances), <tt><a href="sv_lines-pos-NUM.html">NUM</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (50; 1% instances), <tt><a href="sv_lines-pos-ADP.html">ADP</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (47; 1% instances), <tt><a href="sv_lines-pos-AUX.html">AUX</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (30; 0% instances), <tt><a href="sv_lines-pos-X.html">X</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (27; 0% instances), <tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (20; 0% instances), <tt><a href="sv_lines-pos-PART.html">PART</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (8; 0% instances), <tt><a href="sv_lines-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances), <tt><a href="sv_lines-pos-DET.html">DET</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (2; 0% instances), <tt><a href="sv_lines-pos-SYM.html">SYM</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (2; 0% instances), <tt><a href="sv_lines-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="sv_lines-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 punct	color:blue
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
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 punct	color:blue
1	Storlek	storlek	NOUN	SG-IND-NOM	Case=Nom|Definite=Ind|Gender=Com|Number=Sing	0	root	_	SpaceAfter=No
2	.	.	PUNCT	Period	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 6 punct	color:blue
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


