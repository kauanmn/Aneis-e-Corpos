# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 18 - Exercises


In Exercises 7 through 13, decide whether the indicated operations of addition and multiplication are defined (closed) on the set, and give a ring structure. If a ring is not formed, tell why this is the case. If a ring is formed, state whether the ring is commutative, whether it has unity, and whether it is a field.

<br>

### Exercise 11

$\\{ a + b \sqrt{2} \mid a,b \in \mathbb{Z} \\}$ with the usual addition and multiplication

<details>
    <summary><strong>Solution</strong></summary>
    <br>

$\\{ a + b \sqrt{2} \mid a,b \in \mathbb{Z} \\}$ is a commutative ring with unity, but not a field
    
1. Associative:
```math
\displaylines{
  (a + b)+c\\
  = ((a_1 + b_1\sqrt{2}) + (a_2 + b_2\sqrt{2})) + (a_3 + b_3\sqrt{2}) \\
  = ((a_1 + a_2) + (b_1 + b_2)\sqrt{2}) + (a_3 + b_3\sqrt{2})\\
  = (a_1 + a_2 + a_3) + (b_1 + b_2 + b_3)\sqrt{2}\\
  = (a_1 + (a_2 + a_3)) + (b_1 + (b_2 + b_3))\sqrt{2}\\
  = (a_1 + b_1\sqrt{2}) + ((a_2 + a_3) + (b_2 + b_3)\sqrt{2})\\
  = (a_1 + b_1\sqrt{2}) + ((a_2 + b_2\sqrt{2}) + (a_3 + b_3\sqrt{2}))\\
  = a + (b + c)

}
```
<br>

2. Additive identity is $(0 + 0\sqrt{2})$:

```math
    a + 0 = (a_1 + b_1\sqrt{2}) + (0 + 0\sqrt{2}) = (a_1 + 0) + (b_1 + 0)\sqrt{2} = (a_1) + (b_1)\sqrt{2} = a
```

<br>

3. Additive inverse: $a = a_1 + b_1\sqrt{2} \rightarrow -a = -a_1 - b_1\sqrt{2}$

```math
    a + (-a) = (a_1 + b_1\sqrt{2}) + (-a_1 - b_1\sqrt{2}) = (a_1 - a_1) + (b_1 - b_1)\sqrt{2} = 0 + 0\sqrt{2} = 0
```

<br>

4. Commutative: $(a_1 + b_1\sqrt{2}) + (a_2 + b_2\sqrt{2}) = (a_1 + a_2) + (b_1 + b_2)\sqrt{2} = (a_2 + a_1) + (b_2 + b_1)\sqrt{2} = (a_2)$

<br>

5. Multiplicative associativity and distributive law too long and I am tired :/

6. Unity: $1_{A} = 1 + 0 \sqrt{2}$

```math
    a \cdot 1_{A} = (a+b\sqrt{2}) \cdot (1 + 0\sqrt{2}) = (a \cdot 1) + b\sqrt{2} = a + b\sqrt{2} = 1
```

<br>

7. Multiplicative commutativity:

```math
    \displaylines{
        a \cdot b
        = (a_1 + b_1\sqrt{2}) \cdot (a_2 + b_2\sqrt{2})\\
        = a_{1}a_{2} + a_{1}b_{2}\sqrt{2} + b_{1}a_{2}\sqrt{2} + 2b_{1}b_{2}\\
        = a_{2}a_{1} + a_{2}b_{1}\sqrt{2} + b_{2}a_{1}\sqrt{2} + 2b_{2}b_{1}\\
        = (a_2 + b_2\sqrt{2}) \cdot (a_1 + b_1\sqrt{2}) \\
        = b \cdot a
    }
```
</details>
