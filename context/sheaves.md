---
layout: page
title: sheaves
permalink: /context/sheaves
---
For a fixed topological space $X$, there is a natural inclusion $\mathcal{O}(X) \to \cat{Top}/X$ that sends an open subset $U \subset X$ to the continuous function $U \hookrightarrow X$. Apply the construction of Remark \ref{rmk:lan-adjunction} to this functor to define an adjunction\n$$ \xymatrix{ \cat{Top}/X \ar@<-1ex>[r] \ar@{}[r]|-\perp & \cat{Set}^{\mathcal{O}(X)^\op} \ar@<-1ex>[l]}$$\nbetween the category of presheaves on $\mathcal{O}(X)$ and the category of spaces over $X$. By Exercise \ref{exc:equiv-in-adjoint}, this adjunction, like all adjunctions, restricts to define an adjoint equivalence of categories, in this case between the category of **sheaves** on $X$ and the category of **\'{e**tale spaces} over $X$.