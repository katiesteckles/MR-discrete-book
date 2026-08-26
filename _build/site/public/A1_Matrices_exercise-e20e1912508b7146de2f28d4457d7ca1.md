---
numbering: false
---

(matrices-exercises-solutions)=

# Matrices Exercise Solutions

```{admonition} Solution to Exercise 1.1
:class: seealso

{prf:ref}`Exercise 1.1<matrices-ex1>`

(a) $ A = \begin{pmatrix} 
    2 & 3 & 4 \\
    3 & 4 & 5 \\
    4 & 5 & 6 
    \end{pmatrix} $

(b) $ B = \begin{pmatrix}
        1 & -1 & 1 & -1 \\
        -1 & 1 & -1 & 1 \\
        1 & -1 & 1 & -1 \\
        -1 & 1 & -1 & 1
        \end{pmatrix} $

(c) $ C = \begin{pmatrix}
        0 & 1 & 1 & 1 \\
        -1 & 0 & 1 & 1 \\
        -1 & -1 & 0 & 1 \\
        -1 & -1 & -1 & 0
    \end{pmatrix} $
```

```{admonition} Solution to Exercise 1.2
:class: seealso

{prf:ref}`Exercise 1.2<matrices-ex-hilbert>`

(a) &emsp; The $4 \times 4$ Hilbert matrix is

$$ \begin{align*}
    H = 
    \begin{pmatrix}
        1   & 1/2 & 1/3 & 1/4 \\
        1/2 & 1/3 & 1/4 & 1/5 \\
        1/3 & 1/4 & 1/5 & 1/6 \\
        1/4 & 1/5 & 1/6 & 1/7
    \end{pmatrix}.
\end{align*} $$

(b) &emsp; Since addition of two numbers is commutative, i.e., $i + j = j + i$ then $h_{ij} = h_{ji}$ for all $i, j = 1, 2, \ldots, n$ then the $n \times n$ Hilbert matrix is symmetric.  

```

```{admonition} Solution to Exercise 1.3
:class: seealso

{prf:ref}`Exercise 1.3<matrices-ex2>`

(a) &emsp; $A + B = \begin{pmatrix} 1 + 3 & -3 + 0 \\ 4 + (-1) & 2 + 5 \end{pmatrix} = \begin{pmatrix} 4 & -3 \\ 3 & 7 \end{pmatrix}$

(b) &emsp; $B + C$ is undefined since $B$ is $2\times 2$ and $C$ is $2\times 1$

(c) &emsp; $A^\mathsf{T} = \begin{pmatrix} 1 & 4 \\ -3 & 2 \end{pmatrix}$

(d) &emsp; $C^\mathsf{T} = \begin{pmatrix} 5 & 9 \end{pmatrix}$

(e) &emsp; $3 B - A = \begin{pmatrix} 9 & 0 \\ -3 & 15 \end{pmatrix} - \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} = \begin{pmatrix} 8 & 3 \\ -7 & 13 \end{pmatrix}$

(f) &emsp;  $(F^\mathsf{T})^\mathsf{T} = \begin{pmatrix} 1 \\ 2 \\ 4 \end{pmatrix}^\mathsf{T} = \begin{pmatrix} 1 & -2 & 4 \end{pmatrix} = F$

(g) &emsp; $A^\mathsf{T} + B^\mathsf{T} = \begin{pmatrix} 1 & 4 \\ -3 & 2 \end{pmatrix} + \begin{pmatrix} 3 & -1 \\ 0 & 5 \end{pmatrix} = \begin{pmatrix} 4 & 3 \\ -3 & 7 \end{pmatrix}$

(h) &emsp; $(A + B)^\mathsf{T} = \begin{pmatrix} 4 & -3 \\ 3 & 7 \end{pmatrix}^\mathsf{T} = \begin{pmatrix} 4 & 3 \\ -3 & 7 \end{pmatrix}$
```

```{admonition} Solution to Exercise 1.4
:class: seealso
 
 {prf:ref}`Exercise 1.4<matrices-ex3>`

(a) &emsp; $AB = \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} \begin{pmatrix} 3 & 0 \\ -1 & 5 \end{pmatrix} = \begin{pmatrix} 3 + 3 & 0 - 15 \\ 7 - 2 & 0 + 10 \end{pmatrix} = \begin{pmatrix}6 & -15 \\ 10 & 10 \end{pmatrix}$

(b) &emsp; $BA = \begin{pmatrix} 3 & 0 \\ -1 & 5 \end{pmatrix}\begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} = \begin{pmatrix} 3 + 0 & -9 + 0 \\ -1 + 20 & 3 + 10 \end{pmatrix} = \begin{pmatrix} 3 & -9 \\ 19 & 13 \end{pmatrix}$

(c) &emsp; $AC = \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}\begin{pmatrix} 5 \\ 9 \end{pmatrix} = \begin{pmatrix} 15 - 27 \\ 20 + 18 \end{pmatrix} = \begin{pmatrix} -22 \\ 38 \end{pmatrix}$

(d) &emsp; $CA$ is undefined since $C$ has 1 column and $A$ has 2 rows

(e) &emsp; $C^\mathsf{T}C = \begin{pmatrix} 5 & 9 \end{pmatrix} \begin{pmatrix} 5 \\ 9 \end{pmatrix} = 25 + 81 = 106$

(f) &emsp; $CC^\mathsf{T} = \begin{pmatrix} 5 \\ 9 \end{pmatrix}\begin{pmatrix} 5 & 9 \end{pmatrix} = \begin{pmatrix} 25 & 45 \\ 45 & 81 \end{pmatrix}$

(g) &emsp; 

$$ \begin{align*}
    DE &= \begin{pmatrix} 1 & 1 & 3 \\ 4 & -2 & 3 \end{pmatrix} \begin{pmatrix} 1 & 2 \\ 0 & 6 \\ -2 & 3 \end{pmatrix} = \begin{pmatrix} 1 + 0 - 6 & 2 + 6 + 9 \\ 4 + 0 - 6 & 8 - 12 + 9 \end{pmatrix} \\
    &= \begin{pmatrix} -5 & 17 \\ -2 & 5 \end{pmatrix}
\end{align*} $$

(h) &emsp; 

$$ \begin{align*}
    GH &= \begin{pmatrix} 4 & 2 & 3 \\ -2 & 6 & 0 \\ 0 & 7 & 1 \end{pmatrix}
    \begin{pmatrix} 1 & 0 & 1 \\ 5 & 2 & -2 \\ 2 & -3 & 4 \end{pmatrix} \\
    &= \begin{pmatrix} 
        4 + 10 + 6 & 0 + 4 - 9 & 4 - 4 + 12 \\
        -2 + 30 + 0 & 0 + 12 + 0 & -2 - 12 + 0 \\
        0 + 35 + 2 & 0 + 14 - 3 & 0 - 14 + 4
    \end{pmatrix} \\
    &= \begin{pmatrix} 20 & -5 & 12 \\ 28 & 12 & -14 \\ 37 & 11 & -10 \end{pmatrix}
\end{align*} $$

(i) &emsp; 

$$ \begin{align*}
    A(DE) &= \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} \left(
    \begin{pmatrix} 1 & 1 & 3 \\ 4 & -2 & 3 \end{pmatrix} 
    \begin{pmatrix} 1 & 2 \\ 0 & 6 \\ -2 & 3 \end{pmatrix} \right) \\
    &= \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}
    \begin{pmatrix} -5 & 17 \\ -2 & 5 \end{pmatrix} \\
    &= \begin{pmatrix} 1 & 2 \\ -24 & 78 \end{pmatrix}
\end{align*} $$

(j) &emsp; 

$$ \begin{align*}
    (AD)E &= \left(
    \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}
    \begin{pmatrix} 1 & 1 & 3 \\ 4 & -2 & 3 \end{pmatrix}
    \right)
    \begin{pmatrix} 1 & 2 \\ 0 & 6 \\ -2 & 3 \end{pmatrix} \\
    &= \begin{pmatrix} -11 & 7 & -6 \\ 12 & 0 & 18 \end{pmatrix}
    \begin{pmatrix} 1 & 2 \\ 0 & 6 \\ -2 & 3 \end{pmatrix} \\
    &= \begin{pmatrix} 1 & 2 \\ -24 & 78 \end{pmatrix}
\end{align*} $$

(k) &emsp; 

$$ \begin{align*}
    A^3 &= \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}
    \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}
    \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} \\
    &= \begin{pmatrix} -11 & -9 \\ 12 & -8 \end{pmatrix}
    \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} \\
    &= \begin{pmatrix} -47 & 15 \\ -20 & -52 \end{pmatrix}
\end{align*} $$

(l) &emsp; 

$$ \begin{align*}
    G^2 &= \begin{pmatrix} 4 & 2 & 3 \\ -2 & 6 & 0 \\ 0 & 7 & 1 \end{pmatrix}
    \begin{pmatrix} 4 & 2 & 3 \\ -2 & 6 & 0 \\ 0 & 7 & 1 \end{pmatrix} \\
    &= \begin{pmatrix} 12 & 41 & 15 \\ -20 & 32 & -6 \\ -14 & 49 & 1 \end{pmatrix} \\
    \therefore G^4 &= G^2G^2 = 
    \begin{pmatrix} 12 & 41 & 15 \\ -20 & 32 & -6 \\ -14 & 49 & 1 \end{pmatrix}
    \begin{pmatrix} 12 & 41 & 15 \\ -20 & 32 & -6 \\ -14 & 49 & 1 \end{pmatrix} \\
    &=
    \begin{pmatrix} -886 & 2539 & -51 \\ -796 & -90 & -498 \\ -1162 & 1043 & -503 \end{pmatrix}
\end{align*} $$
```

```{admonition} Solution to Exercise 1.5
:class: seealso
 
{prf:ref}`Exercise 1.5<matrices-ex5>`

(a) &emsp; $\det(A) = \begin{vmatrix} 1 & -3 \\ 4 & 2 \end{vmatrix} = 1(2) - (-3)(4) = 14$

(b) &emsp; $\det(B) = \begin{vmatrix} 3 & 0 \\ -1 & 5 \end{vmatrix} = 3(5) - 0 (-1) = 15$
````

```{admonition} Solution to Exercise 1.6
:class: seealso

{prf:ref}`Exercise 1.6<matrices-ex6>`
 
(c) &emsp;
\begin{align*}
    \det(G) &= 
    \begin{vmatrix}
         4 & 2 & 3 \\
        -2 & 6 & 0 \\
         0 & 7 & 1
    \end{vmatrix}
    = 4
    \begin{vmatrix} 6 & 0 \\ 7 & 1 \end{vmatrix} 
    - (-2)
    \begin{vmatrix} 2 & 3 \\ 7 & 1 \end{vmatrix}
    = 4(6 - 0) + 2(2 - 21) = -14
\end{align*} 

(d) &emsp; 
\begin{align*}
    \det(H) &=
    \begin{vmatrix}
        1 &  0 &  1 \\
        5 &  2 & -2 \\ 
        2 & -3 &  4
    \end{vmatrix}
    =
    \begin{vmatrix} 2 & -2 \\ -3 &  4 \end{vmatrix} +
    \begin{vmatrix} 5 &  2 \\  2 & -3 \end{vmatrix}
    = (8 - 6) + (-15 - 4) = -17
\end{align*} 
````


```{admonition} Solution to Exercise 1.7 
:class: seealso

{prf:ref}`Exercise 1.7<matrices-ex-inverse>`
 
$A$:

$$ \begin{align*}
    adj(A) &=
    \begin{pmatrix} 2 & -4 \\ 3 & 1 \end{pmatrix}^\mathsf{T}
    = 
    \begin{pmatrix} 2 & 3 \\ -4 & 1 \end{pmatrix},  \\
    \therefore A^{-1} &= \frac{1}{14} \begin{pmatrix} 2 & 3 \\ -4 & 1 \end{pmatrix}
    = \begin{pmatrix} 1/7 & 3/14 \\ -2/7 & 1/14 \end{pmatrix}.
\end{align*} $$

Check:

$$ \begin{align*}
    AA^{-1} &=
    \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}
    \begin{pmatrix} 1/7 & 3/14 \\ -2/7 & 1/14 \end{pmatrix}
    =
    \begin{pmatrix} 1/7 + 6/7 & 3/14 - 3/14 \\ 4/7 - 4/7 & 12/14 + 2/14 \end{pmatrix}
    = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}.
\end{align*} $$

$B$:

$$ \begin{align*}
    adj{B} &=
    \begin{pmatrix} 5 & 1 \\ 0 & 3 \end{pmatrix}^\mathsf{T}
    =
    \begin{pmatrix} 5 & 0 \\ 1 & 3 \end{pmatrix}, \\
    \therefore B^{-1} &= \frac{1}{15} \begin{pmatrix} 5 & 0 \\ 1 & 3 \end{pmatrix} 
    =
    \begin{pmatrix} 1/3 & 0 \\ 1/15 & 1/5 \end{pmatrix}.
\end{align*} $$

Check:

$$ \begin{align*}
    BB^{-1} &=
    \begin{pmatrix} 3 & 0 \\ -1 & 5 \end{pmatrix}
    \begin{pmatrix} 1/3 & 0 \\ 1/15 & 1/5 \end{pmatrix}
    =
    \begin{pmatrix} 1 + 0 & 0 + 0 \\ -1/3 + 5/15 & 0 + 1 \end{pmatrix}
    =
    \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}.
\end{align*} $$

$G$:

$$ \begin{align*}
    adj{G} &= 
    \begin{pmatrix}
          \begin{vmatrix} 6 & 0 \\ 7 & 1 \end{vmatrix} 
        &
        - \begin{vmatrix} -2 & 0 \\ 0 & 1 \end{vmatrix}
        &
          \begin{vmatrix} -2 & 6 \\ 0 & 7 \end{vmatrix}
        \\
        - \begin{vmatrix} 2 & 3 \\ 7 & 1 \end{vmatrix}
        &
          \begin{vmatrix} 4 & 3 \\ 0 & 1 \end{vmatrix}
        &
        - \begin{vmatrix} 4 & 2 \\ 0 & 7 \end{vmatrix}
        \\
          \begin{vmatrix} 2 & 3 \\ 6 & 0 \end{vmatrix}
        &
        - \begin{vmatrix} 4 & 3 \\ -2 & 0 \end{vmatrix}
        &
          \begin{vmatrix} 4 & 2 \\ -2 & 6 \end{vmatrix}
    \end{pmatrix}^\mathsf{T} \\   
    &=
    \begin{pmatrix}
          6 &  2 & -14 \\
         19 &  4 & -28 \\
        -18 & -6 &  28 
    \end{pmatrix}^\mathsf{T}
    =
    \begin{pmatrix}
          6 &  19 & -18 \\
          2 &   4 &  -6 \\
        -14 & -28 &  28
    \end{pmatrix}, \\
    \therefore G^{-1} 
    &= -\frac{1}{14}
    \begin{pmatrix}
          6 &  19 & -18 \\
          2 &   4 &  -6 \\
        -14 & -28 &  28
    \end{pmatrix}
    =
    \begin{pmatrix}
        -3/7 & -19/14 &  9/7 \\
        -1/7 &  -2/7  &  3/7 \\
         1   &   2    & -2
    \end{pmatrix}.
\end{align*} $$

Check:

$$ \begin{align*}
    GG^{-1} &=
    \begin{pmatrix}
         4 & 2 & 3 \\
        -2 & 6 & 0 \\
         0 & 7 & 1 
    \end{pmatrix}
    \begin{pmatrix}
        -3/7 & -19/14 &  9/7 \\
        -1/7 &  -2/7  &  3/7 \\
         1   &   2    & -2
    \end{pmatrix} \\
    &=
    \begin{pmatrix}
        -12/7 - 2/7 + 3 & -76/14 -  4/7 + 6 &  36/7 +  6/7 - 6 \\
          6/7 - 6/7 + 0 &  38/14 - 12/7 + 0 & -18/7 + 18/7 + 0 \\
          0   - 7/7 + 1 &   0    - 14/7 + 2 &   0   + 21/7 - 2
    \end{pmatrix} \\
    &=
    \begin{pmatrix}
        1 & 0 & 0 \\
        0 & 1 & 0 \\
        0 & 0 & 1
    \end{pmatrix}
\end{align*} $$

$H$:

$$ \begin{align*}
    adj(H) &=
    \begin{pmatrix}
          \begin{vmatrix} 2 & -2 \\ -3 & 4 \end{vmatrix}
        &
        - \begin{vmatrix} 5 & -2 \\ 2 & 4 \end{vmatrix}
        &
          \begin{vmatrix} 5 & 2 \\ 2 & -3 \end{vmatrix}
        \\
        - \begin{vmatrix} 0 & 1 \\ -3 & 4 \end{vmatrix}
        &
          \begin{vmatrix} 1 & 1 \\ 2 & 4 \end{vmatrix}
        &
        - \begin{vmatrix} 1 & 0 \\ 2 & -3 \end{vmatrix}
        \\
          \begin{vmatrix} 0 & 1 \\ 2 & -2 \end{vmatrix}
        &
        - \begin{vmatrix} 1 & 1 \\ 5 & -2 \end{vmatrix}
        &
          \begin{vmatrix} 1 & 0 \\ 5 & 2 \end{vmatrix}
    \end{pmatrix}^\mathsf{T} \\
    &=
    \begin{pmatrix}
        2 & -24 & -19 \\
        -3 & 2 & 3 \\
        -2 & 7 & 2 
    \end{pmatrix}^\mathsf{T}
    =
    \begin{pmatrix}
         2  & -3 & -2 \\
        -24 &  2 &  7 \\
        -19 &  3 &  2 
    \end{pmatrix}, \\
    \therefore H^{-1}
    &= -\frac{1}{17}
    \begin{pmatrix}
         2  & -3 & -2 \\
        -24 &  2 &  7 \\
        -19 &  3 &  2 
    \end{pmatrix}
    =
    \begin{pmatrix}
        -2/17 &  3/17 &  2/17 \\
        24/17 & -2/17 & -7/17 \\
        19/17 & -3/17 & -2/17
    \end{pmatrix} .
\end{align*} $$

Check:

$$ \begin{align*}
    HH^{-1} &=
    \begin{pmatrix}
        1 &  0 &  1 \\
        5 &  2 & -2 \\
        2 & -3 &  4 
    \end{pmatrix}
    \begin{pmatrix}
        -2/17 &  3/17 &  2/17 \\
        24/17 & -2/17 & -7/17 \\
        19/17 & -3/17 & -2/17
    \end{pmatrix}
    \\
    &=
    \begin{pmatrix}
        -2/17 +  0    + 19/17 &  3/17 - 3/17         &  2/17 - 2/17 \\
        -5/17 + 48/17 - 38/17 & 15/17 - 4/17 +  6/17 & 10/17 - 14/17 + 4/17 \\ 
        -4/17 - 72/17 + 76/17 &  6/17 + 6/17 - 12/17 &  4/17 + 21/17 - 8/17
    \end{pmatrix}
    \\
    &=
    \begin{pmatrix}
        1 & 0 & 0 \\
        0 & 1 & 0 \\
        0 & 0 & 1
    \end{pmatrix}
\end{align*} $$
```

```{admonition} Solution to Exercise 1.8
:class: seealso

{prf:ref}`Exercise 1.8<matrices-ex-AAT-symmetric>`

For $AA^\mathsf{T}$ to be symmetric we need to show that $AA^\mathsf{T} = (AA^\mathsf{T})^\mathsf{T}$

$$ \begin{align*}
    (AA^\mathsf{T})^\mathsf{T} &= 
    (A^\mathsf{T})^\mathsf{T}A^\mathsf{T} && \textsf{since $(AB)^\mathsf{T} = B^\mathsf{T}A^\mathsf{T}$} \\
    &= AA^\mathsf{T} && \textsf{since $(A^\mathsf{T})^\mathsf{T} = A$.}
\end{align*} $$

So $AA^\mathsf{T}$ is symmetric
```

```{admonition} Solution to Exercise 1.9
:class: seealso

{prf:ref}`Exercise 1.9<matrices-ex-invAB>`

To prove that $(AB)^{-1} = B^{-1}A^{-1}$ we need to show that $(AB)(B^{-1}A^{-1}) = I$

$$ \begin{align*}
    (AB)(B^{-1}A^{-1}) 
    &= A(BB^{-1}A^{-1}) && \textsf{associativity law} \\
    &= A(IA^{-1}) && \textsf{since $BB^{-1} = I$} \\
    &= AA^{-1} && \textsf{since $AI = IA = A$}\\
    &= I    && \textsf{definition of $A^{-1}.$} 
\end{align*} $$

Therefore $(AB)^{-1} = B^{-1}A^{-1}$.

```

```{admonition} Solution to Exercise 1.10
:class: seealso

{prf:ref}`Exercise 1.10<matrices-ex-AplusBsquared>`

Expanding out $(A + B)^2$

$$ (A + B)^2 = (A + B)(A + B) = A^2 + AB + BA + B^2, $$

therefore $(A + B)^2 \neq A^2 + 2AB + B^2$.

This would be true if $AB = BA$, i.e., $A = B$ or $A = I$ or $B = I$.
```

```{admonition} Solution to Exercise 1.11
:class: seealso

{prf:ref}`Exercise 1.11<matrices-ex-involutory-matrix>`

We need to show that $A^2 = I$

$$ \begin{align*}
    A^2 =
    \begin{pmatrix} a & b \\ c & -a \end{pmatrix} 
    \begin{pmatrix} a & b \\ c & -a \end{pmatrix} 
    = 
    \begin{pmatrix} a^2 + bc & 0 \\ 0 & a^2 + bc \end{pmatrix},
\end{align*} $$

so $a^2 + bc = 1$ for $A$ to be an [involutory matrix](https://en.wikipedia.org/wiki/Involutory_matrix).
```

```{admonition} Solution to Exercise 1.12
:class: seealso

{prf:ref}`Exercise 1.12<matrices-ex-trueorfalse>`

(a) &emsp; True 

Proof: Right multiply both sides of $A = B$ by $C$.

(b) &emsp; False, e.g., if $C = \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix}$ then this would hold for any two matrices.

(c) &emsp; False, e.g., if $A = \begin{pmatrix} 1 & 0 \\ 0 & 0 \end{pmatrix}$ and $B = \begin{pmatrix} 0 & 0 \\ 1 & 0 \end{pmatrix}$ then $AB = O$.

(d) &emsp; True 

Proof: Add $C$ to both sides of $A = B$.

(e) &emsp; False, e.g., if $A = \begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}$ then $A^2 = I$.

(f) &emsp; True 

Proof: If $B = A^2$ then $b_{ii} = \sum_{k=1}^n a_{ik}a_{ki}$ and since $A$ is symmetric then $a_{ik} = a_{ki}$ for $i = 1, 2, \ldots, n$ so $b_{ii} = \sum_{k=1}^n = a_{ij}^2$ which is always greater than or equal to 0.

(g) &emsp; True

Proof: 
- Let $A$ and $B$ be two $n \times n$ matrices then $C$ is also an $n \times n$ matrix.
- Let $A$ be an $n \times n$ matrix and $C$ be an $m \times m$ matrix and $B$ is a $p \times q$ matrix. $p = n$ and $q = m$ but $m = n$ so $p = q = m$ and $B$ is a square matrix.
- Ley $B$ be an $m \times m$ matrix and $C$ be an $n \times n$ matrix and $A$ is a $p \times q$ matrix. $p = n$ and $q = m$ but $m = n$ so $p = q = m$ and $A$ is a square matrix.

(h) &emsp; True

Proof: Let $B$ be a $p \times q$ matrix then since $C$ is an $m \times 1$ matrix then $q = 1$.

(i) &emsp; False, e.g., if $A = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$ then $A^3 = A$.
```

```{admonition} Solution to Exercise 1.13
:class: seealso

{prf:ref}`Exercise 1.13<matrices-ex8>`

(a)

$$ \begin{align*}
    5X &= A \\
    X &= \frac{1}{5} A \\
    &= \dfrac{1}{5}\begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} 
    = \begin{pmatrix} \frac{1}{5} & -\frac{3}{5} \\ \frac{4}{5} & \frac{2}{5} \end{pmatrix}
\end{align*} $$

(b)

$$ \begin{align*}
    X + A &= I \\
    X &= I - A \\
    &= \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} - \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} = \begin{pmatrix} 0 & 3 \\ -4 & -1 \end{pmatrix}
\end{align*} $$

(c)

$$ \begin{align*}
    2X - B &= A \\
    2X &= A + B \\
    X &= \dfrac{1}{2}(A + B) = \dfrac{1}{2}\left( \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} + \begin{pmatrix} 3 & 0 \\ -1 & 5 \end{pmatrix} \right) \\
    &= \dfrac{1}{2} \begin{pmatrix} 4 & -3 \\ 3 & 7 \end{pmatrix} = \begin{pmatrix} 2 & -\frac{3}{2} \\ \frac{3}{2} & \frac{7}{2} \end{pmatrix}
\end{align*} $$

(d)

$$ \begin{align*}
    XA &= I \\
    X &= IA^{-1} = A^{-1}I \\
    &= \dfrac{1}{14} \begin{pmatrix} 2 & 3 \\ -4 & 1 \end{pmatrix} = \begin{pmatrix} \frac{1}{7} & \frac{3}{14} \\ -\frac{2}{7} & \frac{1}{14} \end{pmatrix}
\end{align*} $$

(e)

$$ \begin{align*}
    BX &= A \\
    X &= B^{-1}A \\
    &= \dfrac{1}{15}\begin{pmatrix} 5 & 0 \\ 1 & 3 \end{pmatrix} \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} \\
    &= \dfrac{1}{15} \begin{pmatrix} 5 & -15 \\ 13 & 3\end{pmatrix} = \begin{pmatrix} \frac{1}{3} & -1 \\ \frac{13}{15} & \frac{1}{5} \end{pmatrix}
\end{align*} $$

(f)

$$ \begin{align*}
    A^2 &= X \\
    X &= \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix}\begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} = \begin{pmatrix} -11 & -9 \\ 12 & -8 \end{pmatrix}
\end{align*} $$

(g) &emsp; We begin by setting $X = \begin{pmatrix}a & b \\ c & d\end{pmatrix}$, and then $X^2 = B$ gives

$$ \begin{align*}
    \begin{pmatrix}a^2 + bc & ab + bd \\ ca+dc & cb+d^2\end{pmatrix} =
    \begin{pmatrix} a^2 + bc & b(a + d) \\ c(a + d) & cb + d^2 \end{pmatrix} =
    \begin{pmatrix} 3 & 0 \\ -1 & 5 \end{pmatrix}.
\end{align*} $$

Now we can solve the quadratic equations over $\mathbb{R}$, since $[X^2]_{12} = 0$ then

$$ \begin{align*}
    b(a + d) &= 0 \\
    \therefore b &= 0 \text{ or } a = -d.
\end{align*} $$

For the case when $b = 0$

$$ \begin{align*}
    a^2 + bc &= 3 \implies a = \pm \sqrt{3}, \\
    cb + d^2 &= 5 \implies d = \pm \sqrt{5}.
\end{align*} $$

So we have four possible solutions

$$ \begin{align*}
    X &= \begin{pmatrix} \pm \sqrt{3} & 0 \\ - 1 / (\pm \sqrt{3} \pm \sqrt{5}) & \pm\sqrt{5} \end{pmatrix}, \text{ or }\\
    X &= \begin{pmatrix} \pm \sqrt{3} & 0 \\ - 1 / (\pm \sqrt{3} \mp \sqrt{5}) & \mp\sqrt{5} \end{pmatrix}.
\end{align*} $$

For the case when $a = -d$

$$ \begin{align*}
    c(a + d) = 0c = -1,
\end{align*} $$

which is a contradiction so $a = -d$ yields no solutions.

(h) 

$$ \begin{align*}
    (X + A)B &= I \\
    X + A &= I B^{-1} \\
    X &= B^{-1} - A \\
    &= \frac{1}{15} \begin{pmatrix} 5 & 0 \\ 1 & 3 \end{pmatrix} - 
    \begin{pmatrix} 1 & -3 \\ 4 & 2 \end{pmatrix} \\
    &= \begin{pmatrix} -2/3 & 3 \\ -59/15 & -9/5 \end{pmatrix} \\
    &= \frac{1}{15} \begin{pmatrix} -10 & 45 \\ -59 & -27 \end{pmatrix}
\end{align*} $$
```
