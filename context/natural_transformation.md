---
layout: page
title: natural transformation
permalink: /context/natural_transformation
---
Given categories $\cC$ and $\cD$ and functors $F,G \colon \cC \rightrightarrows \cD$, a **natural transformation** $\alpha \colon F \To G$ consists of:\n1. an arrow $\alpha_c \colon Fc \to Gc$ in $\cD$ for each object $c\in \cC$, the collection of which define the **components** of the natural transformation,\nso that, for any morphism $f \colon c \to c'$ in $\cC$, the following square of morphisms in $\cD$\n$$ \vcenter{\xymatrix{ Fc \ar[d]_{Ff} \ar[r]^{\alpha_c} & Gc \ar[d]^{Gf} \\ Fc' \ar[r]_{\alpha_{c'}} & Gc'}}$$\n**commutes**, i.e., has a common composite $Fc \to Gc'$ in $\cD$.\n\nA **natural isomorphism** is a natural transformation $\alpha \colon F \To G$ in which every component $\alpha_c$ is an isomorphism. In this case, the natural isomorphism may be depicted as $\alpha \colon F \cong G$.
