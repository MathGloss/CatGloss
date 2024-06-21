---
layout: page
title: morphism of adjunctions
permalink: /context/morphism_of_adjunctions
---
A **morphism of adjunctions** from $F \dashv G$ to $F' \dashv G'$ is comprised of a pair of functors\n$$ \xymatrix{ \cC \ar[r]^H \ar@<-1ex>[d]_F \ar@{}[d]|\dashv & \cC' \ar@<-1ex>[d]_{F'} \ar@{}[d]|\dashv \\ \cD \ar@<-1ex>[u]_G \ar[r]_K & \cD' \ar@<-1ex>[u]_{G'}}$$ so that the square with the left adjoints and the square with the right adjoints both commute (i.e., $KF=F'H$ and $HG = G'K$) and satisfying one additional condition, which takes a number of equivalent forms. Prove that the following are equivalent:\n1. $H\eta = \eta' H$, where $\eta$ and $\eta'$ denote the respective units of the adjunctions.\n2. $K\epsilon = \epsilon' K$, where $\epsilon$ and $\epsilon'$ denote the respective counits of the adjunctions.\n3. Transposition across the adjunctions commutes with application of the functors $H$ and $K$, i.e., for every $c \in \cC$ and $d \in \cD$, the diagram\n$$ \xymatrix@=10pt{ \cD(Fc,d) \ar[r]^\cong \ar[d]_K & \cC(c,Gd) \ar[d]^H \\ \cD'(KFc,Kd) \ar@{=}[d] & \cC'(Hc, HGd) \ar@{=}[d] \\ \cD'(F'Hc,Kd) \ar[r]_\cong & \cC'(Hc, G'Kd)}$$ commutes.
