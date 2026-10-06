---
numbering: false
---

(matrices-exercises-solutions)=

# Matrices Exercise Solutions

```{admonition} Solution to Exercise 1.1
:class: seealso

{prf:ref}`Exercise 1.1<sets-ex1>`

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

{prf:ref}`Exercise 1.2<sets-ex-2>`

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

{prf:ref}`Exercise 1.3<sets-ex3>`

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
 
 {prf:ref}`Exercise 1.4<sets-ex4>`

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
 
{prf:ref}`Exercise 1.5<sets-ex5>`

(a) &emsp; $\det(A) = \begin{vmatrix} 1 & -3 \\ 4 & 2 \end{vmatrix} = 1(2) - (-3)(4) = 14$

(b) &emsp; $\det(B) = \begin{vmatrix} 3 & 0 \\ -1 & 5 \end{vmatrix} = 3(5) - 0 (-1) = 15$
````

```{admonition} Solution to Exercise 1.6
:class: seealso

{prf:ref}`Exercise 1.6<sets-ex6>`
 
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

