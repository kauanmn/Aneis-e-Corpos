# Resumo dos teoremas de polinômios

<br>

## 💡 Equivalências

- $R$ anel $\rightarrow R[x]$ anel
- $R$ comutativo $\rightarrow R[x]$ comutativo
- $R$ tem 1 $\rightarrow R[x]$ tem unidade
- $D$ d.i. $\rightarrow D[x]$ d.i.
- $F$ corpo $\rightarrow F[x]$ é um domínio de ideais principais (DIP)

<br>
<br>

## 💡 Algoritmo da Divisão

```math
f(x) = q(x)g(x) + r(x)
```

- $q(x), r(x)$ únicos
- $\text{deg}(r) < \text{deg}(f)$ ou $r(x) = 0$

<br>
<br>

## 💡 Teorema do Fator

```math
\begin{aligned}
  \alpha \text{ raiz } &\iff (x - \alpha) \text{ fator} \\
  &\iff \phi_{\alpha}(f) = 0
\end{aligned}
```

<br>
<br>

## 💡 Teorema do Resto

O resto da divisão de $f(x)$ por $(x-\alpha)$ é $f(\alpha)$

<br>
<br>

## 💡 Máximo de raízes

Se $\text{deg}(f(x)) = n$

então $f(x)$ tem, no máximo, $n$ raízes (contando multiplicidades).

<br>
<br>

## 💡 Redutibilidade de grau 2, 3

Sejam $f(x)$ de grau 2 ou 3 e $F$ corpo.

$f(x)$ REDUTÍVEL sobre $F \iff f(x)$ tem RAIZ em $F$

<br>
<br>

## 💡 Redutibilidade sobre $\mathbb{Z}$ e $Q$

- $f(x)$ REDUTÍVEL sobre $Q[x] \rightarrow f(x)$ REDUTÍVEL sobre $\mathbb{Z}[x]$
- $f(x)$ IRREDUTÍVEL sobre $\mathbb{Z}[x] \rightarrow f(x)$ IRREDUTÍVEL sobre $Q[x]$

<br>
<br>

## 💡 Zero em $Q$ e $\mathbb{Z}$

Seja $f(x) = x^n + a_{n-1}x^{n-1} + \cdots + a_{1}x + a_0 \in \mathbb{Z}[x], a_0 \neq 0$.

Se $f(x)$ tem raiz $\alpha \in Q$

Então $f(x)$ tem RAIZ $m \in \mathbb{Z}$ e $m \mid a_0$

<br>
<br>

## 💡 Teorema de Irredutibilidade $\text{mod } p$

Sejam

- $p \in \mathbb{N}$ primo
- $f(x) \in \mathbb{Z}[x]$
- $\text{deg}(f(x)) \ge 1$

Se:

- $\overline{f_p}(x)$ irredutível em $\mathbb{Z}_p[x]$
- $\text{deg}(f(x)) = \text{deg}(\overline{f_p}(x))$

Então $f(x)$ é IRREDUTÍVEL sobre $Q[x]$

<br>
<br>

## 💡 Critério de Eisenstein

Para $f(x) \in \mathbb{Z}[x]$, se existe um $p$ primo que:

1. $p \nmid a_n$
2. $p \mid a_{n-1}, \cdots, p \mid a_1, p \mid a_0$
3. $p^2 \nmid a_0$

Então $f(x)$ IRREDUTÍVEL sobre $Q[x]$

<br>
<br>

## 💡 $\langle p(x) \rangle$ maximal

```math
\begin{aligned}
    \langle p(x) \rangle \text{ maximal } &\iff p(x) \text{ irredutivel}\\
    & \iff F[x]/\langle p(x) \rangle \text{ corpo}
\end{aligned}
```

<br>
<br>

## 💡 Fatoração única

$f(x)$ (não constante) pode ser escrito como produto finito de polinômios irredutíveis em $F[x]$ (corpo).
