# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 27 - Exercises

<br>

### Exercise 1

Find all prime ideals and all maximal ideals of $\mathbb{Z}_{6}$

<details>
<summary><strong>Solution</strong></summary><br>

Because a finite integral domain is a field, the prime and the maximal ideals are the same.

The ideals $\\{ 0,2,4 \\}$ and $\\{ 0,3 \\}$ are both prime and maximal because the factor rings are isomorphic to the fields $\mathbb{Z}_{2}$ and $\mathbb{Z}_{3}$ respectively.

</details>










<br>

### Exercise 2

Find all prime ideals and all maximal ideals of $\mathbb{Z}_{12}$.

<details>
<summary><strong>Solution</strong></summary><br>

Because a finite integral domain is a field, the prime and the maximal ideals are the same.

The ideals $\\{ 0,2,4,6,8,10 \\}$ and $\\{ 0,3,6,9 \\}$ are both prime and maximal because the factor rings are isomorphic to the fields $\mathbb{Z}_{2}$ and $\mathbb{Z}_{3}$ respectively.

</details>










<br>

### Exercise 5

Find all $c \in \mathbb{Z}_3$ such that $\mathbb{Z}_3[x]/\langle x^2 + c \rangle$ is a field.

<details>
<summary><strong>Solution</strong></summary><br>

Consider the following theorem:

An ideal $\langle p(x) \rangle \neq \\{ 0 \\}$ of $F[x]$ is maximal if and only if $p(x)$ is irreducible over $F$.

Because of this, we just need to find all values of $c$ such that $(x^2 + c)$ is irreducible over $\mathbb{Z}_3$.

Let $f(x) = x^2$. Then $f(0) = 0, f(1) = 1, f(2) = 1$. We must find $c \in \mathbb{Z}_3$ such that $(0 + c)$ and $(1 + c)$ are both nonzero. The only choice is $c = 1$.

</details>










<br>

### Exercise 6

Find all $c \in \mathbb{Z}_3$ such that $\mathbb{Z}_3[x]/\langle x^3 + x^2 + c \rangle$ is a field.

<details>
<summary><strong>Solution</strong></summary><br>

Consider the following theorem:

An ideal $\langle p(x) \rangle \neq \\{ 0 \\}$ of $F[x]$ is maximal if and only if $p(x)$ is irreducible over $F$.

Because of this, we just need to find all values of $c$ such that $(x^3 + x^2 + c)$ is irreducible over $\mathbb{Z}_3$.

Let $f(x) = x^3 + x^2$. Then $f(0) = 0, f(1) = 2, f(2) = 0$. We must find $c \in \mathbb{Z}_3$ such that $(0 + c)$ and $(2 + c)$ are both nonzero. The only choice is $c = 2$.

</details>
