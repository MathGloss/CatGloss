---
layout: page
title: generalized element
permalink: /context/generalized_element
---
Elements of a set $A$ stand in bijection with morphisms $a \colon 1 \to A$ in the category of sets. By composition, morphisms $f \colon A \to B$ in the category of sets act on elements: the composite $fa$ encodes the element $f(a)$. In any category $\cC$, a **generalized element** of an object $A$ is a morphism $a \colon X \to A$ with codomain $A$. Morphisms $f \colon A \to B$ in $\cC$ act on $X$-shaped elements by composition: the composite $fa$ encodes an $X$-shaped generalized element of $B$. In this terminology, the contravariant represented functor $$\Hom(-,A) \colon \cC^\op \to \cat{Set}$$ sends an object $X$ to the set of $X$-shaped generalized elements of $A$. Since the Yoneda embedding $\cC \hookrightarrow \cat{Set}^{\cC^\op}$ is fully faithful, no information about $A$ is lost by considering instead the functor $\Hom(-,A)$ of generalized elements of $A$.
