---
layout: page
title: currying
permalink: /context/currying
---
The product bifunctor\n$$\textup{\textsf{cat}} \times \textup{\textsf{cat}} \xrightarrow{\times} \textup{\textsf{cat}}$$ is closed: the operation called **currying** in computer science defines a family of natural isomorphisms\n$$ \{ A \times B \xrightarrow{f} C \} \cong \{ A \xrightarrow{f} C^B\} \cong \{ B \xrightarrow{f} C^A\}.$$ Thus, the product and exponential bifunctors $$ \textup{\textsf{cat}} \times \textup{\textsf{cat}} \xrightarrow{\times} \textup{\textsf{cat}}, \quad \textup{\textsf{cat}}^\mathrm{op} \times \textup{\textsf{cat}} \xrightarrow{(-)^{(-)}}  \textup{\textsf{cat}}, \quad \textup{\textsf{cat}}^\mathrm{op} \times \textup{\textsf{cat}} \xrightarrow{(-)^{(-)}}  \textup{\textsf{cat}} $$ define a two-variable adjunction.
