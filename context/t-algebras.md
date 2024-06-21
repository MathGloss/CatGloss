---
layout: page
title: $T$-algebras
permalink: /context/t-algebras
---
We have seen, in Lemma \ref{lem:monad-from-adj}, that any adjunction presents a monad on the category serving as the domain of its left adjoint. A natural question is whether all monads arise this way. For instance, is there any adjunction that gives rise to the power set monad on $\cat{Set}$? Perhaps surprisingly, the answer is yes: any monad $T$ on a category $\cC$ can be recovered from two (typically distinct) adjunctions that are moreover universal with this property. The initial such adjunction, in a category to be introduced shortly, is between $\cC$ and the **Kleisli category** $\cC_T$ of $T$. The terminal such adjunction is between $\cC$ and the **Eilenberg--Moore category** $\cC^T$ of $T$, also called the category of **$T$-algebras**.
