---
numbering: false
---

(co-ordinate-geometry-exercises-solutions-section)=

# Co-ordinate Geometry Exercise Solutions

```{admonition} Solution to Exercise 4.1
:class: seealso

{prf:ref}`Exercise 4.1<geometry-ex-line-plane-equations>`

(a) &emsp; Using the {prf:ref}`vector equation of a line<vector-equation-of-a-line-definition>` we have $\mathbf{r} = \mathbf{a} + t\mathbf{d}_1$

\begin{align*}
    \mathbf{d}_1 &= \mathbf{b} - \mathbf{a} =
    \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix} -
    \begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix} = 
    \begin{pmatrix} -1 \\ 0 \\ 0 \end{pmatrix}, \\
    \therefore \mathbf{r} &= \mathbf{a} + t\mathbf{d}_1 =
    \begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix} + t 
    \begin{pmatrix} -1 \\ 0 \\ 0 \end{pmatrix} = 
    \begin{pmatrix} 2 - t \\ 1 \\ 0 \end{pmatrix}
\end{align*} 

(b) &emsp; Using the {prf:ref}`vector equation of a line<vector-equation-of-a-line-definition>` we have $\mathbf{r} = \mathbf{c} + t\mathbf{d}_2$

\begin{align*}
    \mathbf{d}_2 &= \mathbf{d} - \mathbf{c} =
    \begin{pmatrix} 5 \\ 2 \\ 6 \end{pmatrix} -
    \begin{pmatrix} 3 \\ -1 \\ 4 \end{pmatrix} = 
    \begin{pmatrix} 2 \\ 3 \\ 2 \end{pmatrix}, \\
    \therefore \mathbf{r} &= \mathbf{c} + t\mathbf{d}_2 =
    \begin{pmatrix} 3 \\ -1 \\ 4 \end{pmatrix} + t 
    \begin{pmatrix} 2 \\ 3 \\ 2 \end{pmatrix} = 
    \begin{pmatrix} 3 + 2 t \\ -1 + 3 t \\ 4 + 2 t \end{pmatrix}
\end{align*} 
 
(c) &emsp; Calculate the normal vector to the plane

\begin{align*}
    \mathbf{b} - \mathbf{a} &= \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix} - 
    \begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix} = 
    \begin{pmatrix} -1 \\ 0 \\ 0 \end{pmatrix}, \\
    \mathbf{c} - \mathbf{a} &= \begin{pmatrix} 3 \\ -1 \\ 4 \end{pmatrix} -
    \begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix} =
    \begin{pmatrix} 1 \\ -2 \\ 4 \end{pmatrix}, \\
    \therefore \mathbf{n} &= (\mathbf{b} - \mathbf{a}) \times (\mathbf{c} - \mathbf{a}) = 
    \begin{vmatrix} 
        \mathbf{i} & \mathbf{j} & \mathbf{k} \\
        -1 & 0 & 0 \\
        1 & -2 & 4 
    \end{vmatrix} =
    \begin{pmatrix} 0 \\ 4 \\ 2 \end{pmatrix},
\end{align*} 

Using the {prf:ref}`point normal definition of a plane<point-normal-definition>`

\begin{align*}
    n_x(x - a_x) + n_y(y - a_y) + n_z(z - a_z) &= 0 \\
    0(x - 2) + 4(y - 1) + 2(z - 0) &= 0 \\
    4 y + 2 z - 4 &= 0.
\end{align*} 

(d) &emsp; Calculate the normal vector to the plane

\begin{align*}
    \mathbf{c} - \mathbf{b} &= \begin{pmatrix} 3 \\ -1 \\ 4 \end{pmatrix} - 
    \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix} =
    \begin{pmatrix} 2 \\ -2 \\ 4 \end{pmatrix}, \\
    \mathbf{d} - \mathbf{b} &= \begin{pmatrix} 5 \\ 2 \\ 6 \end{pmatrix} -
    \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix} =
    \begin{pmatrix} 4 \\ 1 \\ 6 \end{pmatrix}, \\
    \mathbf{n} &= (\mathbf{c} - \mathbf{b}) \times (\mathbf{d} - \mathbf{b}) = 
    \begin{vmatrix}
        \mathbf{i} & \mathbf{j} & \mathbf{k} \\
        2 & -2 & 4 \\
        4 & 1 & 6
    \end{vmatrix} =
    \begin{pmatrix} -16 \\ 4 \\ 10 \end{pmatrix},
\end{align*} 

Using the {prf:ref}`point normal definition of a plane<point-normal-definition>`

\begin{align*}
    n_x(x - b_x) + n_y(y - b_y) + n_z(z - b_z) &= 0 \\
    -16(x - 1) + 4(y - 1) + 10(z - 0) &= 0\\
    -16 x + 4 y + 10 z + 12 &= 0.
\end{align*} 
```

```{admonition} Solution to Exercise 4.2
:class: seealso

{prf:ref}`Exercise 4.2<geometry-ex-line-equation-1>`

$$ \mathbf{r} = \begin{pmatrix} 3 \\ 2 \\ 1 \end{pmatrix} + t \begin{pmatrix} 2 \\ 1 \\ 3 \end{pmatrix}  = \begin{pmatrix} 3 + 2 t \\ 2 + t \\ 1 + 3 t \end{pmatrix} $$
```

```{admonition} Solution to Exercise 4.3
:class: seealso

{prf:ref}`Exercise 4.3<geometry-ex-plane-equation-1>`

Using the {prf:ref}`point normal definition of a plane<point-normal-definition>`

\begin{align*}
    \mathbf{n} \cdot \begin{pmatrix} x - x_0 \\ y - y_0 \\ z - z_0 \end{pmatrix} &= 0 \\
    \begin{pmatrix} 2 \\ 1 \\ 3 \end{pmatrix} \cdot
    \begin{pmatrix} x - 3 \\ y - 2 \\ z - 5 \end{pmatrix} \\
    2(x - 3) + (y - 2) + 3(z - 5) &= 0 \\
    2 x + y + 3 z - 23 &= 0
\end{align*} 
```

```{admonition} Solution to Exercise 4.4
:class: seealso

{prf:ref}`Exercise 4.4<geometry-ex-plane-1>`

$\mathbf{n} = (3, -2, 1)$. 

Let $x=0$ then $3(0) - 2 y + 2 = 10$ so $y = -4$ and a point on the plane has co-ordinates $(0, -4, 2)$.

Let $x = 2$ then $3(2) - 2 y + 2 = 10$ so $y = -1$ and a point on the plane has co-ordinates $(2, -1, 2)$.
```

```{admonition} Solution to Exercise 4.5
:class: seealso

{prf:ref}`Exercise 4.5<geometry-ex-line-point-distance>`

(a) &emsp; Equating $\ell_1$ and $\ell_2$ and attempting to solve for $t$

\begin{align*}
    1 + 2t_1 &= 1 + 2t_2 \\
    -t_1 &= 4 \\
    1 + 3t_1 &= 7 - t_2
\end{align*} 

From the second equation $t_1 = -4$ which when substituted into the third equation gives $t_2 = 18$. Substituting these into the first equation gives $-7 = 37$ which is a contradiction so $\ell_1$ and $\ell_2$ do not intersect.

We also need to show that they are not parallel, i.e., there is no value $k$ such that $\mathbf{d}_1 = k \mathbf{d}_2$. The direction vectors for $\ell_1$ and $\ell_2$ are $\mathbf{d}_1 = (2, -1, 3)$ and $\mathbf{d}_2 = (2, 0, -1)$ so

$$ \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} = k \begin{pmatrix} 2 \\ 0 \\ -1 \end{pmatrix} $$

which gives the system

\begin{align*}
    2 &= 2k\\
    -1 &= 0\\
    3 &= -k.
\end{align*} 

The second equation is a contradiction so $\ell_1$ and $\ell_2$ are not parallel, and since they do not intersect then they must be skew.

(b) &emsp; Using the {prf:ref}`shortest distance between a point and a line<point-line-distance-theorem>`

\begin{align*}
    t &= \frac{(\mathbf{p} - \mathbf{p}_1)\cdot \mathbf{d}_1}{\mathbf{d}_1 \cdot \mathbf{d}_1} = \frac{ 
    \left( \begin{pmatrix} 0 \\ -1 \\ 3 \end{pmatrix} -
    \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix} \right) \cdot
    \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix}}{
        \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} \cdot
        \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix}
    } 
    = \frac{5}{14}, \\
    \therefore \mathbf{r} &= \mathbf{p}_1 + t\mathbf{d}_1 = \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix} + \frac{5}{14} 
    \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} = 
    \begin{pmatrix} \frac{12}{7} \\ - \frac{5}{14} \\ \frac{29}{14} \end{pmatrix}, \\
    \overrightarrow{\mathbf{rp}} &= \begin{pmatrix} 0 \\ -1 \\ 3 \end{pmatrix} - 
    \begin{pmatrix} \frac{12}{7} \\ -\frac{5}{14} \\ \frac{29}{14} \end{pmatrix} =
    \begin{pmatrix} -\frac{12}{7} \\ -\frac{9}{14} \\ \frac{13}{14} \end{pmatrix}, \\
    \therefore d &= \|\overrightarrow{\mathbf{rp}}\| = 
    \sqrt{\left(-\frac{12}{7}\right)^2 + \left(-\frac{9}{14}\right)^2 + \left(\frac{13}{14}\right)^2} 
    = \frac{\sqrt{826}}{14}.
\end{align*} 

(c) &emsp; The direction vectors for lines $\ell_1$ and $\ell_2$ are $\mathbf{d}_1 = (2, -1, 3)^\mathsf{T}$ and $\mathbf{d}_2 = (2, -, -1)^\mathsf{T}$ respectively. Calculating a vector perpendicular to both $\mathbf{d}_1$ and $\mathbf{d}_2$

\begin{align*}
    \mathbf{n} &= \mathbf{d}_1 \times \mathbf{d_1} = \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} \times
    \begin{pmatrix} 2 \\ 0 \\ -1 \end{pmatrix} =
    \begin{vmatrix}
        \mathbf{i} & \mathbf{j} & \mathbf{k} \\
        2 & -1 & 3 \\
        2 & 0 & -1 
    \end{vmatrix} = 
    \begin{pmatrix} 1 \\ 8 \\ 2 \end{pmatrix}, \\
\end{align*} 

and normalising gives

\begin{align*}
    \hat{\mathbf{n}} = \frac{\mathbf{n}}{\|\mathbf{n}\|} = \frac{1}{\sqrt{69}} 
    \begin{pmatrix} 1 \\ 8 \\ 2 \end{pmatrix} =
    \begin{pmatrix} \frac{\sqrt{69}}{69} \\ \frac{8\sqrt{69}}{69} \\ \frac{2\sqrt{69}}{69} \end{pmatrix}.
\end{align*} 

Using {prf:ref}`the distance between two lines<line-line-distance-theorem>`

\begin{align*}
    d &= (\mathbf{p}_2 - \mathbf{p}_1) \cdot \hat{\mathbf{n}} \\
    &= \left( \begin{pmatrix} 1 \\ 4 \\ 7 \end{pmatrix} -
    \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix} \right) \cdot
    \begin{pmatrix} \frac{\sqrt{69}}{69} \\ \frac{8\sqrt{69}}{69} \\ \frac{2\sqrt{69}}{69} \end{pmatrix} \\
    &= \begin{pmatrix} 0 \\ 4 \\ 6 \end{pmatrix} \cdot
    \begin{pmatrix} \frac{\sqrt{69}}{69} \\ \frac{8\sqrt{69}}{69} \\ \frac{2\sqrt{69}}{69} \end{pmatrix} \\
    &= \frac{44\sqrt{69}}{69}.
\end{align*} 

```

```{admonition} Solution to Exercise 4.6
:class: seealso

{prf:ref}`Exercise 4.6<geometry-ex-line-plane-intersection>`

First we need to find the position vector of a point, $\mathbf{r}$ say, that lies on the plane. Let $x=0$ and $y=1$ then $z=-1$ so we know that $\mathbf{r} = (0, 1, -1)^\mathsf{T}$ lies on the plane. Using the {prf:ref}`point normal definition of a plane<point-normal-definition>`

\begin{align*}
    \mathbf{n} \cdot \begin{pmatrix} x - x_0 \\ y - y_0 \\ z - z_0 \end{pmatrix} &= 0 \\
    \begin{pmatrix} 6 \\ -1 \\ -4 \end{pmatrix} \cdot
    \begin{pmatrix} 0 - (1 + 2 t) \\ 1 - (2 + t) \\ -1 - (-1 + 4 t) \end{pmatrix} &= 0 \\
    \begin{pmatrix} 6 \\ -1 \\ -4 \end{pmatrix} \cdot
    \begin{pmatrix} - 1 - 2 t \\ -1 - t \\  -4 t \end{pmatrix} &= 0 \\
    -6 - 12 t + 1 + t + 16 t &= 0 \\
    5 t - 5 &= 0 \\
    \therefore t = 1.
\end{align*} 

Alternatively, we can note that if $x=2+3t, y = 2+t$ and $z=-1+4t$, then the equation of the plane can be written in terms of $t$ as:

\begin{align*} 6(1+2t) - (2+t) -4(-1+4t) &= 3 \\  6+12t - 2 - t +4 -16t &= 3 \end{align*}

If we simplify and solve this equation for $t$, we get $-5t = -5$ and so $t=1$.

So the line intersects with the plane at

\begin{align*}
    \mathbf{p} + t \mathbf{d} = 
    \begin{pmatrix} 1 \\ 2 \\ -1 \end{pmatrix} + 
    \begin{pmatrix} 2 \\ 1 \\ 4 \end{pmatrix} =
    \begin{pmatrix} 3 \\ 3 \\ 3 \end{pmatrix}.
\end{align*} 
```

```{admonition} Solution to Exercise 4.7
:class: seealso

{prf:ref}`Exercise 4.7<geometry-ex-point-plane-distance>`

Using the {prf:ref}`geometric definition of a dot product<dot-product-definition>`:

\begin{align*}
    (\mathbf{q} - \mathbf{p})\cdot \mathbf{n} &= \|\mathbf{n}\|\|\mathbf{q} - \mathbf{p}\| \cos(\theta).
\end{align*} 

Since $d$ is the length of the adjacent side of the right-angled triangle then

\begin{align*}
    \cos(\theta) &= \frac{d}{\|\mathbf{q} - \mathbf{p}\|},
\end{align*} 

so

\begin{align*}
    (\mathbf{q} - \mathbf{p}) \cdot \mathbf{n} &= \|\mathbf{n}\| \|\mathbf{q} - \mathbf{p}\| \frac{d}{\|\mathbf{q} - \mathbf{p}\|} \\
    \therefore d &= (\mathbf{q} - \mathbf{p})\cdot \frac{\mathbf{n}}{\|\mathbf{n}\|}.
\end{align*} 

The equation of the plane is $6 x-y-4 z=3$ so letting $x=0$ and $y=1$ then $z = 1$ so we know that $\mathbf{p} = (0, 1, -1)$ lies on the plane. Since $\mathbf{q} = (2, 4, -3)^\mathsf{T}$ and $\mathbf{n} = (6, -1, -4)^\mathsf{T}$ then applying the above formula gives

\begin{align*}
    d &= \left( \begin{pmatrix} 2 \\ 4 \\ -3 \end{pmatrix} -
    \begin{pmatrix} 0 \\ 1 \\ -1 \end{pmatrix} \right) \cdot 
    \begin{pmatrix} 6 \\ -1 \\ -4 \end{pmatrix} / \left\|
    \begin{pmatrix} 6 \\ -1 \\ -4 \end{pmatrix} \right\| \\
    &= \begin{pmatrix} 2 \\ 3 \\ -2 \end{pmatrix} \cdot \frac{1}{\sqrt{53}} 
    \begin{pmatrix} 6 \\ -1 \\ -4 \end{pmatrix} \\
    &= \frac{12 - 3 + 8}{\sqrt{53}} = \frac{17}{\sqrt{53}}
\end{align*} 
```
  