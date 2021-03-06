---
layout: base
title:  'Statistics of xcomp in UD_Galician-TreeGal'
udver: '2'
---

## Treebank Statistics: UD_Galician-TreeGal: Relations: `xcomp`

This relation is universal.

206 nodes (1%) are attached to their parents as `xcomp`.

205 instances of `xcomp` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.98543689320388.

The following 9 pairs of parts of speech are connected with `xcomp`: <tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt>-<tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt> (161; 78% instances), <tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt>-<tt><a href="gl_treegal-pos-ADJ.html">ADJ</a></tt> (21; 10% instances), <tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt>-<tt><a href="gl_treegal-pos-NOUN.html">NOUN</a></tt> (11; 5% instances), <tt><a href="gl_treegal-pos-ADJ.html">ADJ</a></tt>-<tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt> (7; 3% instances), <tt><a href="gl_treegal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="gl_treegal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gl_treegal-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="gl_treegal-pos-PRON.html">PRON</a></tt>-<tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="gl_treegal-pos-PROPN.html">PROPN</a></tt>-<tt><a href="gl_treegal-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="gl_treegal-pos-VERB.html">VERB</a></tt>-<tt><a href="gl_treegal-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 7 xcomp	color:blue
1	A	a	ADP	P	AdpType=Prep	3	case	_	_
2	as	o	DET	Ddfp	Definite=Def|Gender=Fem|Number=Plur|PronType=Art	3	det	_	_
3	cinco	cinco	NUM	Ncnfp	Gender=Fem|Number=Plur|NumType=Card	4	obl	_	_
4	remata	rematar	VERB	Vpi30s	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
5	se	se	PRON	Rao3aa	Clitic=Yes|Gender=Com|Person=3|PronType=Prs	4	expl	_	_
6	de	de	ADP	P	AdpType=Prep	7	mark	_	_
7	traballar	traballar	VERB	V0f000	VerbForm=Inf	4	xcomp	_	SpaceAfter=No
8	"	"	PUNCT	Q"	_	4	punct	_	SpaceAfter=No
9	.	.	PUNCT	Q.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 xcomp	color:blue
1	Mais	mais	SCONJ	Cs	_	4	mark	_	_
2	han	haber	AUX	Vpi30p	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	4	aux	_	_
3	de	de	ADP	P	AdpType=Prep	4	mark	_	_
4	voar	voar	VERB	V0f000	VerbForm=Inf	0	root	_	_
5	xa	xa	ADV	Wn	_	4	advmod	_	_
6	para	para	ADP	P	AdpType=Prep	10	mark	_	_
7	que	que	SCONJ	Cs	_	10	mark	_	_
8	non	non	ADV	Wn	Polarity=Neg	10	advmod	_	_
9	nos	nos	PRON	Raa1mp	Case=Acc|Clitic=Yes|Gender=Masc|Number=Plur|Person=1|PronType=Prs	10	obj	_	_
10	pillen	pillar	VERB	Vps30p	Mood=Sub|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	4	advcl	_	_
11	adormecidos	adormecido	ADJ	A0mp	Gender=Masc|Number=Plur	10	xcomp	_	SpaceAfter=No
12	.	.	PUNCT	Q.	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 7 xcomp	color:blue
1	Dende	dende	ADP	P	AdpType=Prep	2	case	_	_
2	entón	entón	ADV	Wn	_	3	advmod	_	_
3	considero	considerar	VERB	Vpi10s	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
4	o	o	PRON	Raa3ms	Case=Acc|Clitic=Yes|Gender=Masc|Number=Sing|Person=3|PronType=Prs	3	obj	_	_
5	o	o	DET	Ddms	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	7	det	_	_
6	mellor	mellor	ADJ	Acms	Degree=Cmp|Gender=Masc|Number=Sing	7	amod	_	_
7	profesor	profesor	NOUN	Scms	Gender=Masc|Number=Sing	3	xcomp	_	_
8	que	que	PRON	Tnms	Gender=Masc|Number=Sing|PronType=Rel	9	nsubj	_	_
9	tiven	ter	VERB	Vei10s	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	7	acl	_	SpaceAfter=No
10	.	.	PUNCT	Q.	_	3	punct	_	_

~~~


