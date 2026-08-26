---
numbering: false
---
(transformations-exercise-solutions-section)=

# Linear Transformations Exercise Solutions

```{admonition} Solution to Exercise 6.1
:class: seealso

{prf:ref}`Exercise 6.1<transformations-ex-linear-transformations>`

(a) Let $\mathbf{u} = (u_1, u_2), \mathbf{v} = (v_1, v_2) \in \mathbb{R}^2$ and $\alpha \in \mathbb{R}$

\begin{align*}
    T(\mathbf{u} + \alpha \mathbf{v}) 
    &= T\begin{pmatrix} u_1 + \alpha v_1 \\ u_2 + \alpha v_2 \end{pmatrix} 
    = \begin{pmatrix} 0 \\ u_2 + \alpha v_2 \end{pmatrix}, \\
    T(\mathbf{u}) + \alpha T(\mathbf{v})
    &= T\begin{pmatrix} u_1 \\ u_2 \end{pmatrix} + \alpha T \begin{pmatrix} v_1 \\ v_2 \end{pmatrix}
    = \begin{pmatrix} 0 \\ u_2 + \alpha v_2 \end{pmatrix},
\end{align*} 

therefore $T$ is a linear transformation.
    
(b) $T$ is not a linear transformation since 

\begin{align*}
    T\left( \begin{pmatrix} 1 \\ 0 \end{pmatrix} + \begin{pmatrix} 1 \\ 1 \end{pmatrix} \right) = \begin{pmatrix} 2 \\ 5 \end{pmatrix}, \\
    T\begin{pmatrix} 1 \\ 0 \end{pmatrix} + T\begin{pmatrix} 1 \\ 1 \end{pmatrix} = \begin{pmatrix} 2 \\ 10 \end{pmatrix}.
\end{align*} 

(c) Let $\mathbf{u} = (u_1, u_2), \mathbf{v} = (v_1, v_2) \in \mathbb{R}^2$ and $\alpha \in \mathbb{R}$

\begin{align*}
    T(\mathbf{u} + \alpha \mathbf{v})
    &= T\begin{pmatrix} u_1 + \alpha v_1 \\ u_2 + \alpha v_2 \end{pmatrix}
    = \begin{pmatrix} u_1 + \alpha v_1 \\ u_1 - u_2 + \alpha v_1 - \alpha v_2 \end{pmatrix}, \\
    T(\mathbf{u}) + \alpha T(\mathbf{v})
    &= T\begin{pmatrix} u_1 \\ u_2 \end{pmatrix} + \alpha T\begin{pmatrix} v_1 \\ v_2 \end{pmatrix}
    = \begin{pmatrix} u_1 + \alpha v_1 \\ u_1 + \alpha v_1 - u_2 - \alpha v_2\end{pmatrix},
\end{align*} 

therefore $T$ is a linear transformation.

(d) Let $\mathbf{u} = (u_1, u_2, v_3),\mathbf{v} = (v_1, v_2, v_3)\in \mathbb{R}^3$ and $\alpha \in \mathbb{R}$

 \begin{align*}
    T(\mathbf{u} + \alpha \mathbf{v}) 
    &= T\begin{pmatrix} u_1 + \alpha v_1 \\ u_2 + \alpha v_2 \\ u_3 + \alpha v_3 \end{pmatrix}
    = \begin{pmatrix} u_1 + u_2 + \alpha v_1 + \alpha v_2 \\  u_3 + \alpha v_3 \end{pmatrix} , \\
    T(\mathbf{u}) + \alpha T(\mathbf{v}) 
    &= T\begin{pmatrix} u_1 \\ u_2 \\ u_3 \end{pmatrix} + \alpha \begin{pmatrix} v_1 \\ v_2 \\ v_3 \end{pmatrix}
    = \begin{pmatrix} u_1 + \alpha v_1 + u_2 + \alpha v_2 \\  u_3 + \alpha v_3 \end{pmatrix}
\end{align*} 

therefore $T$ is a linear transformation.

(e) $T$ is not a linear transformation since

 \begin{align*}
    T\left( \begin{pmatrix} 1 \\ 0 \end{pmatrix} + \begin{pmatrix} 1 \\ 1 \end{pmatrix} \right)
    &= T \begin{pmatrix} 2 \\ 1 \end{pmatrix} 
    = \begin{pmatrix} 7 \\ 1 \end{pmatrix}, \\
    T\begin{pmatrix} 1 \\ 0 \end{pmatrix} + T \begin{pmatrix} 1 \\ 1 \end{pmatrix} 
    &= \begin{pmatrix} 4 \\ 0 \end{pmatrix} + \begin{pmatrix} 4 \\ 1 \end{pmatrix} 
    = \begin{pmatrix} 8 \\ 1 \end{pmatrix}.
\end{align*} 

(f) Let $u = f(x), v = g(x) \in P(\mathbb{R})$ and $\alpha \in \mathbb{R}$:

 \begin{align*}
    T(u + \alpha v) &= T(f(x) + \alpha g(x)) = \frac{\mathrm{d}}{\mathrm{d} x}(f(x) + \alpha g(x)) 
    = \frac{\mathrm{d}}{\mathrm{d} x}f(x) + \alpha \frac{\mathrm{d}}{\mathrm{d} x} g(x), \\
    T(u) + \alpha T(v) &= T(f(x)) + \alpha T(g(x)) 
    = \frac{\mathrm{d}}{\mathrm{d} x}f(x) + \alpha \frac{\mathrm{d}}{\mathrm{d} x}g(x),
\end{align*} 

therefore $T$ is a linear transformation.

(g) Let $u = f(x), v = g(x) \in P(\mathbb{R})$ and $\alpha \in \mathbb{R}$:

\begin{align*}
    T(u + \alpha v) &= T(f(x) + \alpha g(x)) = x(f(x) + \alpha g(x)) = xf(x) + \alpha x g(x), \\
    T(u) + \alpha T(v) &= T(f(x)) + \alpha T(g(x)) = xf(x) + \alpha x g(x),
\end{align*} 

therefore $T$ is a linear transformation.

(h) Let $u = (a_1 + i b_1, a_2 + i b_2), v = (a_3 + i b_3, a_4 + i b_4) \in \mathbb{C}^2$ and $\alpha = c + id \in \mathbb{C}$:

 \begin{align*}
    T(u + \alpha v) &= T((a_1 + i b_1, a_2 + i b_2) + (c + id) (a_3 + i b_3, a_4 + i b_4)) \\ 
&= T((a_1 + i b_1 + (c + id)(a_3 + i b_3), a_2 + i b_2 + (c + id)(a_4 + i b_4)) \\ 
&= a_1 + i b_1 + (c + id)(a_3 + i b_3) + a_2 + i b_2 + (c + id)(a_4 + i b_4) \\ 
    T(u) + \alpha T(v) &= T((a_1 + i b_1, a_2 + i b_2)) + (c + id)T((a_3 + i b_3, a_4 + i b_4)) \\ 
&= a_1 + i b_1 + a_2 + i b_2 + (c + id) (a_3 + i b_3 + a_4 + i b_4)
\end{align*} 

This is the same, therefore $T$ is a linear transformation.

(i) This is not a linear transformation. Indeed, Let $u = (1 + 2i, 3+4i)$ and $v = (5+ 6i, 7+8i) \in \mathbb{C}^2)$ and $\alpha = 1 \in \mathbb{C}$:

 \begin{align*}
    T(u + \alpha v) &= T((1 + 2i + 5 + 6i, 3 + 4i + 7 + 8i)) \\ 
&= T((6 + 8i, 10 + 12i)) = (6+8i)(10+12i) = 60 + 80i + 72i - 96 \\ 
&= 152i - 36 \\
    T(u) + \alpha T(v) &= T((1 + 2i, 3+4i)) + T((5+ 6i, 7+8i)) \\
&= (1+2i)(3+4i) + (5+6i)(7+8i) \\
&= (3+6i +4i -8) + (35 + 42i + 40i - 48) \\
&= 92i-18
\end{align*} 

These are not the same, therefore $T$ is not a linear transformation.

(j) This is not a linear transformation. Indeed, let $u = (1 + 2i, 3+4i)$ and $v = (5+ 6i, 7+8i) \in \mathbb{C}^2)$ and $\alpha = 1+i \in \mathbb{C}$:

$\begin{align*}
    T(u + \alpha v) &= T((1 + 2i + (1+i)(5 + 6i), 3 + 4i + (1+i)(7 + 8i))) \\
&= T((13i, 2+19i)) = 2-19i \\ 
    T(u) + \alpha T(v) &= T((1 + 2i, 3+4i)) + (1+i) T((5+ 6i, 7+8i)) \\
&= 3-4i + (1+i)(7-8i) = 18 -5i
\end{align*} 

These are not the same, therefore $T$ is not a linear transformation.

```

```{admonition} Solution to Exercise 6.2
:class: seealso

{prf:ref}`Exercise 6.2<transformations-ex-transformation-matrix>`


The transformation matrix is 

$$ A = \begin{pmatrix} -1 & 3 \\ 1 & -4 \end{pmatrix} $$

Calculating $T (2, 5)$

$$ T 
\begin{pmatrix} 2 \\ 5 \end{pmatrix} = 
\begin{pmatrix} -1 & 3 \\ 1 & -4 \end{pmatrix} 
\begin{pmatrix} 2 \\ 5 \end{pmatrix}
= \begin{pmatrix} 13 \\ -18 \end{pmatrix}. $$
```

```{admonition} Solution to Exercise 6.3
:class: seealso

{prf:ref}`Exercise 6.3<transformations-ex-R2>`


The transformation matrix is 

$$ A = \begin{pmatrix} 1 & -2 \\ 2 & 3 \end{pmatrix}, $$

so the inverse is

$$  A^{-1} = \frac{1}{7}
\begin{pmatrix} 
    3 & 2 \\
    -2 & 1
\end{pmatrix}. $$

Therefore

$$ \mathbf{u} = A^{-1} 
\begin{pmatrix} -1 \\ 5 \end{pmatrix} =  \frac{1}{7}
\begin{pmatrix} 
    3 & 2 \\
    -2 & 1
\end{pmatrix}
\begin{pmatrix} -1 \\ 5 \end{pmatrix} = 
\begin{pmatrix} 1 \\ 1 \end{pmatrix}. $$
```
```{admonition} Solution to Exercise 6.4
:class: seealso

{prf:ref}`Exercise 6.4<transformations-ex-R3>`

The transformation matrix is determined using {prf:ref}`the equation for the transformation matrix<determining-the-transformation-matrix>` which is

$$A = \begin{pmatrix} T(\mathbf{u}_1) & T(\mathbf{u}_2) & \cdots & T(\mathbf{u}_n) \end{pmatrix}
\begin{pmatrix} \mathbf{u}_1 & \mathbf{u}_2 & \cdots & \mathbf{u}_n \end{pmatrix}^{-1}.$$

Using Gauss-Jordan elimination to calculate the inverse of $(\mathbf{u}_1, \mathbf{u}_2, \mathbf{u}_3)^{-1}$ 

 \begin{align*}
    & \left( \begin{array}{rrr|rrr}
       1 & 0 & -1 & 1 & 0 & 0 \\
       -1 & 1 & 1 & 0 & 1 & 0 \\
       0 & 2 & 1 & 0 & 0 & 1
    \end{array} \right)
    \begin{array}{l} \\ R_2 + R_1 \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow \qquad 
    & \left( \begin{array}{rrr|rrr}
       1 & 0 & -1 & 1 & 0 & 0 \\
       0 & 1 & 0 & 1 & 1 & 0 \\
       0 & 2 & 1 & 0 & 0 & 1
    \end{array} \right)
    \begin{array}{l} \\ \\ R_3 - 2 R_2 \end{array} \\ \\ 
    \longrightarrow \qquad  
    & \left( \begin{array}{rrr|rrr}
       1 & 0 & -1 & 1 & 0 & 0 \\
       0 & 1 & 0 & 1 & 1 & 0 \\
       0 & 0 & 1 & -2 & -2 & 1
    \end{array} \right)
    \begin{array}{l} R_1 + R_3 \\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow \qquad
    & \left( \begin{array}{rrr|rrr}
       1 & 0 & 0 & -1 & -2 & 1 \\
       0 & 1 & 0 & 1 & 1 & 0 \\
       0 & 0 & 1 & -2 & -2 & 1
    \end{array} \right)
\end{align*} 

So $(\mathbf{u}_1, \mathbf{u}_2, \mathbf{u}_3)^{-1} = \begin{pmatrix}  -1 & -2 & 1 \\ 1 & 1 & 0 \\ -2 & -2 & 1 \end{pmatrix}$ and

 \begin{align*}
    A &= \begin{pmatrix} 1 & 6 & 2 \\ -2 & 5 & 4 \\ -4 & 10 & 7 \end{pmatrix}
    \begin{pmatrix} 
        -1 & -2 & 1 \\
        1 & 1 & 0 \\
        -2 & -2 & 1
    \end{pmatrix}
    = \begin{pmatrix} 1 & 0 & 3 \\ -1 & 1 & 2 \\ 0 & 4 & 3 \end{pmatrix}.
\end{align*} 

Checking $A$

$$ T \begin{pmatrix} 1 \\ -1 \\ 0 \end{pmatrix} =
\begin{pmatrix} 1 & 0 & 3 \\ -1 & 1 & 2 \\ 0 & 4 & 3 \end{pmatrix}
\begin{pmatrix}1 \\ -1 \\ 0 \end{pmatrix} = 
\begin{pmatrix} 1 \\ -2 \\ - 4 \end{pmatrix} \quad \checkmark $$
```

```{admonition} Solution to Exercise 6.5
:class: seealso

{prf:ref}`Exercise 6.5<transformations-ex-rotation>`


The transformation matrix is

 \begin{align*}
    Rot\left(\pi/6\right) &= \begin{pmatrix} 
        \cos(\pi/6) & -\sin(\pi/6) \\
        \sin(\pi/6) & \cos(\pi/6)
    \end{pmatrix}  \\
    &= \begin{pmatrix}
        \sqrt{3}/2 & -1/2 \\
        1/2 & \sqrt{3}/2
    \end{pmatrix}
\end{align*} 

therefore

\begin{align*}
    Rot\left(\frac{\pi}{6}\right) \begin{pmatrix} 2 \\ 1 \end{pmatrix}
    &= \begin{pmatrix}
        \sqrt{3}/2 & -1/2 \\
        1/2 & \sqrt{3}/2
    \end{pmatrix}
    \begin{pmatrix} 2 \\ 1 \end{pmatrix} \\
    &= \begin{pmatrix} \sqrt{3} - 1/2 \\ 1 + \sqrt{3}/2 \end{pmatrix}
    \approx \begin{pmatrix} 1.2321 \\ 1.8660 \end{pmatrix}
\end{align*} 
```

```{admonition} Solution to Exercise 6.6
:class: seealso

{prf:ref}`Exercise 6.6<transformations-ex-reflection>`


The transformation matrix is

$$ Re\!f \left(\pi/3\right) =
\begin{pmatrix} 
    \cos(2\pi/3) & \sin(2\pi/3) \\
    \sin(2\pi/3) & -\cos(2\pi/3)
\end{pmatrix}
\begin{pmatrix}
    -1/2 & \sqrt{3}/2 \\
    \sqrt{3}/2 & 1/2
\end{pmatrix} $$

therefore

 \begin{align*}
Re\!f \left(\pi/3\right)
\begin{pmatrix} 5 \\ 3 \end{pmatrix} 
&= \begin{pmatrix}
    -1/2 & \sqrt{3}/2 \\
    \sqrt{3}/2 & 1/2
\end{pmatrix} 
\begin{pmatrix} 5 \\ 3 \end{pmatrix} \\
&= 
\begin{pmatrix} 3\sqrt{3}/2 - 5/2 \\ 3/2 + 5\sqrt{3}/2 \end{pmatrix} 
\approx \begin{pmatrix} 0.0981 \\ 5.8301 \end{pmatrix}.
\end{align*} 
```

````{admonition} Solution to Exercise 6.7
:class: seealso

{prf:ref}`Exercise 6.7<transformations-ex-transform-square>`


(a) $\begin{pmatrix} 
    2 & 4 & 4 & 2 \\
    1 & 1 & 3 & 3 \\
    1 & 1 & 1 & 1 
\end{pmatrix} $

(b) Translate by $(-3, -2)$ so that the centre of the square is at the origin:

 \begin{align*} 
    T \begin{pmatrix} -3 \\ -2 \end{pmatrix} = 
    \begin{pmatrix}
        1 & 0 & -3 \\
        0 & 1 & -2 \\
        0 & 0 & 1 
    \end{pmatrix}
\end{align*} 

Rotate by $\pi/3$ clockwise about the origin:

 \begin{align*}
    Rot\left(-\frac{\pi}{3}\right) &=
    \begin{pmatrix}
        \cos(\pi/3) & \sin(\pi/3) & 0 \\
        -\sin(\pi/3) & \cos(\pi/3) & 0 \\
        0 & 0 & 1
    \end{pmatrix} \\
    &= \begin{pmatrix}
        1/2 & \sqrt{3}/2 & 0 \\
        -\sqrt{3}/2 & 1/2 & 0 \\
        0 & 0 & 1
    \end{pmatrix} \\
    &\approx \begin{pmatrix}
        0.5 & 0.8660 & 0 \\
        -0.8660 & 0.5 & 0 \\
        0 & 0 & 1
    \end{pmatrix}
\end{align*} 

Translate by $(3, 2)$ so that the centre of the square is back to $\mathbf{c}$

 \begin{align*}
    T \begin{pmatrix} 3 \\ 2 \end{pmatrix} &= 
    \begin{pmatrix}
        1 & 0 & 3 \\
        0 & 1 & 2 \\
        0 & 0 & 1
    \end{pmatrix}
\end{align*} 

(c) Calculate composite alignment matrix

 \begin{align*}
    A &= T \begin{pmatrix} 3 \\ 2 \end{pmatrix} \cdot Rot\left(-\frac{\pi}{3}\right) \cdot T \begin{pmatrix} -3 \\ -2 \end{pmatrix} \\
    &= \begin{pmatrix}
        1 & 0 & 3 \\
        0 & 1 & 2 \\
        0 & 0 & 1
    \end{pmatrix}
    \begin{pmatrix}
        1/2 & \sqrt{3}/2 & 0 \\
        -\sqrt{3}/2 & 1/2 & 0 \\
        0 & 0 & 1
    \end{pmatrix}
    \begin{pmatrix}
        1 & 0 & -3 \\
        0 & 1 & -2 \\
        0 & 0 & 1 
    \end{pmatrix} \\
    &= \begin{pmatrix}
        1/2 & \sqrt{3}/2 & 3/2 - \sqrt{3} \\
        -\sqrt{3}/2 & 1/2 & 1 + 3\sqrt{3}/2 \\
        0 & 0 & 1 
    \end{pmatrix} \\
    &\approx
    \begin{pmatrix}
        0.5 & 0.8660 & -0.2321 \\
        -0.8660 & 0.5 & 3.5981 \\
        0 & 0 & 1
    \end{pmatrix}.
\end{align*} 

Apply composite transformation matrix

\begin{align*}
    AP &= \begin{pmatrix}
        1/2 & \sqrt{3}/2 & 3/2 - \sqrt{3} \\
        -\sqrt{3}/2 & 1/2 & 1 + 3\sqrt{3}/2 \\
        0 & 0 & 1 
    \end{pmatrix}
    \begin{pmatrix} 
        2 & 4 & 4 & 2 \\
        1 & 1 & 3 & 3 \\
        1 & 1 & 1 & 1 
    \end{pmatrix} \\
    &= \begin{pmatrix}
        5/2 - \sqrt{3}/2 & 7/2 - \sqrt{3}/2 & \sqrt{3}/2 + 7/2 & \sqrt{3}/2 + 5/2 \\
        \sqrt{3}/2 + 3/2 & 3/2 - \sqrt{3}/2 & 5/2 - \sqrt{3}/2 & \sqrt{3}/2 + 5/2 \\
        1 & 1 & 1 & 1
    \end{pmatrix} \\
    &\approx \begin{pmatrix}
        1.634 & 2.634 & 4.366 & 3.366 \\
        2.366 & 0.634 & 1.634 & 3.366 \\
        1 & 1 & 1 & 1 
    \end{pmatrix}
\end{align*} 

```{figure} ../_images/A_transform_square_plot.png
:width: 500
:class: dark:hidden
```

```{figure} ../_images/A_transform_square_plot-w.png
:width: 500
:class: hidden dark:block
```

````

````
