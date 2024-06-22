---
layout: page
title: sheaf
permalink: /context/sheaf
---
Let $X$ be a topological space and write $\mathcal{O}(X)$ for the poset of open subsets, ordered by inclusion. An $I$-indexed family of open subsets $U_i \subset U$ is said to  **cover** $U$ if the full diagram comprised of the sets $U_i$ and the inclusions of their pairwise intersections $U_i \cap U_j$ has colimit $U$. A presheaf $F \colon \mathcal{O}(X)^\mathrm{op} \to \textup{\textsf{cat}}$ is a **sheaf** if it preserves these colimits, sending them to limits in $\textup{\textsf{cat}}$. Applying Theorem \ref{thm:set-prod-equalizer}, the hypothesis is that for any open cover $\{U_i\}_{i \in I}$ of $U$, the following is an equalizer diagram:\n$$ \xymatrix@C=65pt{ F(U)\ \ar@{>->}[r]^-{F(U_i \hookrightarrow U)} & \prod\limits_{i \in I} F(U_i) \ar@<.5ex>[r]^-{F(U_i \cap U_j \hookrightarrow U_i) \cdot \pi_i}  \ar@<-.5ex>[r]_-{F(U_i \cap U_j \hookrightarrow U_j) \cdot \pi_j} & \prod\limits_{i,j \in I} F(U_i \cap U_j)}$$
