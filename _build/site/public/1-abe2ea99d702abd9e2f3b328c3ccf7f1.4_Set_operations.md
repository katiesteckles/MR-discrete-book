(set-operations-chapter)=

# Set Operations

There are various operations we can perform to compare and combine sets, and observe the relationships between them.

```{admonition} Definition 1.10 - Union
:label: set-union-definition

The **union** of two sets $A$ and $B$, denoted  $A \cup B$, is the set of elements that lie in $A$ or $B$ (or both); that is, 
$$A \cup B = \{x\ |\ x \in A \textrm{ or } x \in B\}$$

```

```{figure} ../_images/venn-union.png
:width: 250
:class: dark:hidden
:align: center
:alt: Venn diagram showing the union of two sets
```
```{figure} ../_images/venn-union-w.png
:width: 250
:class: hidden dark:block
:align: center
:alt: Venn diagram showing the union of two sets
```

For example, let $A = \{2, 4, 5\}$ and $B = \{1,4,6,8\}$. Then, $A \cup B = \{1, 2, 4, 5, 6, 8\}$. (Recall that each element in a set need only be listed once.)


```{admonition} Definition 1.11 - Intersection
:label: set-intersection-definition

The **intersection** of two sets $A$ and $B$, denoted $A \cap B$, is the set of elements that lie in both $A$ and $B$. That is,
$$A \cap B = \{x\ |\ x \in A \textrm{ and } x \in B\}$$

```

```{figure} ../_images/venn-intersection.png
:width: 250
:class: dark:hidden
:align: center
:alt: Venn diagram showing the intersection of two sets
```
```{figure} ../_images/venn-intersection-w.png
:width: 250
:class: hidden dark:block
:align: center
:alt: Venn diagram showing the intersection of two sets
```

For example,

- Let $A = \{2,4,5\}$ and $B = \{1,4,6,8\}$ Then $A \cap B = \{4\}$.

- Let $A = \{2,4,5\}$ and $B = \{1,3\}$. Then $A \cap B = \varnothing$.


```{admonition} Note
:class: important

If a set contains only a single element, it is sometimes called a **singleton set** or **unit set**.
```

If two sets do not intersect, we say they have an empty intersection, and write $A \cap B = \varnothing$.


```{admonition} Definition 1.12 - Symmetric Difference
:label: set-symdiff-definition

The **symmetric difference** of two sets $A$ and $B$, denoted $A \oplus B$, is the set of elements that lie in one of $A$ or $B$ but not in both. We can write(
$$ A \oplus B = (A \cup B) \setminus (A \cap B) = (A \setminus B) \cup (B \setminus A)$$

```

```{figure} ../_images/venn-symdiff.png
:width: 250
:class: dark:hidden
:align: center
:alt: Venn diagram showing the symmetric difference of two sets
```
```{figure} ../_images/venn-symdiff-w.png
:width: 250
:class: hidden dark:block
:align: center
:alt: Venn diagram showing the symmetric difference of two sets
```

For example,

- Let $U = \mathbb{N}$ be the universal set, and let $A = \{1, 2, 3, 4\}$, $B = \{3, 4, 5, 6, 7\}$, $C = \{2, 3, 8, 9\}$, and let $E = \{2, 4, 6, 8, \ldots\}$ be the even numbers. Then
$$A \oplus B = \{1, 2, 5, 6, 7\} \qquad B \oplus C = \{2, 4, 5, 67, 8, 9\} \qquad A \oplus C = \{ 1, 4, 8, 9}$$



Then:
𝑨 ⊕ 𝑩 = {𝟏, 𝟐, 𝟓, 𝟔, 𝟕}, 𝑩 ⊕ 𝑪 = {𝟐, 𝟒, 𝟓, 𝟔, 𝟕, 𝟖, 𝟗}
𝑨 ⊕ 𝑪 = {𝟏, 𝟒, 𝟖, 𝟗}, 𝑨 ⊕ 𝑬 = {𝟏, 𝟑, 𝟔, 𝟖, 𝟏𝟎, . . . . . }
The operations ∪,∩ and\can be repeated or combined to derive more sets.
Example
Let 𝐴 = {1,2,3,4}, 𝐵 = {3,4,5,6,7} and 𝐶 = {6,7,8}.
. Express in tabular form the composite sets:
i. (𝐴 ∪ 𝐵) ∩ 𝐶 = {1,2,3,4, ⥂ 5,6,7} ∩ {6,7,8} = {6,7}.
ii. (𝐴 ∪ 𝐶)\(𝐵 ∪ 𝐶) = {1,2}
Note that in any mathematical expression containing brackets ( ), we must perform the
operations inside the bracket(s) first
Other examples will be discussed in the lecture
15
1.6.5 The disjoint of two sets
A and B are said to be disjoint or nonintersecting if they have no elements in common or, using
the definition of intersection, 𝐴 ∩ 𝐵 = 𝜑, the empty set.
Suppose 𝑆 = 𝐴 ∪ 𝐵 and 𝐴 ∩ 𝐵 = 𝜑 , then S is called the disjoint union of A and B.
Example
Let 𝐴 = {1,2,3,4}, 𝐵 = {3,4,5,6,7} and 𝐶 = {6,7,8}.
Then 𝐴 ∪ 𝐵 = {1,2,3,4,5,6,7},
𝐴 ∩ 𝐵 = {3,4},
𝐶\𝐵 = {8}.
Note that A and C are disjoint (i.e. their intersection is the empty set).
The following properties of union and intersection should be noted.
Property 1: Every element 𝑥 in 𝐴 ∩ 𝐵 belongs to both A and B; hence 𝑥 belongs to 𝐴 and
𝑥 belongs to B. Thus 𝐴 ∩ 𝐵 is a subset of A and of B; namely
𝐴 ∩ 𝐵 ⊆ 𝐴 and 𝐴 ∩ 𝐵 ⊆ 𝐵
Property 2: An element 𝑥 belongs to the union 𝐴 ∪ 𝐵 if 𝑥 belongs to 𝐴 or 𝑥 belongs to 𝐵
Hence every element in 𝐴 belongs to 𝐴 ∪ 𝐵, and every element in 𝐵 belongs to 𝐴 ∪ 𝐵.
That is, 𝐴 ⊆ 𝐴 ∪ 𝐵 and 𝐵 ⊆ 𝐴 ∪ 𝐵.
1.6.6 Duality:
Let 𝐸 be an equation of set algebra. The dual 𝑬∗of 𝐸 is the equation obtained by replacing each
occurrence of ⋃, ⋂, U, Ø in E by ⋂, ⋃, Ø, U respectively.
Example: (U⋂ A) ⋃ (B⋂ A) =A is (Ø⋃ A ) ⋂ (B⋃ A) = A.
16





```{admonition} Definition 1.? - Symmetric difference
:label: symmetric-difference-definition

The **symmetric difference of two sets** $A$ and $B$, denoted by $A\oplus B$, consists of those elements which belongs to either $A$ or $B$ but not to both. That is, $A \oplus B = \{ x | x \in A \cup x\in B, x \not\in A \cap B \} = (A\cup B) \setminus (A \cap B) = (A\setminus B) \cup (B\setminus A)$ 

```