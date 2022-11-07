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










<br>

### Exercício 5

Prove que $2\mathbb{Z}$ é um ideal maximal de $\mathbb{Z}$

<details>
<summary><strong>Solução</strong></summary><br>

Como $\mathbb{Z}/2\mathbb{Z} \cong \mathbb{Z}_{2}$ é um corpo, então $2\mathbb{Z}$ é maximal em $\mathbb{Z}$.

$p\mathbb{Z}$ é maximal em $\mathbb{Z}$, se $p$ é primo.

</details>










<br>

### Exercício 6

Os grupos aditivos $\mathbb{Z}$ and $3\mathbb{Z}$ são isomorfos. São isomorfos como anéis?

<details>
<summary><strong>Solução</strong></summary><br>

Suponha que exista um isomorfismo $\phi : \mathbb{Z} \rightarrow 3\mathbb{Z}$.

Seja $\phi(x) = 3a$ e $\phi(y) = 3b$, com $a,b \in \mathbb{Z}$ Então,

```math
\begin{aligned}
    \phi(xy) &= \phi(x)\phi(y)\\
    &= 3a \cdot 3b\\
    &= 3 \cdot (3ab)\\
    &= 3 \phi(xy)
\end{aligned}
```

Um absurdo. Logo, não existe tal isomorfismo.

</details>

Prove que $2\mathbb{Z}$ é um ideal maximal de $\mathbb{Z}$

<details>
<summary><strong>Solução</strong></summary><br>

Como $\mathbb{Z}/2\mathbb{Z} \cong \mathbb{Z}_{2}$ é um corpo, então $2\mathbb{Z}$ é maximal em $\mathbb{Z}$.

$p\mathbb{Z}$ é maximal em $\mathbb{Z}$, se $p$ é primo.

</details>










<br>

### Exercício 7

Em $M_{3}(\mathbb{R})$, consideremos a solução da equação $X^2 = I_{3 \times 3}$. Então $X^2 - I_{3 \times 3} = 0$. Logo $(X - I_{3 \times 3})(X + I_{3 \times 3})$ = 0$. Portanto, $X = I_{3 \times 3}$ ou $X = -I_{3 \times 3}$

<details>
<summary><strong>Solução</strong></summary><br>

Esta afirmação é falsa porque toda matriz elementar é invertível. Logo, não necessariamente $X = I_{3 \times 3}$ ou $X = -I_{3 \times 3}$.

</details>










<br>

### Exercício 8

Encontrar os anéis da forma $\mathbb{Z}_{m}/I$, onde $m > 1$

<details>
<summary><strong>Solução</strong></summary><br>

O primeiro passo é observar que $\mathbb{Z}_m = \mathbb{Z}/m\mathbb{Z}$. Lembremos também que $\langle m \rangle = m\mathbb{Z} = \\{mt \mid t \in \mathbb{Z} \\}$

Se usarmos o epimorfismo $\pi : \mathbb{Z} \rightarrow \mathbb{Z}/m\mathbb{Z}$ tal que $\pi(l) = l + m\mathbb{Z}$, podemos utilizar o Teorema de Correspondência.

Com o Teorema da Correspondência, os ideais de $\mathbb{Z}/m\mathbb{Z}$ são da forma $J/m\mathbb{Z}$, onde $J$ é um ideal que contem $m\mathbb{Z}$.

Ou seja, os ideais são da forma $I = \langle n \rangle / \langle m \rangle, \langle n \rangle \subseteq \langle m \rangle$. Esta última inclusão implica que $n$ divide $m$.

Usando os corolários do Teorema de Isomorfismo, temos que os anéis quocientes de $\mathbb{Z}_m$ são da forma:

```math
\mathbb{Z}_m / I = \frac{(\mathbb{Z}/\langle m \rangle)}{\langle n \rangle / \langle m \rangle} \cong \mathbb{Z}/\langle n \rangle = \mathbb{Z}_n
```

Exemplo: $m=6$. Como os divisores de 6 são 1, 2, 3, 6, os ideais de $\mathbb{Z}_{6}$ são:

- $\langle 1 \rangle / \langle 6 \rangle = \mathbb{Z}/\langle 6 \rangle = \mathbb{Z}_6$
- $\langle 2 \rangle / \langle 6 \rangle = \\{\overline{0}, \overline{2}, \overline{4} \\} = \langle \overline{2} \rangle$
- $\langle 3 \rangle / \langle 6 \rangle = \\{\overline{0}, \overline{3} \\} = \langle \overline{3} \rangle$
- $\langle 6 \rangle / \langle 6 \rangle = \\{\overline{0} \\} = \langle \overline{0} \rangle$

Portanto, os quocientes de $\mathbb{Z}_6$ são:

- $\frac{(\mathbb{Z}/\langle 6 \rangle)}{\langle 2 \rangle / \langle 6 \rangle} \cong \mathbb{Z}_2$
- $\frac{(\mathbb{Z}/\langle 6 \rangle)}{\langle 3 \rangle / \langle 6 \rangle} \cong \mathbb{Z}_3$
- $\frac{(\mathbb{Z}/\langle 6 \rangle)}{\langle 6 \rangle / \langle 6 \rangle} \cong \mathbb{Z}_6$

</details>
