---
layout: page
title: universal coefficient theorem
permalink: /context/universal_coefficient_theorem
---
In 1941 Saunders Mac Lane gave a lecture at the University of Michigan in which he computed for a prime $p$ that $\mathrm{Ext}(\ZZ[\frac{1}{p}]/\ZZ,\ZZ)\cong\ZZ_p$, the group of $p$-adic integers, where $\ZZ[\frac{1}{p}]/\ZZ$ is the Pr\{u}fer $p$-group. When he explained this result to Samuel Eilenberg, who had missed the lecture, Eilenberg recognized the calculation as the homology of the 3-sphere complement of the $p$-adic solenoid, a space formed as the infinite intersection of a sequence of solid tori, each wound around $p$ times inside the preceding torus.  In teasing apart this connection, the pair of them discovered what is now known as the **universal coefficient theorem** in algebraic topology, which relates the \emph{homology} $H_*$ and \emph{cohomology groups} $H^*$ associated to a space $X$ via a group extension \cite{maclane-autobiography}:\n$$ 0 \to \mathrm{Ext}(H_{n-1}(X),G) \to H^n(X,G) \to \Hom(H_n(X),G) \to 0\rlap{{\,}.}$$
