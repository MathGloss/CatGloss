---
layout: page
title: preserves
permalink: /context/preserves
---
A functor $L \colon \cE \to \cF$ **preserves** a left Kan extension $(\Lan_KF,\eta)$ if the whiskered composite $(L \Lan_K F, L\eta)$ is the left Kan extension of $LF$ along $K$.\n$$\xymatrix{ \cC \ar[rr]^F \ar[dr]_K & \ar@{}[d]|(.4){\Downarrow \eta} & \cE \ar[r]^L & \cF \ar@{}[dr]|*+{\cong} & \cC \ar[rr]^{LF} \ar[dr]_K & \ar@{}[d]|(.4){\Downarrow} & \cF \\ & \cD \ar[ur]_{\Lan_KF} & & & & \cD \ar@{-->}[ur]_{\Lan_KLF} }$$
