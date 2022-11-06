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

### Exercise 12

Let $R$ be a commutative ring with unity of characteristic 3. Compute and simplify $(a+b)^9$ for $a,b \in R$

<details>
<summary><strong>Solution</strong></summary><br>

```math
    \displaylines{
        (a+b)^9 = a^9 + 9a^8b^1 + 36a^7b^2 + \cdots + 36a^2b^7 + 9a^1b^8 + b^9\\
        = a^9 + 3(3a^8b^1 + 12a^7b^2 + \cdots + 12a^2b^7 + 3a^1b^8) + b^9\\
        = a^9 + b^9
    }
```
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
