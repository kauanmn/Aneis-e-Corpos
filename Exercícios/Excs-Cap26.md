# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 26 - Exercises

<br>

### Exercise 1

Describe all ring homomorphisms of $\mathbb{Z} \times \mathbb{Z}$ into $\mathbb{Z} \times \mathbb{Z}$.

[Hint: Note that if $\phi$ is such a homomorphism, then $\phi((1,0)) = \phi((1,0))\phi((1,0))$ and $\phi((0,1)) = \phi((0,1))\phi((0,1))$. Consider also $\phi((1,0)(0,1))$]

<details>
<summary><strong>Solution</strong></summary><br>

Let $\phi$ be a homomorphism of $\mathbb{Z} \times \mathbb{Z}$ into $\mathbb{Z} \times \mathbb{Z}$.

Suppose that $\phi(1,0) = (m,n)$. From $\phi((1,0)) = \phi[(1,0)(1,0)]$, we see that $m^2 = m$ and $n^2 = n$. So $\phi(1,0)$ must be one of the elements $(0,0), (1,0), (0,1), (1,1)$.

By a similar argument, $\phi(0,1)$ must be one of these same four elements.

We also must have $\phi(1,0)\phi(0,1) = \phi(0,0) = (0,0)$. This gives just 9 possibilities:

1. $\phi(1,0) = (1,0)$ while $\phi(0,1) = (0,0) \lor \phi(0,1)$
2. $\phi(1,0) = (0,1)$ while $\phi(0,1) = (0,0) \lor \phi(1,0)$
3. $\phi(1,0) = (1,1)$ while $\phi(0,1) = (0,0)$
4. $\phi(1,0) = (0,0)$ while $\phi(0,1) = (0,0) \lor (1,0) \lor (0,1) \lor (1,1)$

All of these are homomorphisms.

</details>










<br>

---

In Exercises 5 through 7, correct the definition of the italicized term without reference to the text, if correction is needed, so that it is in a form acceptable for publication.

### Exercise 5

An _isomorphism of a ring_ $R$ with a ring $R'$ is a homomorphism $\phi : R \rightarrow R'$ such that $\text{Ker }(\phi) = \\{ 0 \\}$

<details>
<summary><strong>Solution</strong></summary><br>

The correct definition is:

$\phi$ maps $R$ onto $R'$.

An **ISOMORPHISM** of a ring $R$ with a ring $R'$ is a homomorphism $\phi : R \rightarrow R'$ mapping $R$ onto $R'$ such that $\text{Ker }(\phi) = \\{ 0 \\}$

</details>










<br>

### Exercise 6

An _ideal_ $N$ of a ring $R$ is an additive subgroup of $\langle R, + \rangle$ such that $\forall r \in R$ and $\forall n \in N$, we have $rn \in N$ and $nr \in N$.

<details>
<summary><strong>Solution</strong></summary><br>

The definition is correct.

</details>










<br>

### Exercise 7

The _kernel of a homomorphism_ $\phi$ mapping a ring $R$ into a ring $R'$ is $\\{\phi(r)=0 \mid r \in R \\}$

<details>
<summary><strong>Solution</strong></summary><br>

The definition is incorrect. The kernel is $\text{Ker }(\phi) = \\{ r \in R \mid \phi(r) = 0'\\}$

</details>

---










<br>

### Exercise 10

Mark each of the following true or false.

a. The concept of a ring homomorphism is closely connected with the idea of a factor ring.<br>
b. A ring homomorphism $\phi : R \rightarrow R'$ carries ideals of $R$ into ideals of $R'$.<br>
c. A ring homomorphism is one to one if and only if the kernel is $\\{ 0 \\}$.<br>
d. $\mathbb{Q}$ is an ideal in $\mathbb{R}$.<br>
e. Every ideal in a ring is a subring of the ring.<br>
f. Every subring of every ring is an ideal of the ring.<br>
g. Every quotient ring of every commutative ring is again a commutative ring.<br>
h. The rings $\mathbb{Z}/4\mathbb{Z}$ and $\mathbb{Z}_4$ are isomorphic.<br>
i. An ideal $N$ in a ring $R$ with unity 1 is all of $R$ if and only if $1 \in N$.<br>
j. The concept of an ideal is to the concept of a ring as the concept of a normal subgroup is to the concept of a group.

<details>
<summary><strong>Solution</strong></summary><br>

T F T F T F T T T T

b. A ring homomorphism $\phi : R \rightarrow R'$ DOES NOT carries ideals of $R$ into ideals of $R'$.<br>
d. $\mathbb{Q}$ is NOT an ideal in $\mathbb{R}$.<br>
f. NOT every subring of every ring is an ideal of the ring.<br>

</details>










<br>

### Exercise 12

Give an example to show that a factor ring of an integral domain may be a field.

<details>
<summary><strong>Solution</strong></summary><br>
$\mathbb{Z}$ is an integral domain and we know that $\mathbb{Z}/3\mathbb{Z} \cong \mathbb{Z}_{3}$, which is a field.
</details>










<br>

### Exercise 13

Give an example to show that a factor ring of an integral domain may have divisors of 0.

<details>
<summary><strong>Solution</strong></summary><br>
$\mathbb{Z}$ is an integral domain and we know that $\mathbb{Z}/4\mathbb{Z} \cong \mathbb{Z}_{4}$, where $2$ is a divisor of zero.
</details>










<br>

### Exercise 14

Give an example to show that a factor ring of a ring with divisors of 0 may be an integral domain.

<details>
<summary><strong>Solution</strong></summary><br>

$\mathbb{Z} \times \mathbb{Z}$ has divisors of zero, but $(\mathbb{Z} \times \mathbb{Z})/(\mathbb{Z} \times \\{ 0 \\}) \cong \mathbb{Z}$ which has no divisors of zero.

</details>










<br>

### Exercise 15

Find a subring of the ring $\mathbb{Z} \times \mathbb{Z}$ that is not an ideal of $\mathbb{Z} \times \mathbb{Z}$.

<details>
<summary><strong>Solution</strong></summary><br>

Let $S = (n, n) \subset \mathbb{Z} \times \mathbb{Z}, n \in \mathbb{Z}$.

$S$ is a subring, but not an ideal, because $(n,n) \cdot (2,1) = (2n, n) \notin S$ and $(2,1) \in \mathbb{Z} \times \mathbb{Z}$

</details>










<br>

### Exercise 16

A student is asked to prove that a quotient ring of a ring $R$ modulo an ideal $N$ is commutative if and only if $(rs-sr) \in N, \forall r,s \in R$.

The student starts out:

Assume $R/N$ is commutative. Then $rs = sr$, for all $r,s \in R/N$.

<br>

a. Why does the instructor reading this expect nonsense from there on?
b. What should the student have written?
c. Prove the assertion (note the "if and only if")


<details>
<summary><strong>Solution</strong></summary><br>

a. $r$ and $s$ are elements of $R$, not $R/N$.

b. Assume that $R/N$ is commutative. Then, we have

```math
(r + N)(s + N) = (s + N)(r + N)
```

c. Let $r,s \in R$. Then

```math
\begin{aligned}

(r+N)(s+N) &= (s + N)(r + N)\\
rs + N &= sr + N\\
(rs + N) - (sr + N) &= N\\
(rs - sr) + N &= N\\

\end{aligned}
```

$(rs-sr) + N = N$ if, and only if, $(rs-sr) \in N$.

</details>
