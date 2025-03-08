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
$$ (eqns)

We first translate our system of equations into an *augmented* matrix,

$$
\begin{align}
  \left[ {\begin{array}{cccccc}
    \textcolor{blue}{a_{11}} &  \textcolor{blue}{a_{12}} &  &  \textcolor{blue}{\cdots} &  &  \textcolor{blue}{a_{1n}}\\
     \textcolor{blue}{a_{21}} &  \textcolor{blue}{a_{22}} &  &  \textcolor{blue}{\cdots} &  &  \textcolor{blue}{a_{2n}}\\
     \textcolor{blue}{\vdots} &  \textcolor{blue}{\vdots} &  &  \textcolor{blue}{\ddots} &  &  \textcolor{blue}{\vdots}\\
     \textcolor{blue}{a_{n1}} &  \textcolor{blue}{a_{n2}} &  &  \textcolor{blue}{\cdots} &  &  \textcolor{blue}{a_{nn}}\\
  \end{array} } \right|
  \left. {{\begin{array}{c}
  \textcolor{red}{b_1} \\
  \textcolor{red}{b_2} \\
  \textcolor{red}{\vdots} \\
  \textcolor{red}{b_n} \\
  \end{array}}} \right] 
\end{align}
$$

where the *coefficient* matrix (elements in blue) is augmented by the right hand side of Eqs. {eq}`eqns` (elements in red).
