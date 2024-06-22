---
layout: page
title: universal
permalink: /context/universal
---
Some explanation is in order:
1. A coproduct $\coprod_\alpha A_\alpha$ is **disjoint** if each inclusion $A_\alpha \to \coprod_\alpha A_\alpha$ is a monomorphism and if the pullback of any two distinct inclusions is an initial object.
2. A colimit cone $(A_\alpha \to A)_\alpha$ is **universal** if the pullbacks of these maps along any $B \to A$ define a colimit cone $(B \times_A A_\alpha \to B)_\alpha$.
3. An **effective** equivalence relation is one that arises, as in Example \ref{ex:kernel-pair}, as a kernel pair of some morphism.
4. Finally, recall from Definition \ref{defn:separator} that a **separating set** for $\mathsf{E}$ is a set of objects $\mathcal{G} \subset \mathrm{ob}\mathsf{E}$ that is jointly separating: for any $f,g \colon B \rightrightarrows A$ with $f \neq g$ there is some $h \colon G \to B$, with $G \in \mathcal{G}$, so that $fh \neq gh$.
