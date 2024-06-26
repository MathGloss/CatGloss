---
layout: page
title: coskeleton
permalink: /context/coskeleton
---
Write $\DDelta_{\leq n}$ for the full subcategory spanned by the first $n+1$ ordinals $[0],\ldots, [n]$ in ${\mathbbe{\Delta}}$. Restriction along the inclusion functor $i_n \colon \DDelta_{\leq n} \hookrightarrow {\mathbbe{\Delta}}$ is called $n$-**truncation**. As $\textup{\textsf{cat}}$ is complete and cocomplete, Corollary \ref{cor:kan-exist} implies that $n$-truncation admits both left and right adjoints:
 $$\xymatrix{\cat{Set}^{{\mathbbe{\Delta}}^\mathrm{op}}  \ar[r]\mid{i_n^*} & \textup{\textsf{cat}}^{\DDelta_{\leq n}^\mathrm{op}} \ar@/^1.5pc/[l]^{\Ran_{i_n}} \ar@/_1.5pc/[l]_{\Lan_{i_n}} \ar@{}[l]^*+{\labelstyle{\perp}}_*+{\labelstyle\perp} }$$ The composite comonad on $\textup{\textsf{cat}}^{{\mathbbe{\Delta}}^\mathrm{op}}$ is sk$_n$, the functor that maps a simplicial set to its $n$-**skeleton**. The composite monad on $\textup{\textsf{cat}}^{{\mathbbe{\Delta}}^\mathrm{op}}$ is cosk$_n$, the functor that maps a simplicial set to its $n$-**coskeleton**. Furthermore, sk$_n$ is left adjoint to cosk$_n$, as is the case for any comonad and monad arising in this way (see Exercise \ref{exc:adjoint-comonad-monad}).
