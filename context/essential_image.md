---
layout: page
title: essential image
permalink: /context/essential_image
---
The following constructions and definitions are equivalence invariant:
1. If a category is locally small, any category equivalent to it is again locally small.
2. If a category is a groupoid, any category equivalent to it is again a groupoid.
3. If $\mathsf{C} \simeq \mathsf{D}$, then $\mathsf{C}^\mathrm{op} \simeq \mathsf{D}^\mathrm{op}$.
4. The product of a pair of categories is equivalent to the product of any pair of equivalent categories.
5. An arrow in $\mathsf{C}$ is an isomorphism if and only if its image under an equivalence $\mathsf{C} \xrightarrow{\smash{\mathlower{0.6}{\simeq}}} \mathsf{D}$ is an isomorphism.
The last of these properties can be generalized. By Theorem \ref{thm:equivalence}, a full and faithful functor $F \colon \mathsf{C} \to \mathsf{D}$ defines an equivalence onto its **essential image**, the full subcategory of objects isomorphic to $Fc$ for some $c \in \mathsf{C}$. Fully faithful functors have a useful property stated as Exercise \ref{exc:ff-reflect-iso}: if $F$ is full and faithful and $Fc$ and $Fc'$ are isomorphic in $\mathsf{D}$, then $c$ and $c'$ are isomorphic in $\mathsf{C}$. We will introduce what are easily the most important fully faithful functors in category theory in Chapter \ref{ch:yoneda}: the covariant and contravariant Yoneda embeddings.
