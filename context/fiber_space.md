---
layout: page
title: fiber space
permalink: /context/fiber_space
---
Following \cite{grothendieck-kansas}, define a **fiber space** $p \colon E \to B$ to be a morphism in $\textup{\textsf{cat}}$.  A map of fiber spaces is a commutative square. Thus, the category of fiber spaces is isomorphic to the diagram category $\textup{\textsf{cat}}^\mathbbe{2}$. We are also interested in the non-full subcategory $\textup{\textsf{cat}}/B \subset \textup{\textsf{cat}}^\mathbbe{2}$ of fiber spaces over $B$ and maps whose codomain component is the identity. Prove the following:
1. A map $$\xymatrix{ E' \ar[d]_{p'} \ar[r]^g & E \ar[d]^{p} \\ B' \ar[r]_f & B}$$of fiber spaces induces a canonical map from the fiber over a point $b \in B'$ to the fiber over its image $f(b) \in B$.
2. The fiber of a product of fiber spaces is the product of the fibers.
A projection $B \times F \to B$ defines a **trivial fiber space** over $B$, a definition that makes sense for any space $F$.
1. Show that the fiber of a trivial fiber space $B \times F \to B$ is  isomorphic to $F$.
2. Characterize the isomorphisms in $\textup{\textsf{cat}}/B$ between two trivial fiber spaces (with a priori distinct fibers) over $B$.
3. Prove that the assignment of the set of continuous sections of a fiber space over $B$ defines a functor $\textup{fun} \colon \textup{\textsf{cat}}/B \to \textup{\textsf{cat}}$.
4. Consider the non-full subcategory $\textup{\textsf{cat}}^\2_{\text{pb}}$ of fiber spaces in which the morphisms are the pullback squares.  Prove that the assignment of the set of continuous sections to a fiber space defines a functor $\textup{fun}\colon (\textup{\textsf{cat}}^\2_{\text{pb}})^\mathrm{op} \to \textup{\textsf{cat}}$.
5. Describe the compatibility between the actions of the ``sections'' functors just introduced with respect to the map $g$ of fiber spaces $p$ and $q$ over $B$ and their restrictions along $f \colon B' \to B$.
$$ \xymatrix@=10pt{ E' \ar@{}[dr]\mid(.2){\displaystyle\lrcorner} \ar[rr] \ar[ddd]_{p'} & & E  \ar'[d][ddd]_p \ar[dr]^g \\ & F' \ar@{}[dr]\mid(.2){\displaystyle\lrcorner} \ar[ddl]^{q'} \ar[rr] & & F \ar[ddl]^q \\ & & \\  B' \ar[rr]_f & & B}$$
