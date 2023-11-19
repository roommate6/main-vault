# Definitions

## Relation

Let A and B be [[Set#Nonempty set]]s. A relation R from A to B is a [[Subset]] of $\text{A} \times \text{B}$. If R $\subseteq$ $\text{A} \times \text{B}$ and (a,b) $\in$ R, we say that a is related to b by R, and we also write **a R b**. If a is not related to b by R, we write a $\centernot{\text{R}}$ b.

---

Frequently, A and B are equal. In this case, we often say that R $\subseteq$ $\text{A} \times \text{A}$ is a relation on A, insted of a relation from A to A.

---

**Let R $\subseteq$ $\text{A} \times \text{B}$ be a relation from A to B**:

## Domain

The domain of R, denoted Domain(R), is the set of elements in A that are related to some element in B.

## Range

The set of elements in B that are related to some element in A.

## R-relative set of x

If x $\in$ A, we define R(x), the R-relative set of x, to be the set of all y in B with the property that x is R-related to y.

$$R(x) = \{ y \in B\space |\space x\space R\space y\}.$$

## R-relative set of $A_1$

If $A_1 \subseteq A$, then R($A_1$) is the union of the sets R(x), where $x \in A_1$.

$$R(A_1) = \{ y \in B\space |\space x\space R\space y\space \text{for some x in}\space A_1 \}$$
## Theorems

1. Let $A_1$ and $A_2$ be subsets of A. Then:

- If $A_1 \subseteq A_2$, then R($A_1$) $\subseteq$ R($A_2$).
- $R(A_1 \cup A_2) = R(A_1) \cup R(A_2)$.
- $R(A_1 \cap A_2) \subseteq R(A_1) \cap R(A_2)$.

2. Let R and S be relations from A to B. If R(a) = S(a) for all a in A, then R = S.
