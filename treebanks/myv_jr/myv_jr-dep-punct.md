---
layout: base
title:  'Statistics of punct in UD_Erzya-JR'
udver: '2'
---

## Treebank Statistics: UD_Erzya-JR: Relations: `punct`

This relation is universal.

3783 nodes (24%) are attached to their parents as `punct`.

2073 instances of `punct` (55%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.02061855670103.

The following 18 pairs of parts of speech are connected with `punct`: <tt><a href="myv_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (2497; 66% instances), <tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (604; 16% instances), <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (173; 5% instances), <tt><a href="myv_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (137; 4% instances), <tt><a href="myv_jr-pos-INTJ.html">INTJ</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (112; 3% instances), <tt><a href="myv_jr-pos-PRON.html">PRON</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (87; 2% instances), <tt><a href="myv_jr-pos-PROPN.html">PROPN</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (68; 2% instances), <tt><a href="myv_jr-pos-AUX.html">AUX</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (45; 1% instances), <tt><a href="myv_jr-pos-PART.html">PART</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (22; 1% instances), <tt><a href="myv_jr-pos-NUM.html">NUM</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (13; 0% instances), <tt><a href="myv_jr-pos-ADP.html">ADP</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (9; 0% instances), <tt><a href="myv_jr-pos-DET.html">DET</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (6; 0% instances), <tt><a href="myv_jr-pos-X.html">X</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (3; 0% instances), <tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (2; 0% instances), <tt><a href="myv_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="myv_jr-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="myv_jr-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances), <tt><a href="myv_jr-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="myv_jr-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances), <tt><a href="myv_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="myv_jr-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 punct	color:blue
1	Велень	веле	NOUN	N	Case=Gen|Definite=Ind|Number=Plur,Sing	2	nmod	_	GTtags=Sem/Plc,SP,Gen,Indef
2	росась	роса	NOUN	N	Case=Nom|Definite=Def|Number=Sing	4	nsubj	_	GTtags=Sg,Nom,Def
3	эзь	эзь	AUX	Aux	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Polarity=Neg|Tense=Prt1|VerbType=Aux	4	aux:neg	_	_
4	костявт	костявомс	VERB	V	Connegative=Yes|Mood=Ind|Valency=1	0	root	_	GTtags=IV,Ind,ConNeg
5	валске	валске	NOUN	N	AdvType=Tim|Case=Nom|Definite=Ind|Number=Sing	7	amod	_	GTtags=Temp,Sg,Nom,Indef
6	мартонь	марто	ADP	Adp	Case=Gen|Definite=Ind|Number=Plur,Sing	5	fixed	_	GTtags=Der/MWN,N,SP,Gen,Indef
7	чипайсэнть	чипай	NOUN	N	Case=Ine|Definite=Def|Number=Sing	4	obl	_	GTtags=Sg,Ine,Def|SpaceAfter=No
8	.	.	PUNCT	CLB	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 punct	color:blue
1	Турванзо	турва	NOUN	N	Case=Nom|Number=Plur|Number[psor]=Sing|Person[psor]=3	2	nsubj	_	GTtags=Pl,Nom,PxSg3
2	равжо-сэн	равжо-сэнь	ADJ	A	_	0	root	_	_
3	ть	оль	AUX	Cop	Number[subj]=Plur|Person[subj]=3|Tense=Pres	2	cop	_	GTtags=Prs,ScPl3
4	,	,	PUNCT	CLB	_	5	punct	_	_
5	чамазо	чама	NOUN	N	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	11	nsubj	_	GTtags=Sg,Nom,PxSg3|SpaceAfter=No
6	,	,	PUNCT	CLB	_	8	punct	_	_
7	прок	прок	CCONJ	CC	_	8	mark	_	_
8	лияназ	лияназ	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	11	advcl	_	GTtags=Sg,Nom,Indef
9	коцт	коцт	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	8	goeswith	_	GTtags=Sg,Nom,Indef|SpaceAfter=No
10	,	,	PUNCT	CLB	_	8	punct	_	_
11	ашо	ашо	ADJ	A	_	2	conj	_	_
12	_	оль	AUX	Cop	Number[subj]=Sing|Person[subj]=3|Tense=Pres	11	cop	_	GTtags=Prs,ScSg3
13	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 punct	color:blue
1	Лиссь	лисемс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Prt1|Valency=1	0	root	_	GTtags=IV,Ind,Prt1,ScSg3
2	Ястребов	Ястребов	PROPN	N	Animacy=Hum|Case=Nom|Definite=Ind|Gender=Masc|NameType=Sur|Number=Sing	1	nsubj	_	GTtags=Prop,Sur_Mal,Sg,Nom,Indef|SpaceAfter=No
3	,	,	PUNCT	CLB	_	5	punct	_	_
4	седеяк	седеяк	PART	Pcle	Clitic=Gak|Degree=Cmp	5	advmod	_	GTtags=Degree=Cmp,Clt/Gak
5	нусманясто	нусманясто	ADV	Adv	AdvType=Sta	2	acl	_	GTtags=State|SpaceAfter=No
6	.	.	PUNCT	CLB	_	1	punct	_	_

~~~


