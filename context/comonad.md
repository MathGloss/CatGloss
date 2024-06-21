---
layout: page
title: comonad
permalink: /context/comonad
---
A **comonad** on $\cC$ is a monad on $\cC^\op$: explicitly, a comonad consists of an endofunctor $K \colon \cC \to \cC$ together with natural transformations $\epsilon \colon K \To 1_\cC$ and $\delta \colon K \To K^2$ so that the diagrams dual to Definition \ref{defn:monad} commute in $\cC^\cC$.
