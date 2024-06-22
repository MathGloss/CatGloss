---
layout: page
title: contravariant functor
permalink: /context/contravariant_functor
---
A **contravariant functor** $F$ from $\mathsf{C}$ to $\mathsf{D}$ is a functor $F \colon \mathsf{C}^\mathrm{op} \to \mathsf{D}$.
 Explicitly, this consists of the following data:
1. An object $Fc \in \mathsf{D}$, for each object $c \in \mathsf{C}$.
2. A morphism $Ff \colon Fc' \to Fc \in \mathsf{D}$, for each morphism $f \colon c \to c' \in \mathsf{C}$, so that the domain and codomain of $Ff$ are, respectively, equal to $F$ applied to the codomain or domain of $f$.
The assignments are required to satisfy the following two **functoriality axioms**:
1. For any composable pair $f,g$ in $\mathsf{C}$, $Ff \cdot Fg = F(g \cdot f)$.
2. For each object $c$ in $\mathsf{C}$, $F(1_c) = 1_{Fc}$.
