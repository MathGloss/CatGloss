---
layout: page
title: free $T$-algebra morphism
permalink: /context/free_$t$-algebra_morphism
---
Various notations are common for the Eilenberg--Moore category, many involving the string ``alg '' to emphasize the interpretation of its objects as ``algebras'' of some sort. The notation used here, while less evocative, has the virtue of being concise.\n\\n\begin{lem} For any  monad $(T,\eta,\mu)$ acting on a category $\mathsf{C}$, there is an adjunction\n$$ \xymatrix{ \cC \ar@<1ex>[r]^-{F^T} \ar@{}[r]|-\perp & \mathsf{C}^T \ar@<1ex>[l]^-{U^T}}$$ between $\mathsf{C}$ and the Eilenberg--Moore category whose induced monad is $(T,\eta,\mu)$.\n\end{lem}\n\begin{proof}\nThe functor $U^T \colon \mathsf{C}^T \to \mathsf{C}$ is the evident forgetful functor.  The functor $F^T \colon \mathsf{C} \to \mathsf{C}^T$ carries an object $A \in \mathsf{C}$ to the **free $T$-algebra** $$ F^T\! A \coloneqq (TA,\mu_A \colon T^2A \to TA)$$ and carries a morphism $f \colon A \to B$ to the **free $T$-algebra morphism** $$ F^T\! f \coloneqq  (TA,\mu_A) \xrightarrow{Tf} (TB,\mu_B).$$ Note that $U^TF^T=T$.
