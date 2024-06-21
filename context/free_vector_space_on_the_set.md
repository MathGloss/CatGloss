---
layout: page
title: free vector space on the set
permalink: /context/free_vector_space_on_the_set
---
A more interesting challenge is to reverse the direction of this translation and build a vector space from a set $S$. Cardinality restrictions might prevent the direct use of $S$ as the set of vectors for a $\kk$-vector space, and even without this obstruction there is no natural way to define vector addition in $S$.\nInstead, a more natural way to build a vector space  is to let the elements of $S$ serve as a basis: vectors are then finite formal sums  $k_1s_1 + \cdots + k_n s_n$ with $k_i \in \kk$,  $s_i \in S$, and $n \geq 0$. This defines a vector space $\kk[S]$ whose dimension is equal to the cardinality of $S$, called the **free vector space on the set** $S$. Moreover, as our use of the adjective ``natural'' would suggest,  this construction is functorial, defining a functor $\kk[-] \colon \cat{Set} \to \cat{Vect}_\kk$: a function $f \colon S \to T$ induces a linear map $\kk[f] \colon \kk[S] \to \kk[T]$ defined on the basis elements in the evident way.
