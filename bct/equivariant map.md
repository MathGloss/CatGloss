---
layout: page
title:  equivariant map
permalink: /context/equivariant_map
---
Take two $G$-sets, $S$ and $T$.  Since $S$ and $T$ can be regarded as functors $G \to \mathbf{Set}$, we can ask: what is a natural transformation $ \xymatrix{ G \rtwocell^S_T{\alpha} &\mathbf{Set}, } $ in concrete terms?  Such a natural transformation consists of a single map in $\mathbf{Set}$ (since $G$ has just one object), satisfying some axioms.  Precisely, it is a function $\alpha{\colon}\linebreak[0] S \to T$ such that $\alpha(g\cdot s) = g\cdot \alpha(s)$ for all $s \in S$ and $g \in G$.  (Why?)  In other words, it is just a map of $G$-sets, sometimes called a **$G$-equivariant**    map. 