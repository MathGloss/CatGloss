---
layout: page
title: idempotent monad
permalink: /context/idempotent_monad
---
The adjunction associated to a reflective subcategory of $\cC$ induces an **idempotent monad** on $\cC$. Prove that the following three characterizations of an idempotent monad $(T,\eta,\mu)$ are equivalent:\n1. The multiplication $\mu \colon T^2 \To T$ is a natural isomorphism (hence, the appellation ``idempotent'').\n2. Each component of $\mu \colon T^2 \To T$ is a monomorphism.\n3. The natural transformations $\eta T, T\eta \colon T \To T^2$ are equal.