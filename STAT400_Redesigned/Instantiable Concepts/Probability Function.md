---
tags:
  - concept
aliases:
---
\begin{relations}
	-definition_depend_on-> [[Sample Space]]($S$), [[Sigma-algebra]]($B$) %%depend on and is not a child of%%
	-has_element-> [[]]
	-owns_concept-> [[]]
	-owns_property-> [[]]
	-has_property_axis->  [[]]
	-parent_on_axis [no_axis]->  [[]] %%some popular non-property axis: subset/no_axis e.g. [[matrix]] & [[square matrix]], subset of instance [[Vector Space]] & [[Subspace]]%%
	-pipeline[some concept/pipeline]->  [[]]
\end{relations}

\begin{def}
a probability function is a function $P$ with domain $B$ (sigma-algebra) that satisfies
1. $P(A)\ge 0, ~ \forall A \in B$
2. $P(S)=1$
3. If $A_1, A_2, ... \in B$ are pairwise disjoint, then $P(\bigcup_{i=1}^\infty A_i) = \sum_{i=1}^\infty P(A_i)$

These three properties are often called "axioms of probability", or "Kolmogorov axioms". Any function that satisfies these axioms is called a probability function.

The following alternative definition is often used so that the axioms are satisfied by default:
Let $S={s_1,...,s_n}$ be a finite set, let $B$ be any sigma algebra of subset $S$. Let $p_1,...,p_n$ be non-negative numbers that sum to $1$. For any $A\in B$, define $P(A)$ by $P(A)=\sum_{\{i:s_i\in A\}}p_i$; Then $P(A)$ is a probability function on $B$. This remains true if $S=\{s_1,...,s_n\}$ is a finite set.

[[Calculus of Probabilities]]
\end{def}

\begin{notation}
$P$
\end{notation}

\begin{instantiation}
\end{instantiation}