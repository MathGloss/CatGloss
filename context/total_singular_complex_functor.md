---
layout: page
title: total singular complex functor
permalink: /context/total_singular_complex_functor
---
Apply the construction of Remark \ref{rmk:lan-adjunction} to the functor $\Delta \colon \DDelta \to \cat{Top}$ that sends the ordinal $[n]= 0 \to 1 \to \cdots \to n$ to the topological $n$-simplex\n$$ \Delta^n \coloneqq \left\{ (x_0,\ldots, x_n) \in \RR^{n+1} \Biggm| \sum_i x_i = 1, x_i \geq 0\right\}\rlap{{\,}.}$$\nThe left adjoint, defined by left Kan extension, forms the **geometric realization** of a simplicial set. The right adjoint is the **total singular complex functor**, which is used to define singular homology:\n$$ \xymatrix{ \cat{Top} \ar@<-1ex>[r]_-{\fun{Sing}} \ar@{}[r]|-\perp & \cat{Set}^{\DDelta^\op}\rlap{{\,}.}\ar@<-1ex>[l]_-{|-|}}$$
