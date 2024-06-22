---
layout: page
title: monad
permalink: /context/monad
---
A **monad** on a category $\mathsf{C}$ consists of\n1. an endofunctor $T \colon \mathsf{C} \to \mathsf{C}$,\n2. a **unit** natural transformation $\eta \colon 1_\mathsf{C} \Rightarrow T$, and\n3. a **multiplication** natural transformation $\mu \colon T^2 \Rightarrow T$,\nso that the following diagrams commute in $\mathsf{C}^\mathsf{C}$:\n$$ \xymatrix{ T^3 \ar@{=>}[r]^{T\mu} \ar@{=>}[d]_{\mu T} & T^2 \ar@{=>}[d]^{\mu} & & T \ar@{=>}[r]^{\eta T} \ar@{=>}[dr]_{1_T} & T^2 \ar@{=>}[d]^\mu & T \ar@{=>}[l]_{T\eta} \ar@{=>}[dl]^{1_T} \\ T^2 \ar@{=>}[r]_{\mu} & T & & & T}$$
