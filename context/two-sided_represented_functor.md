---
layout: page
title: two-sided represented functor
permalink: /context/two-sided_represented_functor
---
If $\cC$ is locally small, then there is a **two-sided represented functor**\n$$ \cC(-,-) \colon \cC^\op \times \cC \to \cat{Set}$$ defined in the evident manner. A pair of objects $(x,y)$ is mapped to the hom-set $\cC(x,y)$. A pair of morphisms $f \colon w \to x$ and $h \colon y \to z$ is sent to the function $$  \xymatrix@C=8pt@R=8pt{\cC(x,y) \ar[rr]^-{(f^*,h_*)} &&  \cC(w,z) \\ g  & \mapsto & hgf}$$ that takes an arrow $g \colon x \to y$ and then pre-composes with $f$ and post-composes with $h$ to obtain $hgf \colon w \to z$.
