(page_topic1)=
Root Finding in One Dimension
=======================

The *root finding problem* is fairly simple to state:
- Given $f \in C[a,b]$, find $x^*$ such that $f(x^*)=0$.

Before attempting to solve this problem, there are a few considerations:
- Do you know if there is a solution?
- If there is a solution, is a simple root $f'(x^*) \neq 0$ or a multiple root $f'(x^*) = 0$?
- How many roots are there?
- How accurately do you want to know the solution?
- How much of a hurry are you in to get the solution?

The first step to answering these considerations is usually to attempt to plot the function so that you can *bracket the root*.  By this we mean find a region $[a,b]$ where $f(a)$ and $f(b)$ have different signs, i.e. $f(a)*f(b) < 0$.  The Intermediate Value Theorem from calculus then requires that, if $f \in C[a,b]$, there is a point $x^*$ in $[a,b]$ where $f(x^*)=0$.

We will defer the question of simple versus multiple roots to later in the chapter and start with the simplest and most sure-fire way of finding a bracketed root.  We will then look at potentially faster ways of finding a root, although not with the same guarantees of finding it.  Finally we will discuss combination methods that alternate between different ways of searching for the root trying to balance finding it quickly while guaranteeing that we will find it.




