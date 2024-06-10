---
layout: page
title: Research
permalink: /research/
---

## Grammar engineering:

Since 2010, I have been involved in the development of a metagrammar compiler called XMG-2.

Designing and maintaining large scaled grammars for natural language is a complex task which needs a huge amount of work and time.[XMG](http://sourcesup.cru.fr/xmg/) provides a way for the linguists to generate those grammars from an abstract description, using elementary fragments and combining them.  
It includes a dimension system which allows to make different contributions to different levels of linguistic description. For example, syntactic descriptions are accumulated in the syntactic dimension and semantics in the semantic one. XMG-2 project began for two principle reasons.  
The first is technological : XMG is implemented in Oz/Mozart, which is not longer maintained, and not compatible with 64 bits systems.  
The second motivation is to achieve the initial goals of the compiler. These goals are to handle multi-formalism and multi-dimensionality.

XMG-2 and its documentation are [available on GitHub](https://github.com/spetitjean/XMG-2).

## Parsing:

The TreeGraSP project, but also the SFB 991, have produced linguistic resources which use two syntactic formalisms, Tree Adjoining Grammar (TAG) and Role and Reference Grammar (RRG). Some of these resources are precision grammars developed with XMG-2. In order to be able to use or evaluate these resources, the development of a parser adapted for them was necessary.

The tool we develop is based on [TuLiPA](https://sourcesup.cru.fr/tulipa/), a parser for Tree Adjoining Grammars and predicate semantics. The new version, [TuLiPA-frames](https://github.com/spetitjean/TuLiPA-frames), is under active development, and provides extensions for frame semantics and RRG.

## Treebanking:

I was involved in the development of various annotation platforms for Role and Reference Grammar. These include [RRGbank](http://rrgbank.phil.hhu.de), [RRGparbank](http://rrgparbank.phil.hhu.de), [Daabank](http://daabank.phil.hhu.de) and the online parser [RRGparser](http://rrgparser.phil.hhu.de).
