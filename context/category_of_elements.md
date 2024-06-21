---
layout: page
title: category of elements
permalink: /context/category_of_elements
---
The  **category of elements** $\el{F}$ of a contravariant functor $F \colon \cC^\op \to \cat{Set}$  has\n1. as objects, pairs $(c,x)$ where $c \in \cC$ and $x \in Fc$, and\n2. a morphism $(c,x) \to (c',x')$ is a morphism $f \colon c \to c'$ in $\cC$ so that $Ff(x') = x$.\nThe category of elements has an evident forgetful functor $\Pi \colon \el{F} \to \cC$.\n$$ \xymatrix{ \mathrm{If}\ Ff(x')=x,\ \mathrm{then} &  (c,x) \ar[r]^f \ar@{}[dr]|{\rotatebox{-90}{$\mapsto$}}^(.6){\Pi} & (c',x') &  \in & \el{F} \ar[d]^\Pi \\ & c \ar[r]_f & c' & \in  & \cC}$$
