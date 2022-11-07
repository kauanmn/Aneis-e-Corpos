# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 27 - Exercises

<br>

### Exercise 1

Find all prime ideals and all maximal ideals of $\mathbb{Z}_{6}$

<details>
<summary><strong>Solution</strong></summary><br>

Because a finite integral domain is a field, the prime and the maximal ideals are the same.

The ideals $\\{ 0,2,4 \\}$ and $\\{ 0,3 \\}$ are both prime and maximal because the factor rings are isomorphic to the fields

```math
\mathbb{Z}_{2} \text{ and } \mathbb{Z}_{3}
```

respectively.

</details>










<br>

### Exercise 2

Find all prime ideals and all maximal ideals of $\mathbb{Z}_{12}$.

<details>
<summary><strong>Solution</strong></summary><br>

Because a finite integral domain is a field, the prime and the maximal ideals are the same.

The ideals $\\{ 0,2,4,6,8,10 \\}$ and $\\{ 0,3,6,9 \\}$ are both prime and maximal because the factor rings are isomorphic to the fields

```math
\mathbb{Z}_{2} \text{ and } \mathbb{Z}_{3}
```

respectively.

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










---

<br>

In Exercises 10 through 13, correct the definition of the italicized term without reference to the text, if correction is needed, so that it is in a form acceptable for publication.

### Exercise 10

A _maximal ideal_ of a ring $R$ is an ideal that is not contained in any other ideal of $R$.

<details>
<summary><strong>Solution</strong></summary><br>

The definition is INCORRECT, but ideals are not $R$.

A **MAXIMAL IDEAL** of a ring $R$ is an ideal $M$ such that there is no ideal $N$ of $R$ such that $M \subset N \subset R$

</details>










<br>

### Exercise 11

A _prime ideal_ of a commutative ring $R$ is an ideal of the form $pR = \\{ pr \mid r \in R \\}$ for some prime $p$.

<details>
<summary><strong>Solution</strong></summary><br>

The definition is INCORRECT.

A **PRIME IDEAL** of a commutative ring $R$ is an ideal $N$ such that if $a,b \in R$ and $ab \in N$, then either $a \in N$ or $b \in N$.

</details>










<br>

### Exercise 12

A _prime field_ is a field that has no proper subfields.

<details>
<summary><strong>Solution</strong></summary><br>

The definition is CORRECT.

</details>










<br>

### Exercise 13

A _principal ideal_ of a commutative ring with unity is an ideal $N$ with the property that there exists $a \in N$ such that $N$ is the smallest ideal that contains $a$.

<details>
<summary><strong>Solution</strong></summary><br>

The definition is CORRECT.

</details>
