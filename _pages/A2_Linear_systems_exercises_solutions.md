---
numbering: false
---

(systems-exercises-solutions)=



# Systems of Linear Equations Exercise Solutions

```{admonition} Solution to Exercise 2.1
:class: seealso

{prf:ref}`Exercise 2.1<systems-ex-inverse-sol>`

(a)

$$ \begin{align*}
    \det\left(\begin{matrix}-4 & 2\\3 & 4\end{matrix}\right) &= -22, \\ 
    \operatorname{adj}\left(\begin{matrix}-4 & 2\\3 & 4\end{matrix}\right) &= \left(\begin{matrix}4 & -2\\-3 & -4\end{matrix}\right), \\ 
    \therefore A^{-1} &= - \frac{1}{22}\left(\begin{matrix}4 & -2\\-3 & -4\end{matrix}\right) = \left(\begin{matrix}- \frac{2}{11} & \frac{1}{11}\\\frac{3}{22} & \frac{2}{11}\end{matrix}\right) 
\end{align*} $$ 

therefore 

$$\begin{align*}
    \mathbf{x} &= \left(\begin{matrix}- \frac{2}{11} & \frac{1}{11}\\\frac{3}{22} & \frac{2}{11}\end{matrix}\right)
    \left(\begin{matrix}-22\\11\end{matrix}\right) = 
    \left(\begin{matrix}5\\-1\end{matrix}\right)
\end{align*} $$

so the solution is $x_1 = 5$ and $x_2 = -1$.

(b)

$$ \begin{align*}
    \det\left(\begin{matrix}-4 & 2\\-1 & -3\end{matrix}\right) &= 14, \\ 
    \operatorname{adj}\left(\begin{matrix}-4 & 2\\-1 & -3\end{matrix}\right) &= \left(\begin{matrix}-3 & -2\\1 & -4\end{matrix}\right), \\ 
    \therefore A^{-1} &= \frac{1}{14}\left(\begin{matrix}-3 & -2\\1 & -4\end{matrix}\right) = \left(\begin{matrix}- \frac{3}{14} & - \frac{1}{7}\\\frac{1}{14} & - \frac{2}{7}\end{matrix}\right) 
\end{align*} $$ 

therefore 

$$\begin{align*}
    \mathbf{x} &= \left(\begin{matrix}- \frac{3}{14} & - \frac{1}{7}\\\frac{1}{14} & - \frac{2}{7}\end{matrix}\right)
    \left(\begin{matrix}6\\-2\end{matrix}\right) = 
    \left(\begin{matrix}-1\\1\end{matrix}\right)
\end{align*} $$

so the solution is $x_1 = -1$ and $x_2 = 1$.

(c)

$$ \begin{align*}
    \det\left(\begin{matrix}-4 & -4 & -2\\3 & 0 & 4\\1 & 0 & 0\end{matrix}\right) &= -16, \\ 
    \operatorname{adj}\left(\begin{matrix}-4 & -4 & -2\\3 & 0 & 4\\1 & 0 & 0\end{matrix}\right) &= \left(\begin{matrix}0 & 0 & -16\\4 & 2 & 10\\0 & -4 & 12\end{matrix}\right), \\ 
    \therefore A^{-1} &= - \frac{1}{16}\left(\begin{matrix}0 & 0 & -16\\4 & 2 & 10\\0 & -4 & 12\end{matrix}\right) = \left(\begin{matrix}0 & 0 & 1\\- \frac{1}{4} & - \frac{1}{8} & - \frac{5}{8}\\0 & \frac{1}{4} & - \frac{3}{4}\end{matrix}\right) 
\end{align*} $$ 

therefore 

$$\begin{align*}
    \mathbf{x} &= \left(\begin{matrix}0 & 0 & 1\\- \frac{1}{4} & - \frac{1}{8} & - \frac{5}{8}\\0 & \frac{1}{4} & - \frac{3}{4}\end{matrix}\right)
    \left(\begin{matrix}16\\-8\\0\end{matrix}\right) = 
    \left(\begin{matrix}0\\-3\\-2\end{matrix}\right)
\end{align*} $$

so the solution is $x_1 = 0$, $x_2 = -3$ and $x_3 = -2$.

(d)

$$ \begin{align*}
    \det\left(\begin{matrix}4 & 0 & -4\\4 & -1 & 1\\3 & 1 & 2\end{matrix}\right) &= -40, \\ 
    \operatorname{adj}\left(\begin{matrix}4 & 0 & -4\\4 & -1 & 1\\3 & 1 & 2\end{matrix}\right) &= \left(\begin{matrix}-3 & -4 & -4\\-5 & 20 & -20\\7 & -4 & -4\end{matrix}\right), \\ 
    \therefore A^{-1} &= - \frac{1}{40}\left(\begin{matrix}-3 & -4 & -4\\-5 & 20 & -20\\7 & -4 & -4\end{matrix}\right) = \left(\begin{matrix}\frac{3}{40} & \frac{1}{10} & \frac{1}{10}\\\frac{1}{8} & - \frac{1}{2} & \frac{1}{2}\\- \frac{7}{40} & \frac{1}{10} & \frac{1}{10}\end{matrix}\right) 
\end{align*} $$ 

therefore 

$$\begin{align*}
    \mathbf{x} &= \left(\begin{matrix}\frac{3}{40} & \frac{1}{10} & \frac{1}{10}\\\frac{1}{8} & - \frac{1}{2} & \frac{1}{2}\\- \frac{7}{40} & \frac{1}{10} & \frac{1}{10}\end{matrix}\right)
    \left(\begin{matrix}8\\-4\\-12\end{matrix}\right) = 
    \left(\begin{matrix}-1\\-3\\-3\end{matrix}\right)
\end{align*} $$

so the solution is $x_1 = -1$, $x_2 = -3$ and $x_3 = -3$.

```

```{admonition} Solution to Exercise 2.2
:class: seealso

{prf:ref}`Exercise 2.2<systems-ex-cramer>`

(a) 

$$ \begin{align*} 
    x_{1} &= \frac{\det\left(\begin{matrix}-20 & 4\\-5 & 1\end{matrix}\right)}{\det\left(\begin{matrix}1 & 4\\-4 & 1\end{matrix}\right)} 
    = \frac{0}{17} = 0, \\ 
    x_{2} &= \frac{\det\left(\begin{matrix}1 & -20\\-4 & -5\end{matrix}\right)}{\det\left(\begin{matrix}1 & 4\\-4 & 1\end{matrix}\right)} 
    = \frac{-85}{17} = -5. 
\end{align*} $$ 

(b) 

$$ \begin{align*} 
    x_{1} &= \frac{\det\left(\begin{matrix}4 & 1\\12 & 4\end{matrix}\right)}{\det\left(\begin{matrix}1 & 1\\0 & 4\end{matrix}\right)} 
    = \frac{4}{4} = 1, \\ 
    x_{2} &= \frac{\det\left(\begin{matrix}1 & 4\\0 & 12\end{matrix}\right)}{\det\left(\begin{matrix}1 & 1\\0 & 4\end{matrix}\right)} 
    = \frac{12}{4} = 3. 
\end{align*} $$ 

(c) 

$$ \begin{align*} 
    x_{1} &= \frac{\det\left(\begin{matrix}21 & -4 & -4\\8 & -1 & -1\\-14 & -1 & 3\end{matrix}\right)}{\det\left(\begin{matrix}3 & -4 & -4\\-2 & -1 & -1\\4 & -1 & 3\end{matrix}\right)} 
    = \frac{44}{-44} = -1, \\ 
    x_{2} &= \frac{\det\left(\begin{matrix}3 & 21 & -4\\-2 & 8 & -1\\4 & -14 & 3\end{matrix}\right)}{\det\left(\begin{matrix}3 & -4 & -4\\-2 & -1 & -1\\4 & -1 & 3\end{matrix}\right)} 
    = \frac{88}{-44} = -2, \\ 
    x_{3} &= \frac{\det\left(\begin{matrix}3 & -4 & 21\\-2 & -1 & 8\\4 & -1 & -14\end{matrix}\right)}{\det\left(\begin{matrix}3 & -4 & -4\\-2 & -1 & -1\\4 & -1 & 3\end{matrix}\right)} 
    = \frac{176}{-44} = -4. 
\end{align*} $$ 

(d) 

$$ \begin{align*} 
    x_{1} &= \frac{\det\left(\begin{matrix}5 & 4 & 1\\-1 & 1 & 1\\-14 & -4 & 2\end{matrix}\right)}{\det\left(\begin{matrix}4 & 4 & 1\\-2 & 1 & 1\\-5 & -4 & 2\end{matrix}\right)} 
    = \frac{0}{33} = 0, \\ 
    x_{2} &= \frac{\det\left(\begin{matrix}4 & 5 & 1\\-2 & -1 & 1\\-5 & -14 & 2\end{matrix}\right)}{\det\left(\begin{matrix}4 & 4 & 1\\-2 & 1 & 1\\-5 & -4 & 2\end{matrix}\right)} 
    = \frac{66}{33} = 2, \\ 
    x_{3} &= \frac{\det\left(\begin{matrix}4 & 4 & 5\\-2 & 1 & -1\\-5 & -4 & -14\end{matrix}\right)}{\det\left(\begin{matrix}4 & 4 & 1\\-2 & 1 & 1\\-5 & -4 & 2\end{matrix}\right)} 
    = \frac{-99}{33} = -3. 
\end{align*} $$ 

```


```{admonition} Solution to Exercise 2.3
:class: seealso

{prf:ref}`Exercise 2.3<systems-ex-gelim>`

(a) 

$$ \begin{align*} 
    & \left( \begin{array}{cc|c} 
         -1 & 3 & -2 \\ 
         -2 & 1 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 2 R_{1} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         -1 & 3 & -2 \\ 
         0 & -5 & 5 \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{2} &=  - \frac{1}{5} \left( 5 \right) = -1, \\ 
    x_{1} &=  - \left( -2 - 3 \left( -1 \right) \right) = -1. 
\end{align*} $$ 

(b) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         3 & 1 & 2 & 11 \\ 
         4 & 0 & -4 & -4 \\ 
         4 & -2 & 1 & 13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - \frac{4}{3} R_{1} \\ R_{3} - \frac{4}{3} R_{1} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & 1 & 2 & 11 \\ 
         0 & - \frac{4}{3} & - \frac{20}{3} & - \frac{56}{3} \\ 
         0 & - \frac{10}{3} & - \frac{5}{3} & - \frac{5}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{5}{2} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & 1 & 2 & 11 \\ 
         0 & - \frac{4}{3} & - \frac{20}{3} & - \frac{56}{3} \\ 
         0 & 0 & 15 & 45 \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{3} &=  \frac{1}{15} \left( 45 \right) = 3, \\ 
    x_{2} &=  - \frac{1}{\frac{4}{3}} \left( - \frac{56}{3} - \left( - \frac{20}{3} \right) \left( 3 \right) \right) = -1, \\ 
    x_{1} &=  \frac{1}{3} \left( 11 - 1 \left( -1 \right) - 2 \left( 3 \right) \right) = 2. 
\end{align*} $$ 

(c) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -17 \\ 
         2 & -2 & -3 & -14 \\ 
         3 & -1 & 4 & -13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} + 2 R_{1}\\ R_{3} + 3 R_{1}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -17 \\ 
         0 & -12 & -7 & -48 \\ 
         0 & -16 & -2 & -64 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{4}{3} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -17 \\ 
         0 & -12 & -7 & -48 \\ 
         0 & 0 & \frac{22}{3} & 0 \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{3} &=  \frac{1}{\frac{22}{3}} \left( 0 \right) = 0, \\ 
    x_{2} &=  - \frac{1}{12} \left( -48 - \left( -7 \right) \left( 0 \right) \right) = 4, \\ 
    x_{1} &=  - \left( -17 - \left( -5 \right) \left( 4 \right) - \left( -2 \right) \left( 0 \right) \right) = -3. 
\end{align*} $$ 

(d) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -26 \\ 
         2 & -2 & -3 & -19 \\ 
         3 & -1 & -4 & -20 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} + 2 R_{1}\\ R_{3} + 3 R_{1}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -26 \\ 
         0 & -12 & -7 & -71 \\ 
         0 & -16 & -10 & -98 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{4}{3} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -26 \\ 
         0 & -12 & -7 & -71 \\ 
         0 & 0 & - \frac{2}{3} & - \frac{10}{3} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{3} &=  - \frac{1}{\frac{2}{3}} \left( - \frac{10}{3} \right) = 5, \\ 
    x_{2} &=  - \frac{1}{12} \left( -71 - \left( -7 \right) \left( 5 \right) \right) = 3, \\ 
    x_{1} &=  - \left( -26 - \left( -5 \right) \left( 3 \right) - \left( -2 \right) \left( 5 \right) \right) = 1. 
\end{align*} $$ 

(e) 

$$ \begin{align*} 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         2 & 3 & 3 & -3 & 11 \\ 
         -2 & 2 & -5 & -4 & -21 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{2}{3} R_{1} \\ R_{4} + \frac{2}{3} R_{1}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & - \frac{4}{3} & - \frac{23}{3} & - \frac{14}{3} & - \frac{7}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} + \frac{19}{12} R_{2}\\ R_{4} - \frac{1}{3} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         0 & 0 & \frac{125}{12} & - \frac{26}{3} & \frac{229}{4} \\ 
         0 & 0 & - \frac{26}{3} & - \frac{10}{3} & -16 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \phantom{x} \\ R_{4} + \frac{104}{125} R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         0 & 0 & \frac{125}{12} & - \frac{26}{3} & \frac{229}{4} \\ 
         0 & 0 & 0 & - \frac{1318}{125} & \frac{3954}{125} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{4} &=  - \frac{1}{\frac{1318}{125}} \left( \frac{3954}{125} \right) = -3, \\ 
    x_{3} &=  \frac{1}{\frac{125}{12}} \left( \frac{229}{4} - \left( - \frac{26}{3} \right) \left( -3 \right) \right) = 3, \\ 
    x_{2} &=  - \frac{1}{4} \left( 41 - 3 \left( 3 \right) - \left( -4 \right) \left( -3 \right) \right) = -5, \\ 
    x_{1} &=  \frac{1}{3} \left( 28 - \left( -5 \right) \left( -5 \right) - \left( -4 \right) \left( 3 \right) - \left( -1 \right) \left( -3 \right) \right) = 4. 
\end{align*} $$ 

(f) 

$$ \begin{align*} 
    & \left( \begin{array}{cccc|c} 
         2 & -3 & -3 & 4 & -1 \\ 
         4 & -5 & 1 & -5 & 42 \\ 
         3 & 3 & -1 & -5 & 20 \\ 
         1 & 0 & 1 & 3 & -4 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 2 R_{1} \\ R_{3} - \frac{3}{2} R_{1} \\ R_{4} - \frac{1}{2} R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         2 & -3 & -3 & 4 & -1 \\ 
         0 & 1 & 7 & -13 & 44 \\ 
         0 & \frac{15}{2} & \frac{7}{2} & -11 & \frac{43}{2} \\ 
         0 & \frac{3}{2} & \frac{5}{2} & 1 & - \frac{7}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{15}{2} R_{2} \\ R_{4} - \frac{3}{2} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         2 & -3 & -3 & 4 & -1 \\ 
         0 & 1 & 7 & -13 & 44 \\ 
         0 & 0 & -49 & \frac{173}{2} & - \frac{617}{2} \\ 
         0 & 0 & -8 & \frac{41}{2} & - \frac{139}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \phantom{x} \\ R_{4} - \frac{8}{49} R_{3} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         2 & -3 & -3 & 4 & -1 \\ 
         0 & 1 & 7 & -13 & 44 \\ 
         0 & 0 & -49 & \frac{173}{2} & - \frac{617}{2} \\ 
         0 & 0 & 0 & \frac{625}{98} & - \frac{1875}{98} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{4} &=  \frac{1}{\frac{625}{98}} \left( - \frac{1875}{98} \right) = -3, \\ 
    x_{3} &=  - \frac{1}{49} \left( - \frac{617}{2} - \frac{173}{2} \left( -3 \right) \right) = 1, \\ 
    x_{2} &= 44 - 7 \left( 1 \right) - \left( -13 \right) \left( -3 \right) = -2, \\ 
    x_{1} &=  \frac{1}{2} \left( -1 - \left( -3 \right) \left( -2 \right) - \left( -3 \right) \left( 1 \right) - 4 \left( -3 \right) \right) = 4. 
\end{align*} $$ 

```

```{admonition} Solution to Exercise 2.4
:class: seealso

{prf:ref}`Exercise 2.4<systems-ex-gelimpp>`

(a) 

$$ \begin{align*} 
    & \left( \begin{array}{cc|c} 
         -1 & 3 & -2 \\ 
         -2 & 1 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{1} \leftrightarrow R_{2} \\ \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         -2 & 1 & 1 \\ 
         -1 & 3 & -2 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - \frac{1}{2} R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         -2 & 1 & 1 \\ 
         0 & \frac{5}{2} & - \frac{5}{2} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{2} &=  \frac{1}{\frac{5}{2}} \left( - \frac{5}{2} \right) = -1, \\ 
    x_{1} &=  - \frac{1}{2} \left( 1 - 1 \left( -1 \right) \right) = -1. 
\end{align*} $$ 

(b) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         3 & 1 & 2 & 11 \\ 
         4 & 0 & -4 & -4 \\ 
         4 & -2 & 1 & 13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{1} \leftrightarrow R_{2} \\ \\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         4 & 0 & -4 & -4 \\ 
         3 & 1 & 2 & 11 \\ 
         4 & -2 & 1 & 13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - \frac{3}{4} R_{1} \\ R_{3} - R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         4 & 0 & -4 & -4 \\ 
         0 & 1 & 5 & 14 \\ 
         0 & -2 & 5 & 17 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{2} \leftrightarrow R_{3} \\ \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         4 & 0 & -4 & -4 \\ 
         0 & -2 & 5 & 17 \\ 
         0 & 1 & 5 & 14 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} + \frac{1}{2} R_{2}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         4 & 0 & -4 & -4 \\ 
         0 & -2 & 5 & 17 \\ 
         0 & 0 & \frac{15}{2} & \frac{45}{2} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{3} &=  \frac{1}{\frac{15}{2}} \left( \frac{45}{2} \right) = 3, \\ 
    x_{2} &=  - \frac{1}{2} \left( 17 - 5 \left( 3 \right) \right) = -1, \\ 
    x_{1} &=  \frac{1}{4} \left( -4 - 0 \left( -1 \right) - \left( -4 \right) \left( 3 \right) \right) = 2. 
\end{align*} $$ 

(c) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -17 \\ 
         2 & -2 & -3 & -14 \\ 
         3 & -1 & 4 & -13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{1} \leftrightarrow R_{3} \\ \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & 4 & -13 \\ 
         2 & -2 & -3 & -14 \\ 
         -1 & -5 & -2 & -17 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - \frac{2}{3} R_{1} \\ R_{3} + \frac{1}{3} R_{1}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & 4 & -13 \\ 
         0 & - \frac{4}{3} & - \frac{17}{3} & - \frac{16}{3} \\ 
         0 & - \frac{16}{3} & - \frac{2}{3} & - \frac{64}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{2} \leftrightarrow R_{3} \\ \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & 4 & -13 \\ 
         0 & - \frac{16}{3} & - \frac{2}{3} & - \frac{64}{3} \\ 
         0 & - \frac{4}{3} & - \frac{17}{3} & - \frac{16}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{1}{4} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & 4 & -13 \\ 
         0 & - \frac{16}{3} & - \frac{2}{3} & - \frac{64}{3} \\ 
         0 & 0 & - \frac{11}{2} & 0 \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{3} &=  - \frac{1}{\frac{11}{2}} \left( 0 \right) = 0, \\ 
    x_{2} &=  - \frac{1}{\frac{16}{3}} \left( - \frac{64}{3} - \left( - \frac{2}{3} \right) \left( 0 \right) \right) = 4, \\ 
    x_{1} &=  \frac{1}{3} \left( -13 - \left( -1 \right) \left( 4 \right) - 4 \left( 0 \right) \right) = -3. 
\end{align*} $$ 

(d) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -26 \\ 
         2 & -2 & -3 & -19 \\ 
         3 & -1 & -4 & -20 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{1} \leftrightarrow R_{3} \\ \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & -4 & -20 \\ 
         2 & -2 & -3 & -19 \\ 
         -1 & -5 & -2 & -26 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - \frac{2}{3} R_{1} \\ R_{3} + \frac{1}{3} R_{1}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & -4 & -20 \\ 
         0 & - \frac{4}{3} & - \frac{1}{3} & - \frac{17}{3} \\ 
         0 & - \frac{16}{3} & - \frac{10}{3} & - \frac{98}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{2} \leftrightarrow R_{3} \\ \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & -4 & -20 \\ 
         0 & - \frac{16}{3} & - \frac{10}{3} & - \frac{98}{3} \\ 
         0 & - \frac{4}{3} & - \frac{1}{3} & - \frac{17}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{1}{4} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         3 & -1 & -4 & -20 \\ 
         0 & - \frac{16}{3} & - \frac{10}{3} & - \frac{98}{3} \\ 
         0 & 0 & \frac{1}{2} & \frac{5}{2} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{3} &=  \frac{1}{\frac{1}{2}} \left( \frac{5}{2} \right) = 5, \\ 
    x_{2} &=  - \frac{1}{\frac{16}{3}} \left( - \frac{98}{3} - \left( - \frac{10}{3} \right) \left( 5 \right) \right) = 3, \\ 
    x_{1} &=  \frac{1}{3} \left( -20 - \left( -1 \right) \left( 3 \right) - \left( -4 \right) \left( 5 \right) \right) = 1. 
\end{align*} $$ 

(e) 

$$ \begin{align*} 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         2 & 3 & 3 & -3 & 11 \\ 
         -2 & 2 & -5 & -4 & -21 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{2}{3} R_{1} \\ R_{4} + \frac{2}{3} R_{1}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & - \frac{4}{3} & - \frac{23}{3} & - \frac{14}{3} & - \frac{7}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{2} \leftrightarrow R_{3} \\ \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         0 & - \frac{4}{3} & - \frac{23}{3} & - \frac{14}{3} & - \frac{7}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} + \frac{12}{19} R_{2}\\ R_{4} + \frac{4}{19} R_{2}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & 0 & \frac{125}{19} & - \frac{104}{19} & \frac{687}{19} \\ 
         0 & 0 & - \frac{123}{19} & - \frac{98}{19} & - \frac{75}{19} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \phantom{x} \\ R_{4} + \frac{123}{125} R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & 0 & \frac{125}{19} & - \frac{104}{19} & \frac{687}{19} \\ 
         0 & 0 & 0 & - \frac{1318}{125} & \frac{3954}{125} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{4} &=  - \frac{1}{\frac{1318}{125}} \left( \frac{3954}{125} \right) = -3, \\ 
    x_{3} &=  \frac{1}{\frac{125}{19}} \left( \frac{687}{19} - \left( - \frac{104}{19} \right) \left( -3 \right) \right) = 3, \\ 
    x_{2} &=  \frac{1}{\frac{19}{3}} \left( - \frac{23}{3} - \frac{17}{3} \left( 3 \right) - \left( - \frac{7}{3} \right) \left( -3 \right) \right) = -5, \\ 
    x_{1} &=  \frac{1}{3} \left( 28 - \left( -5 \right) \left( -5 \right) - \left( -4 \right) \left( 3 \right) - \left( -1 \right) \left( -3 \right) \right) = 4. 
\end{align*} $$ 

(f) 

$$ \begin{align*} 
    & \left( \begin{array}{cccc|c} 
         2 & -3 & -3 & 4 & -1 \\ 
         4 & -5 & 1 & -5 & 42 \\ 
         3 & 3 & -1 & -5 & 20 \\ 
         1 & 0 & 1 & 3 & -4 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{1} \leftrightarrow R_{2} \\ \\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         4 & -5 & 1 & -5 & 42 \\ 
         2 & -3 & -3 & 4 & -1 \\ 
         3 & 3 & -1 & -5 & 20 \\ 
         1 & 0 & 1 & 3 & -4 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - \frac{1}{2} R_{1} \\ R_{3} - \frac{3}{4} R_{1} \\ R_{4} - \frac{1}{4} R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         4 & -5 & 1 & -5 & 42 \\ 
         0 & - \frac{1}{2} & - \frac{7}{2} & \frac{13}{2} & -22 \\ 
         0 & \frac{27}{4} & - \frac{7}{4} & - \frac{5}{4} & - \frac{23}{2} \\ 
         0 & \frac{5}{4} & \frac{3}{4} & \frac{17}{4} & - \frac{29}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{2} \leftrightarrow R_{3} \\ \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         4 & -5 & 1 & -5 & 42 \\ 
         0 & \frac{27}{4} & - \frac{7}{4} & - \frac{5}{4} & - \frac{23}{2} \\ 
         0 & - \frac{1}{2} & - \frac{7}{2} & \frac{13}{2} & -22 \\ 
         0 & \frac{5}{4} & \frac{3}{4} & \frac{17}{4} & - \frac{29}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} + \frac{2}{27} R_{2}\\ R_{4} - \frac{5}{27} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         4 & -5 & 1 & -5 & 42 \\ 
         0 & \frac{27}{4} & - \frac{7}{4} & - \frac{5}{4} & - \frac{23}{2} \\ 
         0 & 0 & - \frac{98}{27} & \frac{173}{27} & - \frac{617}{27} \\ 
         0 & 0 & \frac{29}{27} & \frac{121}{27} & - \frac{334}{27} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \phantom{x} \\ R_{4} + \frac{29}{98} R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         4 & -5 & 1 & -5 & 42 \\ 
         0 & \frac{27}{4} & - \frac{7}{4} & - \frac{5}{4} & - \frac{23}{2} \\ 
         0 & 0 & - \frac{98}{27} & \frac{173}{27} & - \frac{617}{27} \\ 
         0 & 0 & 0 & \frac{625}{98} & - \frac{1875}{98} \\ 
    \end{array} \right) 
\end{align*} $$ 

Solving by back substitution gives

$$ \begin{align*} 
    x_{4} &=  \frac{1}{\frac{625}{98}} \left( - \frac{1875}{98} \right) = -3, \\ 
    x_{3} &=  - \frac{1}{\frac{98}{27}} \left( - \frac{617}{27} - \frac{173}{27} \left( -3 \right) \right) = 1, \\ 
    x_{2} &=  \frac{1}{\frac{27}{4}} \left( - \frac{23}{2} - \left( - \frac{7}{4} \right) \left( 1 \right) - \left( - \frac{5}{4} \right) \left( -3 \right) \right) = -2, \\ 
    x_{1} &=  \frac{1}{4} \left( 42 - \left( -5 \right) \left( -2 \right) - 1 \left( 1 \right) - \left( -5 \right) \left( -3 \right) \right) = 4. 
\end{align*} $$ 

```

```{admonition} Solution to Exercise 2.5
:class: seealso

{prf:ref}`Exercise 2.5<systems-ex-gjelim>`

(a) 

$$ \begin{align*} 
    & \left( \begin{array}{cc|c} 
         -1 & 3 & -2 \\ 
         -2 & 1 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} -1 R_{1}\\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         1 & -3 & 2 \\ 
         -2 & 1 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} + 2 R_{1}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         1 & -3 & 2 \\ 
         0 & -5 & 5 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{1}{5} R_{2}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         1 & -3 & 2 \\ 
         0 & 1 & -1 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + 3 R_{2}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|c} 
         1 & 0 & -1 \\ 
         0 & 1 & -1 \\ 
    \end{array} \right) 
\end{align*} $$ 

So the solution is $x_{1} = -1$ and $x_{2} = -1$.

(b) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         3 & 1 & 2 & 11 \\ 
         4 & 0 & -4 & -4 \\ 
         4 & -2 & 1 & 13 \\ 
    \end{array} \right) 
    \begin{array}{l} \frac{1}{3} R_{1}\\ \phantom{x} \\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & \frac{1}{3} & \frac{2}{3} & \frac{11}{3} \\ 
         4 & 0 & -4 & -4 \\ 
         4 & -2 & 1 & 13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 4 R_{1} \\ R_{3} - 4 R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & \frac{1}{3} & \frac{2}{3} & \frac{11}{3} \\ 
         0 & - \frac{4}{3} & - \frac{20}{3} & - \frac{56}{3} \\ 
         0 & - \frac{10}{3} & - \frac{5}{3} & - \frac{5}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{3}{4} R_{2}\\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & \frac{1}{3} & \frac{2}{3} & \frac{11}{3} \\ 
         0 & 1 & 5 & 14 \\ 
         0 & - \frac{10}{3} & - \frac{5}{3} & - \frac{5}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} - \frac{1}{3} R_{2} \\ \phantom{x} \\ R_{3} + \frac{10}{3} R_{2}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & -1 & -1 \\ 
         0 & 1 & 5 & 14 \\ 
         0 & 0 & 15 & 45 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \frac{1}{15} R_{3}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & -1 & -1 \\ 
         0 & 1 & 5 & 14 \\ 
         0 & 0 & 1 & 3 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + R_{3} \\ R_{2} - 5 R_{3} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & 0 & 2 \\ 
         0 & 1 & 0 & -1 \\ 
         0 & 0 & 1 & 3 \\ 
    \end{array} \right) 
\end{align*} $$ 

So the solution is $x_{1} = 2$, $x_{2} = -1$ and $x_{3} = 3$.

(c) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -17 \\ 
         2 & -2 & -3 & -14 \\ 
         3 & -1 & 4 & -13 \\ 
    \end{array} \right) 
    \begin{array}{l} -1 R_{1}\\ \phantom{x} \\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 5 & 2 & 17 \\ 
         2 & -2 & -3 & -14 \\ 
         3 & -1 & 4 & -13 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 2 R_{1} \\ R_{3} - 3 R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 5 & 2 & 17 \\ 
         0 & -12 & -7 & -48 \\ 
         0 & -16 & -2 & -64 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{1}{12} R_{2}\\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 5 & 2 & 17 \\ 
         0 & 1 & \frac{7}{12} & 4 \\ 
         0 & -16 & -2 & -64 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} - 5 R_{2} \\ \phantom{x} \\ R_{3} + 16 R_{2}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & - \frac{11}{12} & -3 \\ 
         0 & 1 & \frac{7}{12} & 4 \\ 
         0 & 0 & \frac{22}{3} & 0 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \frac{3}{22} R_{3}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & - \frac{11}{12} & -3 \\ 
         0 & 1 & \frac{7}{12} & 4 \\ 
         0 & 0 & 1 & 0 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{11}{12} R_{3}\\ R_{2} - \frac{7}{12} R_{3} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & 0 & -3 \\ 
         0 & 1 & 0 & 4 \\ 
         0 & 0 & 1 & 0 \\ 
    \end{array} \right) 
\end{align*} $$ 

So the solution is $x_{1} = -3$, $x_{2} = 4$ and $x_{3} = 0$.

(d) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|c} 
         -1 & -5 & -2 & -26 \\ 
         2 & -2 & -3 & -19 \\ 
         3 & -1 & -4 & -20 \\ 
    \end{array} \right) 
    \begin{array}{l} -1 R_{1}\\ \phantom{x} \\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 5 & 2 & 26 \\ 
         2 & -2 & -3 & -19 \\ 
         3 & -1 & -4 & -20 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 2 R_{1} \\ R_{3} - 3 R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 5 & 2 & 26 \\ 
         0 & -12 & -7 & -71 \\ 
         0 & -16 & -10 & -98 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{1}{12} R_{2}\\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 5 & 2 & 26 \\ 
         0 & 1 & \frac{7}{12} & \frac{71}{12} \\ 
         0 & -16 & -10 & -98 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} - 5 R_{2} \\ \phantom{x} \\ R_{3} + 16 R_{2}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & - \frac{11}{12} & - \frac{43}{12} \\ 
         0 & 1 & \frac{7}{12} & \frac{71}{12} \\ 
         0 & 0 & - \frac{2}{3} & - \frac{10}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ - \frac{3}{2} R_{3}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & - \frac{11}{12} & - \frac{43}{12} \\ 
         0 & 1 & \frac{7}{12} & \frac{71}{12} \\ 
         0 & 0 & 1 & 5 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{11}{12} R_{3}\\ R_{2} - \frac{7}{12} R_{3} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|c} 
         1 & 0 & 0 & 1 \\ 
         0 & 1 & 0 & 3 \\ 
         0 & 0 & 1 & 5 \\ 
    \end{array} \right) 
\end{align*} $$ 

So the solution is $x_{1} = 1$, $x_{2} = 3$ and $x_{3} = 5$.

(e) 

$$ \begin{align*} 
    & \left( \begin{array}{cccc|c} 
         3 & -5 & -4 & -1 & 28 \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         2 & 3 & 3 & -3 & 11 \\ 
         -2 & 2 & -5 & -4 & -21 \\ 
    \end{array} \right) 
    \begin{array}{l} \frac{1}{3} R_{1}\\ \phantom{x} \\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & - \frac{5}{3} & - \frac{4}{3} & - \frac{1}{3} & \frac{28}{3} \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         2 & 3 & 3 & -3 & 11 \\ 
         -2 & 2 & -5 & -4 & -21 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - 2 R_{1} \\ R_{4} + 2 R_{1}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & - \frac{5}{3} & - \frac{4}{3} & - \frac{1}{3} & \frac{28}{3} \\ 
         0 & -4 & 3 & -4 & 41 \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & - \frac{4}{3} & - \frac{23}{3} & - \frac{14}{3} & - \frac{7}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{1}{4} R_{2}\\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & - \frac{5}{3} & - \frac{4}{3} & - \frac{1}{3} & \frac{28}{3} \\ 
         0 & 1 & - \frac{3}{4} & 1 & - \frac{41}{4} \\ 
         0 & \frac{19}{3} & \frac{17}{3} & - \frac{7}{3} & - \frac{23}{3} \\ 
         0 & - \frac{4}{3} & - \frac{23}{3} & - \frac{14}{3} & - \frac{7}{3} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{5}{3} R_{2}\\ \phantom{x} \\ R_{3} - \frac{19}{3} R_{2} \\ R_{4} + \frac{4}{3} R_{2}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & - \frac{31}{12} & \frac{4}{3} & - \frac{31}{4} \\ 
         0 & 1 & - \frac{3}{4} & 1 & - \frac{41}{4} \\ 
         0 & 0 & \frac{125}{12} & - \frac{26}{3} & \frac{229}{4} \\ 
         0 & 0 & - \frac{26}{3} & - \frac{10}{3} & -16 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \frac{12}{125} R_{3}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & - \frac{31}{12} & \frac{4}{3} & - \frac{31}{4} \\ 
         0 & 1 & - \frac{3}{4} & 1 & - \frac{41}{4} \\ 
         0 & 0 & 1 & - \frac{104}{125} & \frac{687}{125} \\ 
         0 & 0 & - \frac{26}{3} & - \frac{10}{3} & -16 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{31}{12} R_{3}\\ R_{2} + \frac{3}{4} R_{3}\\ \phantom{x} \\ R_{4} + \frac{26}{3} R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 0 & - \frac{102}{125} & \frac{806}{125} \\ 
         0 & 1 & 0 & \frac{47}{125} & - \frac{766}{125} \\ 
         0 & 0 & 1 & - \frac{104}{125} & \frac{687}{125} \\ 
         0 & 0 & 0 & - \frac{1318}{125} & \frac{3954}{125} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \phantom{x} \\ - \frac{125}{1318} R_{4}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 0 & - \frac{102}{125} & \frac{806}{125} \\ 
         0 & 1 & 0 & \frac{47}{125} & - \frac{766}{125} \\ 
         0 & 0 & 1 & - \frac{104}{125} & \frac{687}{125} \\ 
         0 & 0 & 0 & 1 & -3 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{102}{125} R_{4}\\ R_{2} - \frac{47}{125} R_{4} \\ R_{3} + \frac{104}{125} R_{4}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 0 & 0 & 4 \\ 
         0 & 1 & 0 & 0 & -5 \\ 
         0 & 0 & 1 & 0 & 3 \\ 
         0 & 0 & 0 & 1 & -3 \\ 
    \end{array} \right) 
\end{align*} $$ 

So the solution is $x_{1} = 4$, $x_{2} = -5$, $x_{3} = 3$ and $x_{4} = -3$.

(f) 

$$ \begin{align*} 
    & \left( \begin{array}{cccc|c} 
         2 & -3 & -3 & 4 & -1 \\ 
         4 & -5 & 1 & -5 & 42 \\ 
         3 & 3 & -1 & -5 & 20 \\ 
         1 & 0 & 1 & 3 & -4 \\ 
    \end{array} \right) 
    \begin{array}{l} \frac{1}{2} R_{1}\\ \phantom{x} \\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & - \frac{3}{2} & - \frac{3}{2} & 2 & - \frac{1}{2} \\ 
         4 & -5 & 1 & -5 & 42 \\ 
         3 & 3 & -1 & -5 & 20 \\ 
         1 & 0 & 1 & 3 & -4 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 4 R_{1} \\ R_{3} - 3 R_{1} \\ R_{4} - R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & - \frac{3}{2} & - \frac{3}{2} & 2 & - \frac{1}{2} \\ 
         0 & 1 & 7 & -13 & 44 \\ 
         0 & \frac{15}{2} & \frac{7}{2} & -11 & \frac{43}{2} \\ 
         0 & \frac{3}{2} & \frac{5}{2} & 1 & - \frac{7}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{3}{2} R_{2}\\ \phantom{x} \\ R_{3} - \frac{15}{2} R_{2} \\ R_{4} - \frac{3}{2} R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 9 & - \frac{35}{2} & \frac{131}{2} \\ 
         0 & 1 & 7 & -13 & 44 \\ 
         0 & 0 & -49 & \frac{173}{2} & - \frac{617}{2} \\ 
         0 & 0 & -8 & \frac{41}{2} & - \frac{139}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ - \frac{1}{49} R_{3}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 9 & - \frac{35}{2} & \frac{131}{2} \\ 
         0 & 1 & 7 & -13 & 44 \\ 
         0 & 0 & 1 & - \frac{173}{98} & \frac{617}{98} \\ 
         0 & 0 & -8 & \frac{41}{2} & - \frac{139}{2} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} - 9 R_{3} \\ R_{2} - 7 R_{3} \\ \phantom{x} \\ R_{4} + 8 R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 0 & - \frac{79}{49} & \frac{433}{49} \\ 
         0 & 1 & 0 & - \frac{9}{14} & - \frac{1}{14} \\ 
         0 & 0 & 1 & - \frac{173}{98} & \frac{617}{98} \\ 
         0 & 0 & 0 & \frac{625}{98} & - \frac{1875}{98} \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \phantom{x} \\ \frac{98}{625} R_{4}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 0 & - \frac{79}{49} & \frac{433}{49} \\ 
         0 & 1 & 0 & - \frac{9}{14} & - \frac{1}{14} \\ 
         0 & 0 & 1 & - \frac{173}{98} & \frac{617}{98} \\ 
         0 & 0 & 0 & 1 & -3 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{79}{49} R_{4}\\ R_{2} + \frac{9}{14} R_{4}\\ R_{3} + \frac{173}{98} R_{4}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cccc|c} 
         1 & 0 & 0 & 0 & 4 \\ 
         0 & 1 & 0 & 0 & -2 \\ 
         0 & 0 & 1 & 0 & 1 \\ 
         0 & 0 & 0 & 1 & -3 \\ 
    \end{array} \right) 
\end{align*} $$ 

So the solution is $x_{1} = 4$, $x_{2} = -2$, $x_{3} = 1$ and $x_{4} = -3$.
```

```{admonition} Solution to Exercise 2.x6
:class: seealso

{prf:ref}`Exercise 2.6<systems-ex-gj-inverse>`

(a) 

$$ \begin{align*} 
    & \left( \begin{array}{cc|cc} 
         -4 & 2 & 1 & 0 \\ 
         3 & 4 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} - \frac{1}{4} R_{1}\\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & - \frac{1}{2} & - \frac{1}{4} & 0 \\ 
         3 & 4 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 3 R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & - \frac{1}{2} & - \frac{1}{4} & 0 \\ 
         0 & \frac{11}{2} & \frac{3}{4} & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \frac{2}{11} R_{2}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & - \frac{1}{2} & - \frac{1}{4} & 0 \\ 
         0 & 1 & \frac{3}{22} & \frac{2}{11} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{1}{2} R_{2}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & 0 & - \frac{2}{11} & \frac{1}{11} \\ 
         0 & 1 & \frac{3}{22} & \frac{2}{11} \\ 
    \end{array} \right) 
\end{align*} $$ 
So $A^{-1} = \left(\begin{matrix}- \frac{2}{11} & \frac{1}{11}\\\frac{3}{22} & \frac{2}{11}\end{matrix}\right)$. Checking this is correct

$$ \begin{align*} 
    \left(\begin{matrix}- \frac{2}{11} & \frac{1}{11}\\\frac{3}{22} & \frac{2}{11}\end{matrix}\right)\left(\begin{matrix}-4 & 2\\3 & 4\end{matrix}\right) = \left(\begin{matrix}1 & 0\\0 & 1\end{matrix}\right) \quad \checkmark\end{align*} $$

(b) 

$$ \begin{align*} 
    & \left( \begin{array}{cc|cc} 
         -4 & 2 & 1 & 0 \\ 
         -1 & -3 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} - \frac{1}{4} R_{1}\\ \phantom{x} \end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & - \frac{1}{2} & - \frac{1}{4} & 0 \\ 
         -1 & -3 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} + R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & - \frac{1}{2} & - \frac{1}{4} & 0 \\ 
         0 & - \frac{7}{2} & - \frac{1}{4} & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{2}{7} R_{2}\end{array} & 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & - \frac{1}{2} & - \frac{1}{4} & 0 \\ 
         0 & 1 & \frac{1}{14} & - \frac{2}{7} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + \frac{1}{2} R_{2}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{cc|cc} 
         1 & 0 & - \frac{3}{14} & - \frac{1}{7} \\ 
         0 & 1 & \frac{1}{14} & - \frac{2}{7} \\ 
    \end{array} \right) 
\end{align*} $$ 
So $A^{-1} = \left(\begin{matrix}- \frac{3}{14} & - \frac{1}{7}\\\frac{1}{14} & - \frac{2}{7}\end{matrix}\right)$. Checking this is correct

$$ \begin{align*} 
    \left(\begin{matrix}- \frac{3}{14} & - \frac{1}{7}\\\frac{1}{14} & - \frac{2}{7}\end{matrix}\right)\left(\begin{matrix}-4 & 2\\-1 & -3\end{matrix}\right) = \left(\begin{matrix}1 & 0\\0 & 1\end{matrix}\right) \quad \checkmark\end{align*} $$

(c) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|ccc} 
         -4 & -4 & -2 & 1 & 0 & 0 \\ 
         3 & 0 & 4 & 0 & 1 & 0 \\ 
         1 & 0 & 0 & 0 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} - \frac{1}{4} R_{1}\\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 1 & \frac{1}{2} & - \frac{1}{4} & 0 & 0 \\ 
         3 & 0 & 4 & 0 & 1 & 0 \\ 
         1 & 0 & 0 & 0 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 3 R_{1} \\ R_{3} - R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 1 & \frac{1}{2} & - \frac{1}{4} & 0 & 0 \\ 
         0 & -3 & \frac{5}{2} & \frac{3}{4} & 1 & 0 \\ 
         0 & -1 & - \frac{1}{2} & \frac{1}{4} & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ - \frac{1}{3} R_{2}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 1 & \frac{1}{2} & - \frac{1}{4} & 0 & 0 \\ 
         0 & 1 & - \frac{5}{6} & - \frac{1}{4} & - \frac{1}{3} & 0 \\ 
         0 & -1 & - \frac{1}{2} & \frac{1}{4} & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} - R_{2} \\ \phantom{x} \\ R_{3} + R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & \frac{4}{3} & 0 & \frac{1}{3} & 0 \\ 
         0 & 1 & - \frac{5}{6} & - \frac{1}{4} & - \frac{1}{3} & 0 \\ 
         0 & 0 & - \frac{4}{3} & 0 & - \frac{1}{3} & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ - \frac{3}{4} R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & \frac{4}{3} & 0 & \frac{1}{3} & 0 \\ 
         0 & 1 & - \frac{5}{6} & - \frac{1}{4} & - \frac{1}{3} & 0 \\ 
         0 & 0 & 1 & 0 & \frac{1}{4} & - \frac{3}{4} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} - \frac{4}{3} R_{3} \\ R_{2} + \frac{5}{6} R_{3}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & 0 & 0 & 0 & 1 \\ 
         0 & 1 & 0 & - \frac{1}{4} & - \frac{1}{8} & - \frac{5}{8} \\ 
         0 & 0 & 1 & 0 & \frac{1}{4} & - \frac{3}{4} \\ 
    \end{array} \right) 
\end{align*} $$ 
So $A^{-1} = \left(\begin{matrix}0 & 0 & 1\\- \frac{1}{4} & - \frac{1}{8} & - \frac{5}{8}\\0 & \frac{1}{4} & - \frac{3}{4}\end{matrix}\right)$. Checking this is correct

$$ \begin{align*} 
    \left(\begin{matrix}0 & 0 & 1\\- \frac{1}{4} & - \frac{1}{8} & - \frac{5}{8}\\0 & \frac{1}{4} & - \frac{3}{4}\end{matrix}\right)\left(\begin{matrix}-4 & -4 & -2\\3 & 0 & 4\\1 & 0 & 0\end{matrix}\right) = \left(\begin{matrix}1 & 0 & 0\\0 & 1 & 0\\0 & 0 & 1\end{matrix}\right) \quad \checkmark\end{align*} $$

(d) 

$$ \begin{align*} 
    & \left( \begin{array}{ccc|ccc} 
         4 & 0 & -4 & 1 & 0 & 0 \\ 
         4 & -1 & 1 & 0 & 1 & 0 \\ 
         3 & 1 & 2 & 0 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \frac{1}{4} R_{1}\\ \phantom{x} \\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & -1 & \frac{1}{4} & 0 & 0 \\ 
         4 & -1 & 1 & 0 & 1 & 0 \\ 
         3 & 1 & 2 & 0 & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ R_{2} - 4 R_{1} \\ R_{3} - 3 R_{1} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & -1 & \frac{1}{4} & 0 & 0 \\ 
         0 & -1 & 5 & -1 & 1 & 0 \\ 
         0 & 1 & 5 & - \frac{3}{4} & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ -1 R_{2}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & -1 & \frac{1}{4} & 0 & 0 \\ 
         0 & 1 & -5 & 1 & -1 & 0 \\ 
         0 & 1 & 5 & - \frac{3}{4} & 0 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ R_{3} - R_{2} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & -1 & \frac{1}{4} & 0 & 0 \\ 
         0 & 1 & -5 & 1 & -1 & 0 \\ 
         0 & 0 & 10 & - \frac{7}{4} & 1 & 1 \\ 
    \end{array} \right) 
    \begin{array}{l} \phantom{x} \\ \phantom{x} \\ \frac{1}{10} R_{3}\end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & -1 & \frac{1}{4} & 0 & 0 \\ 
         0 & 1 & -5 & 1 & -1 & 0 \\ 
         0 & 0 & 1 & - \frac{7}{40} & \frac{1}{10} & \frac{1}{10} \\ 
    \end{array} \right) 
    \begin{array}{l} R_{1} + R_{3} \\ R_{2} + 5 R_{3}\\ \phantom{x} \end{array} \\ \\ 
    \longrightarrow 
    & \left( \begin{array}{ccc|ccc} 
         1 & 0 & 0 & \frac{3}{40} & \frac{1}{10} & \frac{1}{10} \\ 
         0 & 1 & 0 & \frac{1}{8} & - \frac{1}{2} & \frac{1}{2} \\ 
         0 & 0 & 1 & - \frac{7}{40} & \frac{1}{10} & \frac{1}{10} \\ 
    \end{array} \right) 
\end{align*} $$ 
So $A^{-1} = \left(\begin{matrix}\frac{3}{40} & \frac{1}{10} & \frac{1}{10}\\\frac{1}{8} & - \frac{1}{2} & \frac{1}{2}\\- \frac{7}{40} & \frac{1}{10} & \frac{1}{10}\end{matrix}\right)$. Checking this is correct

$$ \begin{align*} 
    \left(\begin{matrix}\frac{3}{40} & \frac{1}{10} & \frac{1}{10}\\\frac{1}{8} & - \frac{1}{2} & \frac{1}{2}\\- \frac{7}{40} & \frac{1}{10} & \frac{1}{10}\end{matrix}\right)\left(\begin{matrix}4 & 0 & -4\\4 & -1 & 1\\3 & 1 & 2\end{matrix}\right) = \left(\begin{matrix}1 & 0 & 0\\0 & 1 & 0\\0 & 0 & 1\end{matrix}\right) \quad \checkmark\end{align*} $$
```

```{admonition} Solution to Exercise 2.7
:class: seealso

{prf:ref}`Exercise 2.7<systems-ex-consistency>`

(a) 

$$ \begin{align*}
&    \left( \begin{array}{ccc|c}
         1 & -1 & 2 & 2 \\
         2 & 1 & 4 & 7 \\
         4 & 1 & 1 & 4 \\
    \end{array} \right)
    \begin{matrix} \phantom{x} \\ R_{2} - 2 R_{1} \\ R_{3} - 4 R_{1} \end{matrix} &
    \longrightarrow &
    \left( \begin{array}{ccc|c}
         1 & -1 & 2 & 2 \\
         0 & 3 & 0 & 3 \\
         0 & 5 & -7 & -4 \\
    \end{array} \right)
    \begin{matrix} \phantom{x} \\ \phantom{x} \\ R_{3} - \frac{5}{3} R_{2} \end{matrix} \\ \\
    \longrightarrow &
    \left( \begin{array}{ccc|c}
         1 & -1 & 2 & 2 \\
         0 & 3 & 0 & 3 \\
         0 & 0 & -7 & -9 \\
    \end{array} \right)
\end{align*} $$

therefore $\operatorname{rank}(A) = 3$ and $\operatorname{rank}(A \mid \mathbf{b}) = 3$ so this system has a unique solution

$$ \begin{align*}
    x_{3} &= \frac{1}{-7} \left( -9\right) = \frac{9}{7}, \\
    x_{2} &= \frac{1}{3} \left( 3 - 0 \left( \frac{9}{7} \right)\right) = 1, \\
    x_{1} &= \frac{1}{1} \left( 2 - \left( -1 \right) \left( 1 \right) - 2 \left( \frac{9}{7} \right)\right) = \frac{3}{7}.
\end{align*} $$

(b) 

$$ \begin{align*}
&    \left( \begin{array}{ccc|c}
         1 & -1 & 2 & 3 \\
         2 & -3 & 7 & 4 \\
         -1 & 3 & -8 & 1 \\
    \end{array} \right)
    \begin{matrix} \phantom{x} \\ R_{2} - 2 R_{1} \\ R_{3} + R_{1} \end{matrix} &
    \longrightarrow &
    \left( \begin{array}{ccc|c}
         1 & -1 & 2 & 3 \\
         0 & -1 & 3 & -2 \\
         0 & 2 & -6 & 4 \\
    \end{array} \right)
    \begin{matrix} \phantom{x} \\ \phantom{x} \\ R_{3} + 2 R_{2} \end{matrix} \\ \\
    \longrightarrow &
    \left( \begin{array}{ccc|c}
         1 & -1 & 2 & 3 \\
         0 & -1 & 3 & -2 \\
         0 & 0 & 0 & 0 \\
    \end{array} \right)
\end{align*} $$

therefore $\operatorname{rank}(A) = 2$ and $\operatorname{rank}(A \mid \mathbf{b}) = 2$. Since $\operatorname{rank}(A) = \operatorname{rank}(A \mid \mathbf{b}) < 3$ then this system has infintely many solutons. Let $r = x_3$

$$ \begin{align*}
    x_2 &= \frac{1}{-1}(-2 - 3r) = 2 + 3r, \\
    x_1 &= 3 + 2 + 3r - 2r = 5 + r.
\end{align*} $$

(c)

$$ \begin{align*}
&    \left( \begin{array}{ccc|c}
         1 & 1 & -2 & 1 \\
         2 & -1 & 1 & 9 \\
         1 & 4 & -7 & 2 \\
    \end{array} \right)
    \begin{matrix} \phantom{x} \\ R_{2} - 2 R_{1} \\ R_{3} - R_{1} \end{matrix} &
    \longrightarrow &
    \left( \begin{array}{ccc|c}
         1 & 1 & -2 & 1 \\
         0 & -3 & 5 & 7 \\
         0 & 3 & -5 & 1 \\
    \end{array} \right)
    \begin{matrix} \phantom{x} \\ \phantom{x} \\ R_{3} + R_{2} \end{matrix} \\ \\
    \longrightarrow &
    \left( \begin{array}{ccc|c}
         1 & 1 & -2 & 1 \\
         0 & -3 & 5 & 7 \\
         0 & 0 & 0 & 8 \\
    \end{array} \right)
\end{align*} $$

therefore $\operatorname{rank}(A) = 2$ and $\operatorname{rank}(A \mid \mathbf{b}) = 3$. Since $\operatorname{rank}(A) < \operatorname{rank}(A \mid \mathbf{b})$ then this is an inconsistent system and does not have a solution.
```
