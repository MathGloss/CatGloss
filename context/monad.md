---
layout: page
title: monad
permalink: /context/monad
---
A **monad** on a category $\cC$ consists of\n1. an endofunctor $T \colon \cC \to \cC$,\n2. a **unit** natural transformation $\eta \colon 1_\cC \To T$, and\n3. a **multiplication** natural transformation $\mu \colon T^2 \To T$,\nso that the following diagrams commute in $\cC^\cC$:\n$$ \xymatrix{ T^3 \ar@{=>}[r]^{T\mu} \ar@{=>}[d]_{\mu T} & T^2 \ar@{=>}[d]^{\mu} & & T \ar@{=>}[r]^{\eta T} \ar@{=>}[dr]_{1_T} & T^2 \ar@{=>}[d]^\mu & T \ar@{=>}[l]_{T\eta} \ar@{=>}[dl]^{1_T} \\ T^2 \ar@{=>}[r]_{\mu} & T & & & T}$$
