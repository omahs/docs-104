---
layout: base
title:  'Statistics of mark:prt in UD_Scottish_Gaelic-ARCOSG'
udver: '2'
---

## Treebank Statistics: UD_Scottish_Gaelic-ARCOSG: Relations: `mark:prt`

This relation is a language-specific subtype of <tt><a href="gd_arcosg-dep-mark.html">mark</a></tt>.

3016 nodes (7%) are attached to their parents as `mark:prt`.

3016 instances of `mark:prt` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.10344827586207.

The following 11 pairs of parts of speech are connected with `mark:prt`: <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (2139; 71% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (591; 20% instances), <tt><a href="gd_arcosg-pos-ADV.html">ADV</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (172; 6% instances), <tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (80; 3% instances), <tt><a href="gd_arcosg-pos-NUM.html">NUM</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (9; 0% instances), <tt><a href="gd_arcosg-pos-PRON.html">PRON</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (7; 0% instances), <tt><a href="gd_arcosg-pos-PROPN.html">PROPN</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (7; 0% instances), <tt><a href="gd_arcosg-pos-X.html">X</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (6; 0% instances), <tt><a href="gd_arcosg-pos-ADP.html">ADP</a></tt>-<tt><a href="gd_arcosg-pos-PART.html">PART</a></tt> (3; 0% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-SCONJ.html">SCONJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 mark:prt	color:blue
1	turkey	turkey	X	Xfe	Foreign=Yes	0	root	_	_
2	burger	burger	X	Xfe	Foreign=Yes	1	flat	_	_
3	an	an	PART	Qq	Mood=Int|PartType=Vb|PronType=Int	4	mark:prt	_	_
4	robh	bi	VERB	V-s--d	Tense=Past	1	ccomp	_	_
5	e	e	PRON	Pp3sm	Gender=Masc|Number=Sing|Person=3	4	nsubj	_	_
6	math	math	ADJ	Ap	_	4	xcomp:pred	_	SpaceAfter=No
7	?	?	PUNCT	Fg	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 12 mark:prt	color:blue
1	‘s	‘s	CCONJ	Cc	_	3	cc	_	_
2	an	an	PART	Qq	Mood=Int|PartType=Vb|PronType=Int	3	mark:prt	_	_
3	robh	bi	VERB	V-s--d	Tense=Past	0	root	_	_
4	a	a	DET	Dq	_	6	det	_	_
5	h-uile	uile	DET	Dq	_	4	fixed	_	_
6	duine	duine	NOUN	Ncsmn	Case=Nom|Gender=Masc|Number=Sing	3	nsubj	_	_
7	eile	eile	ADJ	Aq-smn	Case=Nom|Gender=Masc|Number=Sing	6	amod	_	_
8	air	air	PART	Sa	_	13	case	_	_
9	na	an	DET	Tdpf	Gender=Fem|Number=Plur	10	det	_	_
10	trì	trì	NUM	Mc	_	11	nummod	_	_
11	duilleagan	duilleag	NOUN	Ncpfn	Case=Nom|Gender=Fem|Number=Plur	13	obj	_	_
12	a	a	PART	Ug	PartType=Inf	13	mark:prt	_	_
13	dhèanamh	dèan	NOUN	Nv	VerbForm=Inf	3	xcomp:pred	_	SpaceAfter=No
14	?	?	PUNCT	Fg	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 mark:prt	color:blue
1	thuirt	abair	VERB	V-s	Tense=Past	0	root	_	_
2	[Name]	[Name]	PROPN	Nn-mn	Case=Nom|Gender=Masc	1	nsubj	_	_
3	gun	gun	PART	Qa	_	4	mark:prt	_	_
4	robh	bi	VERB	V-s--d	Tense=Past	1	ccomp	_	_
5	e	e	PRON	Pp3sm	Gender=Masc|Number=Sing|Person=3	4	nsubj	_	_
6	ag	ag	PART	Sa	_	7	case	_	_
7	obair	obraich	NOUN	Nv	VerbForm=Vnoun	4	xcomp:pred	_	_
8	gu	gu	PART	Ua	PartType=Ad	9	mark:prt	_	_
9	anmoch	anmoch	ADV	Rt	_	7	advmod	_	_
10	so	so	SCONJ	Xfe	Foreign=Yes	11	mark	_	_
11	[?]	[?]	X	Xx	_	1	discourse	_	_

~~~

