---
layout: page
title: two-sided represented functor
permalink: /context/two-sided_represented_functor
---
If $\mathsf{C}$ is locally small, then there is a **two-sided represented functor**\n$$ \mathsf{C}(-,-) \colon \mathsf{C}^\mathrm{op} \times \mathsf{C} \to \textup{\textsf{cat}}$$ defined in the evident manner. A pair of objects $(x,y)$ is mapped to the hom-set $\mathsf{C}(x,y)$. A pair of morphisms $f \colon w \to x$ and $h \colon y \to z$ is sent to the function $$  \xymatrix@C=8pt@R=8pt{\mathsf{C}(x,y) \ar[rr]^-{(f^*,h_*)} &&  \mathsf{C}(w,z) \\ g  & \mapsto & hgf}$$ that takes an arrow $g \colon x \to y$ and then pre-composes with $f$ and post-composes with $h$ to obtain $hgf \colon w \to z$.
