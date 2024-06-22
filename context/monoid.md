---
layout: page
title: monoid
permalink: /context/monoid
---
A **monoid** is an object $M \in \textup{\textsf{cat}}$ together with a pair of morphisms $\mu \colon M \times M \to M$ and $\eta \colon 1 \to M$ so that the following diagrams commute:\n$$ \xymatrix{ M \times M \times M \ar[d]_{\mu \times 1_M} \ar[r]^-{1_M \times \mu} & M \times M \ar[d]^\mu & M \ar[r]^-{\eta \times 1_M} \ar[dr]_{1_M} & M \times M \ar[d]^\mu & M \ar[l]_-{1_M \times \eta} \ar[dl]^{1_M} \\ M \times M \ar[r]_-\mu & M &&  M}$$
