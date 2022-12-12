# Exercícios de Revisão da P2

1. Sejam $f(x) \in \mathbb{Z}[x]$ e $k \in \mathbb{Z}$: <br>
    a. Mostre que $f(x)$ é irredutível em $\mathbb{Q}[x]$ se, e somente se, $f(x + k)$ é irredutível em $\mathbb{Q}[x]$ <br>
    b. Mostre que $x^4 + x^3 + x^2 + x + 1$ é irredutível em $\mathbb{Q}[x]$

2. Seja $p \in \mathbb{N}$. Mostre que $\Phi_p(x) := 1+x+\cdots + x^{p-1}$ é irredutível em $\mathbb{Q}[x]$
3. $x^4 + x^2 + x + 1$ é irredutível em $\mathbb{Q}[x]$?
4. Seja $n \in \mathbb{N}$ qualquer. Dê um exemplo de um polinômio de grau $n$ em $\mathbb{Z}_3[x]$ sem raízes em $\mathbb{Z}_3$


<br>
<br>

# Soluções

## Exercício 1.a

Se $f(x)$ é irredutível para $x \in \mathbb{Z}$, então $f(x)$ é irredutível para todo elemento $a \in \mathbb{Z}$, incluindo $(x + k) \in \mathbb{Z}$.

<br>
<br>

## Exercício 1.b

Seja $f(x) = x^4 + x^3 + x^2 + x + 1$.

Suponha que $f(x)$ é redutível. Assim, caímos em dois casos: `(a)` há um fator de grau 3 e outro de grau 1; ou `(b)` há dois fatores de grau 2.

`(a)` $f(x) = (x + a)(x^3 + bx^2 + cx + d)$. Logo, $-a \in \mathbb{Q}$ é raiz de $f(x)$. Então, de acordo com o teorema visto em aula, $f(x)$ tem que ter uma raiz $m \in \mathbb{Z}$ que divide $a_0$. As possibilidades são $\pm 1$, porém $f(1) \neq 0$ e $f(-1) \neq 0$. Portanto, este caso não é possível.

`(b)` $f(x) = (x^2 + ax + b)(x^2 + cx + d) = x^4 + (a+c)x^3 + (ac + b + d)x^2 + (bc + ad)x + bd$. Assim, temos que:

1. $a + c = 1$
2. $ac + b + d = 1$
3. $bc + ad = 1$
4. $bd = 1$

Com `4.`, $b = d = \pm 1$.

`I.` Se $b = d = -1$, então, em `3.` temos $bc + ad = 1 \rightarrow a + c = -1$, uma contradição com `1.`. <br>
`II.` Se $b = d = 1$, então, manipulando `1.` e `2.`, descobrimos que $c = -1/a$ e $a^2 - a - 1 = 0$.

Apelando para os métodos do ensino médio, a solução para $a^2 - a - 1$ é:

```math
a = \frac{1 \pm \sqrt{5}}{2} \notin \mathbb{Q}
```

Portanto, $f(x)$ é irredutível sobre $\mathbb{Q}$.

<br>
<br>

## Exercício 2

A prova será feita usando o **critério de Eisenstein**.

Seja $\Phi_p(x) := 1+x+\cdots + x^{p-1}$.

Suponha que $\exists p \in \mathbb{Z}$ primo que satisfaça o critério para $\Phi_p(x), \forall x$.

E temos que $\Phi_{p}(x)$ é irredutível em $\mathbb{Q}[x]$ se, e somente se, $\Phi_{p}(x+1)$ irredutível em $\mathbb{Q}[x]$.

Pelo binômio de Newton, $\Phi_{p}(x+1) = x^{p-1} + k_{p-2}x^{p-2} + \cdots + k_{1}x + p$. Logo, $p$ divide $k_{p-2}, ..., k_{1}$ (pelo binômio de Newton), mas não divide $k_{p-1} = 1$ e $p^2$ não divide $p$, satisfazendo o critério de Eisenstein.

Como $\Phi_{p}(x+1)$ é irredutível em $\mathbb{Q}[x]$, então $\Phi_{p}(x)$ é irredutível em $\mathbb{Q}[x]$, Q.E.D.



<br>
<br>

## Exercício 3

Seja $f(x) = x^4 + x^2 + x + 1$.

Suponha que $f(x)$ é redutível em $\mathbb{Q}[x]$. Assim, $f(x)$ também seria redutível em $\mathbb{Z}[x]$. Logo, temos dois casos: `(a)` $f(x)$ tem um fator de grau 1 e outro de grau 3; ou `(b)` tem 2 fatores de grau 2.

Em `(a)`, pelo fato de ter que dividir $a_0$ em $\mathbb{Z}$, as únicas possibilidades são $x = \pm 1$. Porém, nenhuma delas são raízes de $f(x)$.

Em `(b)`, temos $f(x) = (x^2 + ax + b)(x^2 + cx + d) = x^4 + (a+c)x^3 + (ac + b + d)x^2 + (bc + ad)x + bd$.

Logo,

1. $a + c = 0$
2. $ac + b + d = 1$
3. $bc + ad = 1$
4. $bd = 1$

Considerando o `4.`, $b = d = \pm 1$. Assim, voltando a atenção para `3.`, temos $(bc + ad) = b(c + a) = 1$.

Se $b = d = 1$, então $b(c + a) = c + a = 1$, contradizendo `1.`. Se $b = d = -1$, então $c + a = -1$, também contradizendo `1.`. Logo, chegamos em uma contradição e, portanto, $f(x)$ não pode ser redutível em $\mathbb{Q}[x]$.

De fato, é possível verificar que não há raízes reais para $f(x)$ (symbolab):

![image](https://user-images.githubusercontent.com/23441506/206942274-da82a6c4-e7bd-4f1c-a74f-9ace06a423be.png)

<br>
<br>

## Exercício 4

Seja $f(x) = x^n + 2x + 2$.

- Para $x = 0$ ou $x = 1$, $f(x) = 2$
- Para $x = 2, f(x) = 2^n$. E $2^n \neq 0, \forall n \in \mathbb{N}$ em $\mathbb{Z}_3$

$2^n$ não é um múltiplo de 3 porque o único fator inteiro positivo de 2 é 1 e o próprio 2.

Assim, $f(x) \neq 0$ para todo $x$ e $n$.
