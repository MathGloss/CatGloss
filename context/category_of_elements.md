---
layout: page
title: category of elements
permalink: /context/category_of_elements
---
The  **category of elements** $\textstyle{\int}\!{el}$ of a contravariant functor $F \colon \mathsf{C}^\mathrm{op} \to \textup{\textsf{cat}}$  has\n1. as objects, pairs $(c,x)$ where $c \in \mathsf{C}$ and $x \in Fc$, and\n2. a morphism $(c,x) \to (c',x')$ is a morphism $f \colon c \to c'$ in $\mathsf{C}$ so that $Ff(x') = x$.\nThe category of elements has an evident forgetful functor $\Pi \colon \textstyle{\int}\!{el} \to \mathsf{C}$.\n$$ \xymatrix{ \mathrm{If}\ Ff(x')=x,\ \mathrm{then} &  (c,x) \ar[r]^f \ar@{}[dr]|{\rotatebox{-90}{$\mapsto$}}^(.6){\Pi} & (c',x') &  \in & \textstyle{\int}\!{el} \ar[d]^\Pi \\ & c \ar[r]_f & c' & \in  & \mathsf{C}}$$
