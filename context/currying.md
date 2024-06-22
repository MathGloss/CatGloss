---
layout: page
title: currying
permalink: /context/currying
---
The product bifunctor\n$$\cat{Set} \times \cat{Set} \xrightarrow{\times} \cat{Set}$$ is closed: the operation called **currying** in computer science defines a family of natural isomorphisms\n$$ \{ A \times B \xrightarrow{f} C \} \cong \{ A \xrightarrow{f} C^B\} \cong \{ B \xrightarrow{f} C^A\}.$$ Thus, the product and exponential bifunctors $$ \cat{Set} \times \cat{Set} \xrightarrow{\times} \cat{Set}, \quad \cat{Set}^\op \times \cat{Set} \xrightarrow{(-)^{(-)}}  \cat{Set}, \quad \cat{Set}^\op \times \cat{Set} \xrightarrow{(-)^{(-)}}  \cat{Set} $$ define a two-variable adjunction.
