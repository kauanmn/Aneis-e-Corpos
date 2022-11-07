# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 19 - Exercises

<br>

In Exercises 5 through 10, find the characteristic of the given ring.

### Exercise 5

$2\mathbb{Z}$

<details>
<summary><strong>Solution</strong></summary>

<br>$\text{char}(2\mathbb{Z}) = 0$

</details>










<br>

### Exercise 6

$\mathbb{Z} \times \mathbb{Z}$

<details>
<summary><strong>Solution</strong></summary>

<br>
$\text{char}(\mathbb{Z} \times \mathbb{Z}) = 0$

</details>










<br>

### Exercise 7

$\mathbb{Z}_3 \times 3\mathbb{Z}$

<details>
<summary><strong>Solution</strong></summary>

<br>
$\text{char}(\mathbb{Z}_3 \times 3\mathbb{Z}) = 0$

</details>










<br>

### Exercise 8

$\mathbb{Z}_3 \times \mathbb{Z}_3$

<details>
<summary><strong>Solution</strong></summary>

<br>
$\text{char}(\mathbb{Z}_3 \times \mathbb{Z}_3) = 3$

</details>










<br>

### Exercise 9

$\mathbb{Z}_3 \times \mathbb{Z}_4$

<details>
<summary><strong>Solution</strong></summary>

<br>
$\text{char}(\mathbb{Z}_3 \times \mathbb{Z}_4) = 12$

</details>










<br>

### Exercise 10

$\mathbb{Z} _{6} \times \mathbb{Z} _{15}$

<details>
<summary><strong>Solution</strong></summary>

<br>
$\text{char}(\mathbb{Z}_6 \times \mathbb{Z}_{15}) = 30$

</details>










<br>

### Exercise 11

Let $R$ be a commutative ring with unity of characteristic 4. Compute and simplify $(a+b)^4$ for $a,b \in R$.

<details>
<summary><strong>Solution</strong></summary><br>

```math
\begin{aligned}
    (a+b)^4 &= ((a+b)^2)^2\\
    &= (a^2 + ab + ba + b^2)^2\\
    &= (a^2 + ab + ab + b^2)^2\\
    &= (a^2 + 2ab + b^2)^2\\
    &= (a^2 + b^2)^2\\
    &= a^4 + a^2b^2 + b^2a^2 + a^4\\
    &= a^4 + a^2b^2 + a^2b^2 + a^4\\
    &= a^4 + 2a^2b^2 + a^4\\
    &= a^4 + a^4
\end{aligned}
```

</details>










<br>

### Exercise 12

Let $R$ be a commutative ring with unity of characteristic 3. Compute and simplify $(a+b)^9$ for $a,b \in R$

<details>
<summary><strong>Solution</strong></summary><br>

```math
\begin{aligned}
    (a+b)^9 &= a^9 + 9a^8b^1 + 36a^7b^2 + \cdots + 36a^2b^7 + 9a^1b^8 + b^9\\
    &= a^9 + 3(3a^8b^1 + 12a^7b^2 + \cdots + 12a^2b^7 + 3a^1b^8) + b^9\\
    &= a^9 + b^9
\end{aligned}
```
</details>










<br>

### Exercise 21

Give a one-sentence synopsis of the proof of the "if" part of Theorem 19.5

<details>
<summary><strong>Solution</strong></summary><br>

Let $R$ be a ring in which the cancellation laws hold, and suppose $ab=0$ for some $a,b \in R$. We must show that either $a$ or $b$ is $0$

We can rewrite $ab = ac$ as $a(b-c) = 0$. Because there are no divisors of zero, $a \neq 0$ or $b=c$

</details>










<br>

### Exercise 25

Show that a finite ring $R$ with unity $1 \neq 0$ and no divisors of 0 is a division ring.

(It is actually a field, although commutativity is not easy to prove. See Theorem 24.10)

[Note: In your proof, to show that $a \neq 0$ is a unit, you must show that a "left multiplicative inverse" of $a \neq 0$ in $R$ is also a "right multiplicative inverse."]

<details>
<summary><strong>Solution</strong></summary><br>

Let $R$ be a finite ring with unity $1 \neq 0$ and no divisors of 0. Thus, the cancellation laws are valid.

Theorem 19.11 show us that every finite integral domain is a field.

Also, using the cancellation laws, the Theorem 19.11 proof shows that every nonzero $a \in R$ has a right multiplicative inverse $a_i$. A similar construction can show that $a$ also has a left multiplicative inverse $a_j$. By associativity of multiplication, we have

```math
\begin{aligned}
    a_{j} &= a_j(aa_{i})\\
    &= (a_{j}a)a_{i}\\
    &= 1 \cdot a_{i}\\
    &= a_{i}
\end{aligned}
```

Thus, every nonzero element is a unity. By definition, $R$ is a division ring.

</details>










<br>

### Exercise 28

Show that if $D$ is an integral domain, then $\\{ n \cdot 1 \mid n \in \mathbb{Z} \\}$ is a subdomain of $D$ contained in every subdomain of $D$.

<details>
<summary><strong>Solution</strong></summary><br>

Let $R = \\{ n \cdot 1 \mid n \in \mathbb{Z} \\}$

- Addition closure: $(n \cdot 1) + (m \cdot 1) = n \cdot 1 + m \cdot 1 = (n + m) \cdot 1 \in R$
- Addition neutral element: let $n = 0$, then we have $(n \cdot 1) + (0 \cdot 1) = (n + 0) \cdot 1 = n \cdot 1$
- Additive inverse: the inverse of $n \cdot 1$ is $-n \cdot 1$: $(n \cdot 1) + (-n \cdot 1) = (n - n) \cdot 1 = 0 \cdot 1 = 0$
    
This shows that $R$ is an abelian group with the operation $+$
    
- Multiplicative closure: with distributive laws, we have $(n \cdot 1)(m \cdot 1) = (nm) \cdot 1 \in R$
- Multiplicative identity: because $1 \cdot 1 = 1$, then $1 \in R$

Thus $R$ is a commutative ring with unity.

- Does $R$ have zero divisors? because a product $ab=0$ in $R$ can also be viewed as a product in $D$, we see that $R$ also has no divisors of zero.

Thus, $R$ is a subdomain of $D$

</details>
