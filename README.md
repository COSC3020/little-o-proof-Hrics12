[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/wM4-KOzy)
# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

With $f(n)\in o(g(n))$ = 0 meaning that when $f(n)$ grows less then $g(n)$ as $n$ nears infinity.
$f(n)\in O(g(n))$ says there is a constant $c$ greater then 0 and $n_0$. Meaning $f(n)$ is above a constant multiple $c*g(n)$ for a large value $n$.
This means $f(n)$ is a constant multiple higher then $g(n)$ for a large $n$.
You can then say that $n>n_0$ and the $lim_{n\to\infty} \frac{f(n)}{g(n)} = 0 < c$ ....... 
$n>n_0, \frac{f(n)}{g(n)} < c$
