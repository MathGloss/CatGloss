---
layout: page
title: functor
permalink: /context/functor
---
A **functor** $F \colon \cC \to \cD$, between categories $\cC$ and $\cD$, consists of the following data:\n1. An object $Fc \in \cD$, for each object $c \in \cC$.\n2. A morphism $Ff \colon Fc \to Fc' \in \cD$, for each morphism $f \colon c \to c' \in \cC$, so that the domain and codomain of $Ff$ are, respectively, equal to $F$ applied to the domain or codomain of $f$.\nThe assignments are required to satisfy the following two **functoriality axioms**:\n1. For any composable pair $f,g$ in $\cC$, $Fg \cdot Ff = F(g \cdot f)$.\n2. For each object $c$ in $\cC$, $F(1_c) = 1_{Fc}$.
