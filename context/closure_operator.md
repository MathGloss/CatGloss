---
layout: page
title: closure operator
permalink: /context/closure_operator
---
A monad on a preorder $(\cP, \leq)$ is given by an order-preserving function $T \colon \cP \to \cP$ that is so that $p \leq Tp$ and  $T^2p \leq Tp$. If $\cP$ is a poset, so that isomorphic objects are equal, these two conditions imply that $T^2 p = Tp$. An order-preserving function $T$ so that $p \leq Tp$ and $T^2 p = Tp$ is called a **closure operator**.  Dually, a comonad on a poset category $(\cP, \leq)$ defines a **kernel operator**: an order-preserving function $K$ so that $Kp \leq p$ and $K p = K^2 p$.
