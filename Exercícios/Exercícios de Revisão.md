### Exercício 1

Se $R$ é um anel tal que $ab = ca, a \neq 0$ implica que $b = c$, então $R$ é comutativo.

<details>
<summary><strong>Solução</strong></summary><br>

Seja $a,b \in R$.

Se $a = 0$ ou $b = 0$, então $cd = dc = 0$.

Se $a,b \neq 0$, então

```math

\begin{aligned}
    ab &= c
    (ab)a &= ca
    a(ba) &= ca
    ba &= c
\end{aligned}

```

Logo, $R$ é comutativo.

</details>










<br>

### Exercício 2

$R$ é um anel tal que $\forall a,b \in R, a^2 - b^2 = (a+b)(a-b) \iff R$ é comutativo.

<details>
<summary><strong>Solução</strong></summary><br>

```math

\begin{aligned}

    (a+b)(a-b) &= a(a-b) + b(a-b)
    &= a^2 - ab + ba - b^2

\end{aligned}

```

Logo,

```math

\begin{aligned}

    (a+b)(a-b) = a^2 - b^2 &\iff (-ab + ba) = 0
    &\iff ab =ba

\end{aligned}

```

</details>
