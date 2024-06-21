---
layout: page
title: Eilenberg--Moore category
permalink: /context/eilenberg--moore_category
---
Let $\cC$ be a category with a monad $(T,\eta,\mu)$. The **Eilenberg--Moore category** for $T$ or the **category of $T$-algebras** is the category $\cC^T$ whose: 1. objects are pairs $(A \in \cC, a \colon TA \to A)$, so that the diagrams\n$$ \vcenter{ \xymatrix{ A \ar[r]^-{\eta_A} \ar[dr]_{1_A} & TA \ar[d]^{a} & & T^2A \ar[r]^-{\mu_A} \ar[d]_{Ta} & TA \ar[d]^{a} \\ & A & & TA \ar[r]_-{a} & A}}$$\ncommute in $\cC$, and\n2. morphisms $f \colon (A,a) \to (B,b)$ are $T$-algebra **homomorphisms**: maps $f \colon A \to B$ in $\cC$ so that the square\n$$ \xymatrix{ TA \ar[d]_a \ar[r]^{Tf} & TB \ar[d]^b \\ A \ar[r]_f & B}$$ commutes,  with composition and identities as in $\cC$.
