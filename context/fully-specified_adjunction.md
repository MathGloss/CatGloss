---
layout: page
title: fully-specified adjunction
permalink: /context/fully-specified_adjunction
---
\begin{rmk} Proposition  \ref{prop:unified-adjunction} reveals that the data of a **fully-specified adjunction** can be presented in two equivalent forms: it consists of a pair of functors $F \colon \mathsf{C} \rightleftarrows \mathsf{D} \colon G$ together with
1. a natural family of isomorphisms $\mathsf{D}(Fc,d) \cong \mathsf{C}(c,Gd)$ for all $c \in \mathsf{C}$ and $d \in \mathsf{D}$,
or, equivalently,
1. natural transformations $\eta \colon 1_\mathsf{C} \Rightarrow GF$ and $\epsilon \colon FG \Rightarrow 1_\mathsf{D}$ so that $G\epsilon \cdot \eta G = 1_G$ and $\epsilon F \cdot F \eta = 1_F$.
Indeed, either of the unit and the counit alone, satisfying an appropriate universal property, suffices to determine a fully specified adjunction: \eqref{itm:original-defn} and \eqref{itm:unit-counit-defn} are each equivalent to either of
1. a natural transformation $\eta \colon 1_\mathsf{C} \Rightarrow GF$ so that the function
$$ \xymatrix{ \cD(Fc,d) \ar[r]^-G & \cC(GFc,Gd) \ar[r]^-{(\eta_c)^*} & \mathsf{C}(c,Gd)}$$ defines an isomorphism for all $c \in \mathsf{C}$ and $d \in \mathsf{D}$,
or, equivalently, and dually,
1. a natural transformation $\epsilon \colon FG \Rightarrow 1_\mathsf{D}$ so that the function
$$ \xymatrix{ \cC(c,Gd) \ar[r]^-F & \cD(Fc,FGd) \ar[r]^-{(\epsilon_d)_*} & \mathsf{D}(Fc,d)}$$ defines an isomorphism for all $c \in \mathsf{C}$ and $d \in \mathsf{D}$.
In particular, a morphism of adjunctions, introduced in Exercise \ref{exc:adj-mor}, is defined to be a morphism of fully-specified adjunctions. On account of the equivalence between \eqref{itm:original-defn}, \eqref{itm:unit-counit-defn}, \eqref{itm:unit-formula}, and \eqref{itm:counit-formula}, this notion can be presented in several equivalent ways.
\end{rmk}
