### Exercício 1

Se $R$ é um anel tal que $ab = ca, a \neq 0$ implica que $b = c$, então $R$ é comutativo.

<details>
<summary><strong>Solução</strong></summary><br>

Seja $a,b \in R$.

Se $a = 0$ ou $b = 0$, então $cd = dc = 0$.

Se $a,b \neq 0$, então

```math

\begin{aligned}
    ab &= c\\
    (ab)a &= ca\\
    a(ba) &= ca\\
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

    (a+b)(a-b) &= a(a-b) + b(a-b)\\
    &= a^2 - ab + ba - b^2

\end{aligned}

```

Logo,

```math

\begin{aligned}

    (a+b)(a-b) = a^2 - b^2 &\iff (-ab + ba) = 0\\
    &\iff ab =ba

\end{aligned}

```

</details>










<br>

### Exercício 3

Prove que $2\mathbb{Z}$ e $3\mathbb{Z}$ não são isomorfos.

<details>
<summary><strong>Solução</strong></summary><br>

Suponha que exista um isomorfismo $f:2\mathbb{Z} \rightarrow 3\mathbb{Z}$

Assim, $f(2) = 3a$ para algum $a \in \mathbb{Z}$.

Então, calculamos $f(4)$ de duas formas diferentes:

1. $f(4) = f(2) + f(2) = 3a + 3a = 6a$
2. $f(4) = f(2) \cdot f(2) = 3a \cdot 3a = 9a^2$

Logo, $6a = 9a^2$, cuja única solução é $a = 0$.

Porém, $f(0) = 0 = f(2)$, o que contradiz com o fato de $f$ ser uma função injetora. Portanto, $2\mathbb{Z}$ e $3\mathbb{Z}$ não são isomorfos.

</details>










<br>

### Exercício 4

Prove que $\langle x^2 + 1 \rangle$ não é um ideal primo de $\mathbb{Z}_{2}[x]$

<details>
<summary><strong>Solução</strong></summary><br>

Seja $I = \langle x^2 + 1 \rangle$. Suponha que $I$ é primo em $\mathbb{Z}_{2}[x]$.

<br>

(1) Temos $\overline{1} = \overline{-1}$, o que leva a $x^2 + 1 = x^2 - 1$ em $\mathbb{Z}_{2}[x]$

(2) Se $\langle x^2 + 1 \rangle$ é primo em $\mathbb{Z}_{2}[x]$, então

```math
\mathbb{Z}_{2}[x] / \langle x^2 + 1 \rangle
```

é um domínio de integridade.

<br>

Neste quociente, $\overline{x^2 + 1} = \overline{0}$. Por outro lado, $0 = \overline{x^2 + 1} = \overline{x^2 - 1} = \overline{(x+1)}\overline{(x-1)}$.

Por ser um domínio de integridade, $\overline{x-1} \neq 0$ e $\overline{x+1} \neq 0$, o que é uma contradição.

Logo, $\langle x^2 + 1 \rangle$ não é ideal primo de $\mathbb{Z}_{2}[x]$


</details>
