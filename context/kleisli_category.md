---
layout: page
title: Kleisli category
permalink: /context/kleisli_category
---
Let $\cC$ be a category with a monad $(T,\eta,\mu)$. The **Kleisli category**  $\cC_T$ is defined so that\n1. its objects are the objects of $\cC$, and\n2. a morphism from $A$ to $B$ in $\cC_T$, depicted as $A \rightsquigarrow B$,  is a morphism $A \to TB$ in $\cC$. Identities and composition are defined using the monad structure:\n1. The unit $\eta_A \colon A \to TA$ defines the identity morphism $A \rightsquigarrow A  \in \cC_T$.\n2. The composite of a morphism $f \colon A \to TB$ from $A$ to $B$ with a morphism $g \colon B \to TC$ from $B$ to $C$ is defined to be\n$$ \xymatrix{ A \ar[r]^f & TB \ar[r]^{Tg} & T^2C \ar[r]^{\mu_C} & TC.}$$\nThe verification that these operations are associative and unital is left as Exercise \ref{exc:kleisli-cat}.
