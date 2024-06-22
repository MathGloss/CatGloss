---
layout: page
title: preserves
permalink: /context/preserves
---
A functor $L \colon \mathsf{E} \to \mathsf{F}$ **preserves** a left Kan extension $(\Lan_KF,\eta)$ if the whiskered composite $(L \Lan_K F, L\eta)$ is the left Kan extension of $LF$ along $K$.\n$$\xymatrix{ \cC \ar[rr]^F \ar[dr]_K & \ar@{}[d]|(.4){\Downarrow \eta} & \mathsf{E} \ar[r]^L & \mathsf{F} \ar@{}[dr]|*+{\cong} & \mathsf{C} \ar[rr]^{LF} \ar[dr]_K & \ar@{}[d]|(.4){\Downarrow} & \mathsf{F} \\ & \mathsf{D} \ar[ur]_{\Lan_KF} & & & & \mathsf{D} \ar@{-->}[ur]_{\Lan_KLF} }$$
