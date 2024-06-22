---
layout: page
title: creates
permalink: /context/creates
---
For any class of diagrams $K \colon \mathsf{J} \to \mathsf{C}$ valued in $\mathsf{C}$, a functor $F \colon \mathsf{C} \to \mathsf{D}$
1. **preserves** those limits if for any diagram $K \colon \mathsf{J} \to \mathsf{C}$ and limit cone over $K$, the image of this cone defines a limit cone over the composite diagram $FK \colon \mathsf{J} \to \mathsf{D}$;
2. **reflects** those limits  if any cone over a diagram $K \colon \mathsf{J} \to \mathsf{C}$, whose image upon applying $F$ is a limit cone for the diagram $FK \colon \mathsf{J} \to \mathsf{D}$, is a limit cone over $K$; and
3. **creates** those limits if whenever $FK \colon \mathsf{J} \to \mathsf{D}$ has a limit in $\mathsf{D}$, there is some limit cone over $FK$ that can be lifted to a limit cone over $K$, and moreover $F$ reflects the limits in the class of diagrams.
