---
layout: page
title: comma category
permalink: /context/comma_category
---
Given functors $F \colon \cD \to \cC$ and $G \colon \cE \to \cC$, show that there is a category, called the **comma category** $F \comma G$, which has\n1. as objects, triples $(d \in \cD, e \in \cE, f \colon Fd \to Ge \in \cC)$, and\n2. as morphisms $(d,e,f) \to (d',e',f')$, a pair of morphisms $(h \colon d \to d', k \colon e \to e')$ so that the square\n$$  \xymatrix{ Fd \ar[d]_{Fh} \ar[r]^f & Ge \ar[d]^{Gk} \\ Fd' \ar[r]_{f'} & Ge'}$$ commutes in $\cC$, i.e., so that $f' \cdot Fh = Gk \cdot f$.\nDefine a pair of projection functors $\dom \colon F \comma G \to \cD$ and $\cod \colon F \comma G \to \cE$.
