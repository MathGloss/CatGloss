---
layout: page
title: space of ordered configurations of $n$ points
permalink: /context/space_of_ordered_configurations_of_$n$_points
---
More formally, the **space of ordered configurations of $n$ points** is a subspace of the product space $X^n$, namely the complement of the ``fat diagonal''\n$$ \textup{fun}_n(X) \coloneqq \big\{ (x_1,\ldots, x_n) \in X^n \bigm| x_i \neq x_j\ \forall i \neq j\big\}.$$\nThe symmetric group $\Sigma_n$ acts on $X^n$ by permuting the coordinates, and this action restricts to the subspace $\textup{fun}_n(X)\subset X^n$. The colimit of the diagram $\textup{fun}_n(X) \colon \mathsf{B}\Sigma_n \to \textup{\textsf{cat}}$ defines the **space of configurations of $n$ points**\n$$ \textup{fun}_n(X) \coloneqq \mathrm{colim} \left( \mathsf{B}\Sigma_n \xrightarrow{\fun{PConf}_n(X)} \textup{\textsf{cat}}\right).$$ Exercise \ref{exc:orbit-colimit} describes its underlying set.
