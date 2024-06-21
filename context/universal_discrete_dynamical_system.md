---
layout: page
title: universal discrete dynamical system
permalink: /context/universal_discrete_dynamical_system
---
A set $X$ with an endomorphism $f \colon X \to X$ and a distinguished element $x_0$ is called a **discrete dynamical system**. This data allows one to consider the discrete-time evolution of the initial element $x_0$, a sequence defined by $x_{n+1} \coloneqq f(x_n)$. The principle of mathematical recursion asserts that the natural numbers $\NN$, the successor function $s \colon \NN \to \NN$, and the element $0 \in \NN$ define the **universal discrete dynamical system**: which is to say, there is a unique function $r \colon \NN \to X$ so that $r(n) = x_n$ for each $n$, i.e., so that $r(0)=x_0$ and so that the diagram\n$$\vcenter{\xymatrix{ \NN \ar[r]^s \ar[d]_r & \NN \ar[d]^r \\ X \ar[r]_f & X}}$$ commutes.
