---
layout: page
title: functor
permalink: /context/functor
---
A **functor** $F \colon \mathsf{C} \to \mathsf{D}$, between categories $\mathsf{C}$ and $\mathsf{D}$, consists of the following data:\n1. An object $Fc \in \mathsf{D}$, for each object $c \in \mathsf{C}$.\n2. A morphism $Ff \colon Fc \to Fc' \in \mathsf{D}$, for each morphism $f \colon c \to c' \in \mathsf{C}$, so that the domain and codomain of $Ff$ are, respectively, equal to $F$ applied to the domain or codomain of $f$.\nThe assignments are required to satisfy the following two **functoriality axioms**:\n1. For any composable pair $f,g$ in $\mathsf{C}$, $Fg \cdot Ff = F(g \cdot f)$.\n2. For each object $c$ in $\mathsf{C}$, $F(1_c) = 1_{Fc}$.
