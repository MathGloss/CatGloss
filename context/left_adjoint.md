---
layout: page
title: left adjoint
permalink: /context/left_adjoint
---
An **adjunction** consists of a pair of functors $F \colon \cC \to \cD$ and $G \colon \cD \to \cC$ together with an isomorphism $$\cD(Fc,d) \cong \cC(c,Gd)$$ for each $c \in \cC$ and $d \in \cD$ that is natural in both variables. Here $F$ is **left adjoint** to $G$ and $G$ is **right adjoint** to $F$. The morphisms $$ \xymatrix{ Fc \ar[r]^{f^\sharp} & d} \qquad \leftrightsquigarrow\qquad \xymatrix{ c \ar[r]^{f^\flat} & Gd}$$ corresponding under the bijection \eqref{eq:hom-set-adj} are **adjunct** or are **transposes** of each other.
