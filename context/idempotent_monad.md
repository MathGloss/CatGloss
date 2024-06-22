---
layout: page
title: idempotent monad
permalink: /context/idempotent_monad
---
The adjunction associated to a reflective subcategory of $\mathsf{C}$ induces an **idempotent monad** on $\mathsf{C}$. Prove that the following three characterizations of an idempotent monad $(T,\eta,\mu)$ are equivalent:
1. The multiplication $\mu \colon T^2 \Rightarrow T$ is a natural isomorphism (hence, the appellation ``idempotent'').
2. Each component of $\mu \colon T^2 \Rightarrow T$ is a monomorphism.
3. The natural transformations $\eta T, T\eta \colon T \Rightarrow T^2$ are equal.
