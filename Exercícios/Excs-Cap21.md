# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 21 - Exercises

<br>

### Exercise 7

Prove Part 3 of the Step 3. You may assume any preceding part of Step 3.

<details>
<summary><strong>Solution</strong></summary>

<br>
Let $F$ be a field of quotients and $[(a,b)] \in F$.

```math
  [(a,b)] + [(0,1)] = [(a \cdot 1+b \cdot 0, b \cdot 1)] = [(a,b)]
```

And Part 1 states that addition in $F$ is commutative. Then, we have

```math
    [(0,1)] + [(a,b)] = [(a,b)]
```

</details>










<br>

### Exercise 12

Let $R$ be a nonzero commutative ring, and let $T$ be a nonempty subset of $R$ closed under multiplication and containing neither $0$ nor divisors of $0$. Starting with $R \times T$ and otherwise exactly following the construction in this section, we can show that the ring $R$ can be enlarged to a partial ring of quotients $Q(R,T)$.

Think about this for 15 minutes or so; look back over the construction and see why things still work. In particular, show the following:

a. $Q(R,T)$ has unity even if $R$ does not
b. In $Q(R,T)$. every nonzero element of $T$ is a unit

<details>
<summary><strong>Solution</strong></summary><br>
a. Because $T$ is nonempty, there exits $a \in T$. Then $[(a,a)]$ is unity in $Q(R,T)$, because

```math
[(a,a)] \cdot [(b,c)] = [(ab, ac)] \sim [(b,c)]
```

since $abc = acb$ in the commutative ring $R$.

<br>

b. A nonzero element $a \in T$ is identified with $[(aa,a)]$ in $Q(R,T)$. Because $T$ has no divisors, $[a,aa] \in Q(R,T)$, and we see that $[(aa,a)] \cdot [(a,aa)] = [(aaa,aaa)] \sim [(a,a)]$, because $aaaa = aaaa$. We say in 12.a that $[(a,a)]$ is unity in $Q(R,T)$.

Commutativity of $Q(R,T)$ shows that $[(a,aa)] \cdot [(aa,a)]$ is unity also, so $a \in T$ has an inverse in $Q(R,T)$ if $a \neq 0$.
</details>
