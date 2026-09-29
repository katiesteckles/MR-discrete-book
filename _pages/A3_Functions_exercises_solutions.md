---
numbering: false
---
(vectors-exercises-solutions-section)=

# Vectors Exercise Solutions

```{admonition} Solution to Exercise 3.1
:class: seealso

{prf:ref}`Exercise 3.1<vectors-ex-arithmetic>`

(a) &emsp; $2\mathbf{u} + \mathbf{w} = 2\begin{pmatrix} 2 \\ 3 \end{pmatrix} + \begin{pmatrix} 1 \\ 6 \end{pmatrix} 
= \begin{pmatrix} 4 \\ 6 \end{pmatrix} + \begin{pmatrix} 1 \\ 6 \end{pmatrix} 
= \begin{pmatrix} 5 \\ 12 \end{pmatrix}$

(b) &emsp; $\mathbf{w} - \mathbf{u} = \begin{pmatrix} 1 \\ 6 \end{pmatrix} - \begin{pmatrix} 2 \\ 3 \end{pmatrix} 
= \begin{pmatrix} 1 - 2 \\ 6 - 3 \end{pmatrix} = \begin{pmatrix} -1 \\ 3 \end{pmatrix}$

(c) &emsp; $\hat{\mathbf{u}} = \dfrac{\mathbf{u}}{\|\mathbf{u}\|} = \dfrac{1}{\sqrt{13}} \begin{pmatrix} 2 \\ 3 \end{pmatrix} 
= \begin{pmatrix} \frac{2}{\sqrt{13}} \\ \frac{3}{\sqrt{13}} \end{pmatrix}$

(d) &emsp; $-\hat{\mathbf{v}} = -\dfrac{\mathbf{v}}{\|\mathbf{v}\|} = -\dfrac{1}{\sqrt{13}} \begin{pmatrix} 3 \\ -2 \end{pmatrix} = \begin{pmatrix} -\frac{3}{\sqrt{13}} \\ \frac{2}{\sqrt{13}} \end{pmatrix}$

(e) &emsp; $\dfrac{1}{2}\mathbf{v} = \dfrac{1}{2} \begin{pmatrix} 3 \\ -2 \end{pmatrix} 
= \begin{pmatrix} 3 / 2 \\ -2 / 2 \end{pmatrix}$

(f) &emsp; $\mathbf{v} - \mathbf{u} = \begin{pmatrix} 3 \\ -2 \end{pmatrix} - \begin{pmatrix} 2 \\ 3 \end{pmatrix}= \begin{pmatrix} 1 \\ -5 \end{pmatrix}$

(g) &emsp; $\mathbf{w} - \mathbf{u} = \begin{pmatrix} 1 \\ 6 \end{pmatrix} - \begin{pmatrix} 2 \\ 3 \end{pmatrix} = \begin{pmatrix} -1 \\ 3 \end{pmatrix}$

(h) &emsp; $\mathbf{u} \cdot \mathbf{w} = \begin{pmatrix} 2 \\ 3 \end{pmatrix} \cdot \begin{pmatrix} 1 \\ 6 \end{pmatrix} = 2 \times 1 + 3 \times 6 = 20$

(i) &emsp; Using {prf:ref}`the equation for the geometric dot product<geometric-dot-product-equation>`

\begin{align*}
    (\mathbf{v} - \mathbf{u}) \cdot (\mathbf{w} - \mathbf{u}) &= \|(\mathbf{v} - \mathbf{u})\|\|(\mathbf{w} - \mathbf{u})\| \cos(\theta) \\
    \begin{pmatrix} 1 \\ -5 \end{pmatrix} \cdot \begin{pmatrix} -1 \\ 3 \end{pmatrix} &=
    \left\| \begin{pmatrix} 1 \\ -5 \end{pmatrix} \right\|
    \left\| \begin{pmatrix} -1 \\ 3 \end{pmatrix} \right\| \cos(\theta) \\
    -16 &= \sqrt{26} \sqrt{10} \cos(\theta) \\
    \theta &= \cos^{-1} \left( \frac{-16}{\sqrt{260}} \right) \approx 3.0172
\end{align*} 

(j) &emsp; $\mathbf{u} \cdot \mathbf{v} = \begin{pmatrix} 2 \\ 3 \end{pmatrix} \cdot \begin{pmatrix} 3 \\ -2 \end{pmatrix} = 2 \times 3 + 3 \times (-2) = 0$

(k) &emsp; $\mathbf{v} \times \mathbf{w} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 3 & -2 & 0 \\ 1 & 6 & 0 \end{vmatrix} = 0\mathbf{i} - 0 \mathbf{j} + 20 \mathbf{k} = \begin{pmatrix} 0 \\ 0 \\ 20 \end{pmatrix}$
```

```{admonition} Solution to Exercise 3.2
:class: seealso

{prf:ref}`Exercise 3.2<vectors-ex-linear-combination>`

(a) &emsp; $\mathbf{u} = 2 \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix} + 7 \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix} + \begin{pmatrix} 0 \\ 0 \\ 1 \end{pmatrix} = 2 \mathbf{i} + 7 \mathbf{j} + \mathbf{k}$

(b)

\begin{align*}
    & \left( \begin{array}{ccc|c}
    1 & 0 & 1 & 2 \\
    -1 & 2 & 0 & 7 \\
    0 & 0 & -1 & 1
    \end{array} \right)
    \begin{array}{l} \\ R_2 + R_1 \\ \phantom{x} \end{array} &
    \longrightarrow &
    \left( \begin{array}{ccc|c}
        1 & 0 & 1 & 2 \\
        0 & 2 & 1 & 9 \\
        0 & 0 & -1 & 1
    \end{array} \right)
    \begin{array}{l} \\ \frac{1}{2} R_2 \\ -R_3 \phantom{x} \end{array} \\ \\
    \longrightarrow &
    \left( \begin{array}{ccc|c}
        1 & 0 & 1 & 2 \\
        0 & 1 & 1/2 & 9/2 \\
        0 & 0 & 1 & -1
    \end{array} \right)
    \begin{array}{l} R_1 - R_3 \\ R_2 - \frac{1}{2} R_3 \\ \phantom{x} \end{array} &
    \longrightarrow &
    \left( \begin{array}{ccc|c}
        1 & 0 & 0 & 3 \\
        0 & 1 & 0 & 5 \\
        0 & 0 & 1 & -1
    \end{array} \right)
    \begin{array}{l} R_1 - R_3 \\ R_2 - \frac{1}{2} R_3 \\ \phantom{x} \end{array} \\ \\
\end{align*} 

 Therefore $\mathbf{u} = 3 \mathbf{f}_1 + 5 \mathbf{f}_2 - \mathbf{f}_3$.
```

```{admonition} Solution to Exercise 3.3
:class: seealso

{prf:ref}`Exercise 3.3<vectors-ex-perpendicular>`

(a) &emsp; If $\mathbf{u}$ and $\mathbf{v}$ are perpendicular then $\mathbf{u} \cdot \mathbf{v} = 0$.

\begin{align*}
    \mathbf{u} \cdot \mathbf{v} &= 0 \\
    \begin{pmatrix} 1 \\ k \\ -2 \end{pmatrix} \cdot
    \begin{pmatrix} 2 \\ -5 \\ 4 \end{pmatrix} &= 0 \\
    2 - 5 k - 8 &= 0 \\
    -5k &= 6 \\
    \therefore k &= -\frac{6}{5}.
\end{align*} 
        
(b) &emsp; 

\begin{align*}
    \mathbf{u} \cdot \mathbf{v} &= 0 \\
    \begin{pmatrix} 1 \\ 0 \\ k + 2 \\ -1 \\ 2 \end{pmatrix} \cdot 
    \begin{pmatrix} 1 \\ k \\ -2 \\ 1 \\ 2 \end{pmatrix} &= 0 \\
    1 - 2k - 2 - 1 + 2 &= 0 \\
    -2k &= 0 \\
    \therefore k &= 0.
\end{align*} 
```

```{admonition} Solution to Exercise 3.4
:class: seealso

{prf:ref}`Exercise 3.4<vectors-ex-angle>`

\begin{align*}
    \mathbf{u} \cdot \mathbf{v} &= \begin{pmatrix} 1 \\ 2 \\ 3 \end{pmatrix} \cdot
    \begin{pmatrix} -1 \\ 2 \\ -1 \end{pmatrix} = -1 + 4 - 3 = 0, \\
    \mathbf{u} \cdot \mathbf{w} &= \begin{pmatrix} 1 \\ 2 \\ 3 \end{pmatrix} \cdot
    \begin{pmatrix} 2 \\ -3 \\ 1 \end{pmatrix} = 2 - 6 + 3 = -1, \\
    \mathbf{v} \cdot \mathbf{w} &= \begin{pmatrix} -1 \\ 2 \\ -1 \end{pmatrix} \cdot
    \begin{pmatrix} 2 \\ -3 \\ 1 \end{pmatrix} = -2 -6 -1 =  -9.
\end{align*} 

Therefore $\mathbf{u} \perp \mathbf{v}$. The angle between $\mathbf{u}$ and $\mathbf{w}$ is

\begin{align*}
    \theta &= \cos^{-1} \left( \frac{\mathbf{u} \cdot \mathbf{w}}{\|\mathbf{u} \|\|\mathbf{w}\|} \right) \\
    &= \cos^{-1} \left( \frac{-1}{\sqrt{14}\sqrt{14}}\right) \\
    &= \cos^{-1}\left(\frac{-1}{14}\right) \approx 1.6423,
\end{align*} 

and the angle between $\mathbf{v}$ and $\mathbf{w}$ is

\begin{align*}
    \theta &= \cos^{-1} \left( \frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{v} \|\|\mathbf{w}\|} \right) \\
    &= \cos^{-1} \left( \frac{-9}{\sqrt{6}\sqrt{14}} \right) \approx 2.9515.
\end{align*} 
```
