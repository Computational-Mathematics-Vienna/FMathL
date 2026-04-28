# FMathL - Formal Mathematical Language

FMathL (= Formal Mathematical Language) is the working title for a modeling and documentation language for mathematics, suited to the habits of mathematicians, to be developed in a project at the University of Vienna.

The project complements efforts for formalizing mathematics from the perspective of computer science and automated theorem proving. In the long run, the FMathL system might turn into a user-friendly automatic mathematical assistant for retrieving, editing, and checking mathematics (but also computer science and theoretical physics) in both informal, partially formalized, and completely formalized mathematical form.

The project is part of a greater [vision](http://arnold-neumaier.at/FMathL/vision.html), the creation of an expert system called [MathResS](http://arnold-neumaier.at/FMathL/mathress.html) ( = Mathematical Research System) that supports mathematicians and scientists dealing with mathematics in a comprehensive way. Part of the project is done in collaboration with the software company [DAGOPT](http://www.dagopt.com/en/home).

Related projects by others are [MathNat - Mathematical texts in controlled natural language](https://tel.archives-ouvertes.fr/tel-00680095) (by Muhammad Humayoun), [Naproche - Natural language proof checking](http://www.naproche.net/) (by Marcos Cramer et al., until 2013), [A Language for Mathematics](http://philmat.oxfordjournals.org/content/early/2016/09/13/philmat.nkw020.short?rss=1) (by Mohan Ganesalingam), [A Fully Automatic Theorem Prover with Human-Style Output](https://pubmed.ncbi.nlm.nih.gov/30174363/) (by Ganesalingam and Gowers), [A language for mathematical knowledge management](http://www.andrew.cmu.edu/user/avigad/Papers/mkm/) (by Kieffer, Avigad and Friedman), [Mathcat](http://www-al.nii.ac.jp/mathcat-project/) (by Akiko Aizawa), and [FPL - the Formal Proving Language](https://www.bookofproofs.org/branches/fpl-formal-proving-language/) (by Andreas Piotrowski).

# The FMathL project

FMathL (= Formal Mathematical Language) is the working title for a modeling and documentation language for mathematics, to be developed at the University of Vienna.

If you'd like to be actively involved in the FMathL project, please contact [Arnold Neumaier](mailto:Arnold.Neumaier@univie.ac.at).

Part of the goals associated with the FMathL language were realized through the project A modeling system for mathematics (MoSMath), supported from 2008-2011 by a grant of the Austrian Science Foundation FWF under contract number [P20631](https://www.fwf.ac.at/forschungsradar/10.55776/P20631).

Another FMathL-related project An automatic mathematical research system (MathResS) never got off the ground, due to lack of funding. All referees in all versions submitted found the project to be far too ambitious to be realizable.

Thus much of what is said here is about plans, some of which is already realized, and some of which will perhaps be realized in the near future.

Most of the content of this web site dates back to 2011. Important additional work was done in 2016-2017.

The design of FMathL is based on our experience with
- pure and applied mathematics in general,
- modeling languages,
- numerical programming systems,
- test problem collections for various problem types,
- real applications, and
- wrong starts in the past.

The goal of the FMathL project is to combine
- the universality of the common mathematical language to describe completely arbitrary problems,
- the advantages of [LaTeX](http://www.latex-project.org) for writing and viewing mathematics,
- the user-friendliness of mathematical modeling systems such as [AMPL](http://www.ampl.com) for the flexible definition of large-scale numerical analysis problems,
- the high-level discipline of the [CVX](https://cvxr.com/cvx/) system for solving convex programming problems and enforcing their semantic correctness, and
- the semantic clarity of the [Z notation](http://www.zuser.org) for the precise specification of concepts and statements.

We believe that this goal is reachable, and that an easy-to-use such system will change the way modeling is done in practice. See [A modeling system for mathematics](FMathL/project.pdf) for some background information.

# FMathL project update 2016-2017
A. Neumaier, The communication of mathematics, Lecture, Isaac Newton Institute for Mathematical Sciences, Cambridge 2017.
[video of the lecture](https://www.newton.ac.uk/seminar/21863/)

A. Neumaier, Concise - a synthesis of types, grammars, semantics Lecture, Isaac Newton Institute for Mathematical Sciences, Cambridge 2017.
[video of the lecture](https://www.newton.ac.uk/seminar/21967/)

A. Neumaier, [From Informal to Formal Mathematics](FMathL/inFormal.pdf), Slides of a lecture presented at VINO 2017 (Technical University Vienna, Austria)

These lectures summarize parts of the master thesis by Andreas Pichler and the Ph.D. thesis by Kevin Kofler; see the references below.

Loosely related to FMathL is my lecture

A. Neumaier, [Artificial Intelligence, Mathematics, and Consciousness](FMathL/AI2016slides.pdf), Slides, 2016.

##Important references

P. Schodl, [Foundations for a self-reflective, context-aware semantic representation of mathematical specifications](http://othes.univie.ac.at/16941/1/2011-07-06_9947489.pdf), Ph.D. thesis, Faculty of Mathematics, University of Vienna (2011).

F. Domes, A. Neumaier, K. Kofler, P. Schodl, H. Schichl, [Concise Manual, Version 0.91](http://arnold-neumaier.at/ms/ConciseManual.pdf), Faculty of Mathematics, University of Vienna (2014).

A. Pichler, [Semantische Repräsentation mathematischer Konzepte](http://arnold-neumaier.at/ms/pichlerMaster.pdf), Masterarbeit, Faculty of Mathematics, University of Vienna (2016).

K. Kofler, [Dynamic Generalized Parsing and Natural Mathematical Language](https://www.tigen.org/kevin.kofler/fmathl/dyngenpar/diss.pdf), Ph.D. thesis, Faculty of Mathematics, University of Vienna (2017).

[DynGenPar - Dynamic Generalized Parser](https://www.tigen.org/kevin.kofler/fmathl/dyngenpar/ for generalized context free grammars (by Kevin Kofler)
supports dynamic grammar additions, incremental parsing, prediction, rule labels, custom parse actions, arbitrary token sources, hierarchical parsing, parallel multiple context-free grammars (PMCFGs), and next token constraints.

# Software created by 2012

[Concise}(http://www.mat.univie.ac.at/~dferi/concise.html), a graph-based universal programming system for manipulating semantic information stored in the semantic memory. It combines in a novel way the capabilities of imperative programming and object-oriented programming. (Online is only an old version with much less capability than described in the thesis by Kevin Kofler.)

[DynGenPar](http://www.tigen.org/kevin.kofler/fmathl/dyngenpar/), an innovative parser based on a new principle combining bottom-up and top-down features of traditional parsers. The most unique feature of the algorithm is the possibility to add rules to the grammar at almost any time, even during parsing.

[Papers and technical reports until 2012](http://arnold-neumaier.at/FMathL/papers/list.html) 
