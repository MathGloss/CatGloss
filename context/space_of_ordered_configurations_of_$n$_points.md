---
layout: page
title: space of ordered configurations of $n$ points
permalink: /context/space_of_ordered_configurations_of_$n$_points
---
More formally, the **space of ordered configurations of $n$ points** is a subspace of the product space $X^n$, namely the complement of the ``fat diagonal''\n$$ \fun{PConf}_n(X) \coloneqq \big\{ (x_1,\ldots, x_n) \in X^n \bigm| x_i \neq x_j\ \forall i \neq j\big\}\rlap{{\,}.}$$\nThe symmetric group $\Sigma_n$ acts on $X^n$ by permuting the coordinates, and this action restricts to the subspace $\fun{PConf}_n(X)\subset X^n$. The colimit of the diagram $\fun{PConf}_n(X) \colon \cB\Sigma_n \to \cat{Top}$ defines the **space of configurations of $n$ points**\n$$ \fun{Conf}_n(X) \coloneqq \colim \left( \cB\Sigma_n \xrightarrow{\fun{PConf}_n(X)} \cat{Top}\right)\rlap{{\,}.}$$ Exercise \ref{exc:orbit-colimit} describes its underlying set.
