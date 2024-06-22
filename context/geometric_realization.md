---
layout: page
title: geometric realization
permalink: /context/geometric_realization
---
Apply the construction of Remark \ref{rmk:lan-adjunction} to the functor $\Delta \colon {\mathbbe{\Delta}} \to \textup{\textsf{cat}}$ that sends the ordinal $[n]= 0 \to 1 \to \cdots \to n$ to the topological $n$-simplex\n$$ \Delta^n \coloneqq \left\{ (x_0,\ldots, x_n) \in \mathbb{R}^{n+1} \Biggm| \sum_i x_i = 1, x_i \geq 0\right\}.$$\nThe left adjoint, defined by left Kan extension, forms the **geometric realization** of a simplicial set. The right adjoint is the **total singular complex functor**, which is used to define singular homology:\n$$ \xymatrix{ \cat{Top} \ar@<-1ex>[r]_-{\textup{fun}} \ar@{}[r]|-\perp & \textup{\textsf{cat}}^{{\mathbbe{\Delta}}^\mathrm{op}}.\ar@<-1ex>[l]_-{|-|}}$$
