---
layout: page
title: classifying function
permalink: /context/classifying_function
---
The following contravariant functors are representable.\n1. The contravariant power set functor $P \colon \cat{Set}^\op \to \cat{Set}$ is represented by the set $\Omega = \{\top,\bot\}$ with two elements. The natural isomorphism $\cat{Set}(A,\Omega) \cong PA$ is defined by the bijection that associates a function $A \to \Omega$ with the subset that is the preimage of $\top$; reversing perspectives, a subset $A' \subset A$ is identified with its **classifying function** $\chi_{A'} \colon A \to \Omega$, which sends exactly the elements of $A'$ to the element $\top$. The naturality condition stipulates that for any function $f \colon A \to B$, the diagram\n$$ \xymatrix{ \cat{Set}(B,\Omega) \ar[r]^-{\cong} \ar[d]_{f^{*}} & PB \ar[d]^{f^{-1}} \\ \cat{Set}(A,\Omega) \ar[r]_-\cong & PA}$$ commutes. That is, naturality asserts that given a function $\chi_{B'} \colon B \to \Omega$ classifying the subset $B' \subset B$, the composite function $A \xrightarrow{f} B \xrightarrow{\chi_{B'}} \Omega$ classifies the subset $f^{-1}(B')\subset A$.\n2. The functor $\mathcal{O} \colon \cat{Top}^\op \to \cat{Set}$ that sends a space to its set of open subsets is represented by the **Sierpinski space** $S$, the topological space with two points, one closed and one open. The natural bijection $\cat{Top}(X,S) \cong \mathcal{O}(X)$ associates a continuous function $X \to S$ to the preimage of the open point. This bijection is natural because a composite function $Y \to X \to S$ classifies the preimage of the open subset of $X$ under the function $Y \to X$.\n3. The Sierpinski space also represents the functor $\mathcal{C} \colon \cat{Top}^\op \to \cat{Set}$ that sends a space to its set of closed subsets. Composing the natural isomorphisms $\mathcal{O} \cong \cat{Top}(-,S) \cong \mathcal{C}$ we see that the closed set and open set functors are naturally isomorphic. The composite natural isomorphism carries an open subset to its complement, which is closed. This recovers the natural isomorphism described in Example \ref{exs:natural}\eqref{itm:open-closed-nat}.\n4. The functor $\Hom(- \times A, B) \colon \cat{Set}^\op \to \cat{Set}$ that sends a set $X$ to the set of functions $X \times A \to B$ is represented by the set $B^A$ of functions from $A$ to $B$. That is, there is a natural bijection between functions $X \times A \to B$ and functions $X \to B^A$. This natural isomorphism is referred to as **currying** in computer science; by fixing a variable in a two-variable function, one obtains a family of functions in a single variable.\n5. The functor $U(-)^* \colon \cat{Vect}_\kk^\op \to \cat{Set}$ that sends a vector space to the set of vectors in its dual space is represented by the vector space $\kk$, i.e., linear maps $V \to \kk$ are, by definition, precisely the vectors in the dual space $V^*$.\n6. For any fixed abelian group $A$ and any $n \geq 0$, \emph{singular cohomology with coefficients in $A$} defines a functor $H^n(-;A) \colon \cat{Top}^\op \to \cat{Ab}$. As in Example \ref{exs:functor}\eqref{itm:underlying-element}, this functor is a homotopy invariant, factoring through the quotient $\cat{Top} \to \cat{Htpy}$ to define a functor $H^n(-;A) \colon \cat{Htpy}^\op \to \cat{Ab}$. Passing to underlying sets and restricting to a subcategory of ``nice'' spaces, such as the \emph{CW complexes}, the resulting functor $, of CW complexes and homotopy classes of continuous maps}$H^n(-;A) \colon \cat{Htpy}_{\mathrm{CW}}^\op \to \cat{Set}$ is represented by the **Eilenberg--MacLane space** $K(A,n)$. That is, for any CW complex $X$, homotopy classes of maps $X \to K(A,n)$ stand in bijection with elements of the $n$th singular cohomology group  $H^n(X;A)$ of $X$ with coefficients in $A$.\n7. A **classifying space** for a topological group $G$ is a CW complex $BG$ that represents the functor $\cat{Htpy}^\op_{\mathrm{CW}} \to \cat{Set}$ that takes a CW complex to the set of isomorphism classes of \emph{principal $G$-bundles} over it.