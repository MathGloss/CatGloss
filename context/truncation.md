---
layout: page
title: truncation
permalink: /context/truncation
---
Write $\DDelta_{\leq n}$ for the full subcategory spanned by the first $n+1$ ordinals $[0],\ldots, [n]$ in $\DDelta$. Restriction along the inclusion functor $i_n \colon \DDelta_{\leq n} \hookrightarrow \DDelta$ is called $n$-**truncation**. As $\cat{Set}$ is complete and cocomplete, Corollary \ref{cor:kan-exist} implies that $n$-truncation admits both left and right adjoints:\n $$\xymatrix{\cat{Set}^{\DDelta^\op}  \ar[r]|{i_n^*} & \cat{Set}^{\DDelta_{\leq n}^\op} \ar@/^1.5pc/[l]^{\Ran_{i_n}} \ar@/_1.5pc/[l]_{\Lan_{i_n}} \ar@{}[l]^*+{\labelstyle{\perp}}_*+{\labelstyle\perp} }$$ The composite comonad on $\cat{Set}^{\DDelta^\op}$ is sk$_n$, the functor that maps a simplicial set to its $n$-**skeleton**. The composite monad on $\cat{Set}^{\DDelta^\op}$ is cosk$_n$, the functor that maps a simplicial set to its $n$-**coskeleton**. Furthermore, sk$_n$ is left adjoint to cosk$_n$, as is the case for any comonad and monad arising in this way (see Exercise \ref{exc:adjoint-comonad-monad}).
