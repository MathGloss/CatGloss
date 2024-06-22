---
layout: page
title: homotopy category
permalink: /context/homotopy_category
---
Apply the construction of Remark \ref{rmk:lan-adjunction} to the embedding ${\mathbbe{\Delta}}\hookrightarrow\textup{\textsf{cat}}$ of the category of finite non-empty ordinals and order-preserving maps to define an adjunction\n$$ \xymatrix{ \cat{Cat} \ar@<-1ex>[r]_-N \ar@{}[r]|-\perp & \textup{\textsf{cat}}^{{\mathbbe{\Delta}}^\mathrm{op}}. \ar@<-1ex>[l]_-{h}}$$\nThe right adjoint defines the **nerve** of a category, while the left adjoint constructs the **homotopy category** of a simplicial set. The counit of this adjunction is an isomorphism, so Lemma \ref{lem:counit-conditions} implies that the nerve is fully faithful. Hence, $\textup{\textsf{cat}}$ defines a reflective subcategory of the category of simplicial sets, proving the claim made in Example \ref{exs:reflective-subcats}\eqref{itm:cat-nerve-embedding}.
