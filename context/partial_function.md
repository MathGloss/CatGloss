---
layout: page
title: partial function
permalink: /context/partial_function
---
These examples aside, the notion of isomorphism of categories is somewhat unnatural. To illustrate, consider the category $\cat{Set}^\partial$ of sets and partially-defined functions. A **partial function** $f\colon X \to Y$ is a function from a (possibly-empty) subset $X' \subset X$ to $Y$; the subset $X'$ is the **domain of definition** of the partial function $f$. The composite of two partial functions $f \colon X \to Y$ and $g \colon Y \to Z$ is the partial function whose domain of definition is the intersection of the domain of definition of $f$ with the preimage of the domain of definition of $g$.
