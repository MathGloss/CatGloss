---
layout: page
title: linear dual
permalink: /context/linear_dual
---
Any finite-dimensional $\kk$-vector space $V$ is isomorphic to its **linear dual**, the vector space $V^* = \Hom(V,\kk)$ of linear maps $V \to \kk$, because these vector spaces have the same dimension. This can be proven through the construction of an explicit **dual basis**: choose a basis $e_1,\ldots, e_n$ for $V$ and then define $e_1^*,\ldots, e_n^* \in V^*$ by $$ e_i^*(e_j) = \begin{cases}  1 & i = j \\ 0 & i \neq j. \end{cases}$$ The collection $e_1^*,\ldots, e_n^*$ defines a basis for $V^*$ and the map $e_i \mapsto e_i^*$ extends by linearity to define an isomorphism $V \cong V^*$.
