---
layout: base
title:  'Statistics of obj in UD_Greek-GDT'
udver: '2'
---

## Treebank Statistics: UD_Greek-GDT: Relations: `obj`

This relation is universal.

2382 nodes (4%) are attached to their parents as `obj`.

1990 instances of `obj` (84%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.51007556675063.

The following 10 pairs of parts of speech are connected with `obj`: <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-NOUN.html">NOUN</a></tt> (1856; 78% instances), <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-PRON.html">PRON</a></tt> (373; 16% instances), <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-PROPN.html">PROPN</a></tt> (47; 2% instances), <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-ADJ.html">ADJ</a></tt> (40; 2% instances), <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-X.html">X</a></tt> (35; 1% instances), <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-NUM.html">NUM</a></tt> (23; 1% instances), <tt><a href="el_gdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="el_gdt-pos-NOUN.html">NOUN</a></tt> (3; 0% instances), <tt><a href="el_gdt-pos-VERB.html">VERB</a></tt>-<tt><a href="el_gdt-pos-ADV.html">ADV</a></tt> (3; 0% instances), <tt><a href="el_gdt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="el_gdt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="el_gdt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="el_gdt-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 7 obj	color:blue
1	Θα	θα	PART	PART	_	2	aux	_	_
2	συνεχίσει	συνεχίζω	VERB	VERB	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No
3	,	,	PUNCT	PUNCT	_	4	punct	_	_
4	όμως	όμως	CCONJ	CCONJ	_	2	cc	_	SpaceAfter=No
5	,	,	PUNCT	PUNCT	_	4	punct	_	_
6	τη	ο	DET	DET	Case=Acc|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	7	det	_	_
7	διανομή	διανομή	NOUN	NOUN	Case=Acc|Gender=Fem|Number=Sing	2	obj	_	_
8	δεμάτων	δέμα	NOUN	NOUN	Case=Gen|Gender=Neut|Number=Plur	7	nmod	_	_
9	6	6	NUM	NUM	NumType=Card	10	nummod	_	_
10	μέρες	μέρα	NOUN	NOUN	Case=Acc|Gender=Fem|Number=Plur	7	nmod	_	_
11	την	ο	DET	DET	Case=Acc|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	12	det	_	_
12	εβδομάδα	εβδομάδα	NOUN	NOUN	Case=Acc|Gender=Fem|Number=Sing	10	nmod	_	SpaceAfter=No
13	"	"	PUNCT	PUNCT	_	10	punct	_	SpaceAfter=No
14	.	.	PUNCT	PUNCT	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 obj	color:blue
1	Τι	τι	PRON	PRON	Case=Acc|Gender=Neut|Number=Sing|Person=3|PronType=Int	2	obj	_	_
2	πράξαμε	πράττω	VERB	VERB	Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No
3	;	;	PUNCT	PUNCT	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 10 obj	color:blue
1	Τρεις	τρεις	NUM	NUM	Case=Nom|Gender=Masc|Number=Plur|NumType=Card	2	nummod	_	_
2	νεκροί	νεκρός	ADJ	ADJ	Case=Nom|Gender=Masc|Number=Plur	0	root	_	_
3	από	από	ADP	ADP	_	6	case	_	_
4	τη	ο	DET	DET	Case=Acc|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	6	det	_	_
5	σφοδρή	σφοδρός	ADJ	ADJ	Case=Acc|Gender=Fem|Number=Sing	6	amod	_	_
6	κακοκαιρία	κακοκαιρία	NOUN	NOUN	Case=Acc|Gender=Fem|Number=Sing	2	nmod	_	_
7	που	που	PRON	PRON	Case=Nom|Gender=Fem|Number=Sing|Person=3|PronType=Rel	8	nsubj	_	_
8	πλήττει	πλήττω	VERB	VERB	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	6	acl:relcl	_	_
9	τα	ο	DET	DET	Case=Acc|Definite=Def|Gender=Neut|Number=Plur|PronType=Art	10	det	_	_
10	Βαλκάνια	Βαλκάνια	PROPN	PROPN	Case=Acc|Gender=Neut|Number=Plur	8	obj	_	SpaceAfter=No
11	.	.	PUNCT	PUNCT	_	2	punct	_	_

~~~


