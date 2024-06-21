---
layout: page
title: product
permalink: /context/product
---
A **product** is a limit of a diagram indexed by a discrete category, with only identity morphisms. A diagram in $\cC$ indexed by a discrete category  $J$ is simply a collection of objects $F_j \in \cC$ indexed by $j \in J$. A cone over this diagram is a $J$-indexed family of morphisms $(\lambda_j \colon c \to F_j)_{j \in J}$, subject to no further constraints. The limit is typically denoted by $\prod_{j \in J} F_j $ and the legs of the limit cone are maps $$\left(\pi_k \colon \prod_{j \in J} F_j \to F_k\right)_{k \in J}$$ called **(product) projections**. The universal property asserts that composition with the product projections defines a natural isomorphism\n$$ \xymatrix{ \cC(c,\prod_{j \in J} F_j ) \ar[r]^-{(\pi_k)_*}_-{\cong} & \prod_{k \in J} \cC(c,F_k) \cong \fun{Cone}(c,F).}$$
