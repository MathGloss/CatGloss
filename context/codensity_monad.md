---
layout: page
title: codensity monad
permalink: /context/codensity_monad
---
The **codensity monad** of $G \colon \cD \to \cC$ is given by the right Kan extension of $G$ along itself, whenever this exists.\n$$\xymatrix{ \cD \ar[rr]^G \ar[dr]_G & \ar@{}[d]|(.4){\Uparrow \epsilon} & \cC \\ & \cC \ar@{-->}[ur]_{\Ran_GG\eqqcolon T}}$$\nThe unit and multiplication natural transformations are defined using the universal property of $\epsilon \colon TG \To G$ as follows:\n$$\xymatrix{ \cD \ar[rr]^G \ar[dr]_G & \ar@{}[d]|(.4){\Uparrow 1_G} & \cC \ar@{}[dr]|*+{=} & \cD \ar[rr]^G \ar[dr]_G & \ar@{}[d]_(.4){\Uparrow\epsilon} \ar@{}[dr]|(.58){\exists !\Nwarrow\eta}& \cC \\ & \cC \ar[ur]_{1_\cC} &&  & \cC \ar@/^/[ur]^{T} \ar@/_1.5pc/[ur]_{1_\cC}& } $$\n$$\xymatrix{ \cD \ar[rrr]^G \ar@/^/[drr]^(.6)G \ar[dr]_G &  & \ar@{}[d]|(.4){\Uparrow \epsilon} & \cC \ar@{}[dr]|*+{=} & \cD \ar[rrr]^G \ar[dr]_G & \ar@{}[d]|(.4){\Uparrow\epsilon} &\ar@{}[d]|(.6){\exists !\Nwarrow\mu} &  \cC \\ & \cC \ar@{}[u]|(.4){\Uparrow\epsilon} \ar[r]_T & \cC \ar[ur]_{T}  &&  & \cC \ar@/^/[urr]^{T} \ar[r]_T & \cC \ar[ur]_T } $$
