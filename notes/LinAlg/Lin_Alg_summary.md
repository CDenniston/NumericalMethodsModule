(page_topic1)=
Numerical Linear Algebra
=======================

In this chapter we are primarily interested in systems with a unique solution so we will consider a system of $n$ linear equations in $n$ unknowns:

$$\begin{align}
E_1:\quad a_{11}x_1+a_{12}x_2+\cdots+a_{1n}x_n&=b_1\\
E_2:\quad a_{21}x_1+a_{22}x_2+\cdots+a_{2n}x_n&=b_2\\
\vdots\quad\qquad\qquad\qquad \vdots \qquad\qquad\qquad &\quad\,\, \vdots \\
E_1:\quad a_{n1}x_1+a_{n2}x_2+\cdots+a_{nn}x_n&=b_n\\
\end{align}
$$

We first translate our system of equations into an *augmented* matrix

$$
\begin{align}
  \left[ {\begin{array}{cccccc}
    a_{11} & a_{12} &  & \cdots &  & a_{1n}\\
    a_{21} & a_{22} &  & \cdots &  & a_{2n}\\
    \vdots & \vdots &  & \ddots &  & \vdots\\
    a_{n1} & a_{n2} &  & \cdots &  & a_{nn}\\
  \end{array} } \textcolor{lightgray}{\right|}
  \left. {{\begin{array}{c}
  b_1 \\
  b_2 \\
  \vdots \\
  b_n \\
  \end{array}}} \right] 
\end{align}
$$ 