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

Definition of $O$: $f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$


Ok, im starting over:

We know that there is a point $n_0$ beyond that's always $f(n)< c* g(n)$ for any positive constant $c$  in the definition of $f(n)\in o(g(n))$. We can then pick a positive constant $a$ that is less then our
constant $c$. $a$ is the constant we would use for the definition of $f(n)\in O(g(n))$. We know that $\forall n\ge n_0 : f(n) < cg(n)$. Now we can see $f(n) < ag(n)$ when constant $a$ is used instead of the larger costant $c$ we show the definiton of $O$ is satisfied.

