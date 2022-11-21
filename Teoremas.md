# Teoremas

Página com resultados importantes, para serem usados em provas etc.


<br>


### 💡 Proposição

Sejam $R$ um anel e $a,b,c \in R$, então:

1. $a \cdot 0 = 0 \cdot a = 0$
2. $a(-b) = (-a)b = -ab$
3. $(-a)(-b) = ab$
4. $a(b-c)=ab-ac$
5. $(b-c)a=ba-ca$
6. Caso $R$ tenha unidade, então:

    a. $(-1)a = -a$ <br>
    b. $(-1)(-1)=1$

<br>

### 💡 Proposição

Seja $(A, +, \cdot)$ um anel com unidade. Então $A^x$ é um grupo.

$A^x = \\{ x \in A \mid x \text { invertivel} \\}$

<br>

### 💡 Proposição

Seja $A$ um anel, então:

1. $(a^{n})^{m} = a^{n \cdot m}, \forall n,m \ge 1 \in \mathbb{N}$
2. Se $A$ é um anel com 1 e $b \in A^x$, então $(b^n)^m = b^{n \cdot m}, \forall n,m \in \mathbb{Z}$
3. Se $A$ é um anel comutativo, então $(ab)^n = a^{n}b^{m}, \forall n,m \in \mathbb{N} \setminus \\{ 0 \\}$

<br>

### 💡 Proposição

No anel $\mathbb{Z}_{n}$, os divisores de zero são os elementos que não são primos relativos com $n$

<br>

### Corolário

Se $p$ é primo, então $\mathbb{Z}_{p}$ não tem divisores de zero.

<br>

### 💡 Proposição

Seja $R$ um domínio de integridade. Se $a,b,c \in R$ e $a \neq 0$ são tais que $ab = ac$, então $b=c$

<br>

### ⚠️ TEOREMA ⚠️

Todo domínio de integridade finito é um corpo

<br>

### Corolário

Todo $\mathbb{Z}_{p}$ com $p$ primo é um corpo

<br>

### ⚠️ TEOREMA ⚠️

Se $R$ é um anel com unidade, então $\text{char}(R)=n, n \gt 0 \iff \\{ n$ é o menor inteiro positivo tal que $n-1 = 0\\}$

<br>

### ⚠️ TEOREMA ⚠️

A característica de um domínio de integridade é zero ou primo

<br>

### 💡 Proposição

(Teste para subaneis) Sejam $R$ um anel e $S \subseteq R$ tal que $S \neq \emptyset$. $S$ é um subanel de $R$ se vale que:

1. $ab \in S$
2. $a-b \in S$

$\forall a,b \in S$

<br>

### 💡 Proposição

Se $\phi : A \rightarrow B$ é um homomorfismo de anéis, então:

1. $\phi (0_{A}) = 0_{B}$
2. $\phi (-a) = -\phi(a)$
3. Se $A$ e $B$ têm unidade, não necessariamente vale que $\phi (1_{A}) = 1_{B}$

<br>

### 💡 Proposição

Sejam $A$ e $B$ anéis com identidade e $\phi : A \rightarrow B$ um homomorfismo de anéis. Então:

1. Se $B$ é um domínio de integridade, $\phi (1_{A}) = 1_{B}$
2. Se $\phi$ é um homomorfismo sobrejetor, $\phi (1_{A}) = 1_{B}$



<br>

### 💡 Proposição

O conjunto de classes de equivalência $A/I$ tem estrutura de anel, chamado de **ANEL QUOCIENTE** de $A$ por $I$



<br>

### 💡 Proposição

Seja $\phi : A \rightarrow B$ um homomorfismo de anéis, então:

1. $\text{ker } \phi$ é um ideal de $A$
2. $\phi$ é um homomorfismo $\iff \text{ker } \phi = \\{ 0_{A} \\}$



<br>

### 💡 Proposição

Seja $\phi : A \rightarrow B$ um homomorfismo de anéis, então:

1. Se $A_{1}$ é um subanel de $A$, então $\phi (A_{1})$ é um subanel de $B$
2. Se $B_{1}$ é um subanel de $B$, então $\phi ^ {-1} (B_1)$ é um subanel de $A$
3. Se $I$ é um ideal de $A$, então $\phi (I)$ é um ideal de $\text{Im } \phi$
4. Se $I \lhd B$, então $\phi ^ {-1}(I) \lhd A$ E $\text{ker } \phi \subseteq \phi ^ {-1}(I)$
5. Se $I \lhd A$ e $\text{ker } \phi \subseteq I$, então $\phi^{-1}(\phi(I)) = I$


<br>

### ⚠️ 1º TEOREMA DO ISOMORFISMO ⚠️

Seja $\phi : A \rightarrow B$ um homomorfismo de anéis, então

```math
\displaylines{
    \phi^{*} : A/\text{ker } \phi \rightarrow \text{Im } \phi \\
    a + \text{ker } \phi \mapsto \phi(a)
}
```

é um isomorfismo de anéis, i.e.,

```math
    A / \text{ker } \phi \cong \text{Im } \phi
```


<br>

### Corolário

Se $\phi : A \rightarrow B$ é um epimorfismo de anéis, então $A / \text{ker } \phi \cong B$


<br>

### Corolário

Seja $\phi : A \rightarrow B$ um epimorfismo de anéis. Então

```math
    A/\phi^{-1}(J) \cong B/J
```



<br>

### Corolário

Sejam $A$ um anel e $I,J \lhd A$ tais que $I \subseteq J$. Então

```math
A/J \cong (A/I) / (J/I)
```



<br>


### ⚠️ TEOREMA DA CORRESPONDÊNCIA ⚠️

Seja $\phi : A \rightarrow B$ um epimorfismo de anéis.

Então, existe uma correspondência bijetora entre os ideais de $A$ e $B$ que contêm $\text{ker } \phi$.



<br>

### Corolário

Sejam $A$ um anel e $I \lhd A$.

Então existe uma correspondência bijetora entre os ideaiss de $A/I$ e os ideais de $A$ que contém $I$



<br>


### ⚠️ 2º TEOREMA DO ISOMORFISMO ⚠️

Sejam $A$ um anel, $S$ um subanel de $A$ e $I \lhd A$. Então:

1. $(S \cap I) \lhd A$
2. $S+I = \\{ s + a \mid s \in S \land a \in I \\}$ é um subanel de $A$, que contém $I$ e $I \lhd (s + I)$
3. $S/S \cap I \cong (S+I)/I$



<br>

### ⚠️ TEOREMA ⚠️

Seja $R$ um anel comutativo com unidade.

Então $I$ é um ideal maximal de $R \iff R/I$ é um corpo.



<br>

### Corolário

Seja $R$ um anel comutativo com unidade é um corpo $\iff$ os únicos ideais de $R$ são $\\{ 0 \\}$ e $R$ (não há ideais próprios não nulos)



<br>

### ⚠️ TEOREMA ⚠️

Sejam $R$ um anel comutativo com $1$ e $I$ um ideal próprio de $R$. Então,

```math
    I \text { primo} \iff R/I \text{ domínio de integridade}
```



<br>

### Corolário

Seja $R$ um anel comutativo com 1. Então,

Todo ideal maximal é um ideal primo.



<br>

### 💡 Proposição

Se $F$ é um corpo, então:

1. Se $\text{Char }(F) = p, p \text{ primo}$, então $F$ contém um subcorpo isomorfo a $\mathbb{Z}_p$
2. Se $\text{Char }(F) = 0$, então $F$ contém um subcorpo isomorfo a $\mathbb{Q}$ (racionais)



<br>

### Lema

A função

```math
\displaylines{
    i:D \rightarrow F \\
    a \mapsto [(a,1)]
}
```

é um monomorfismo de anéis. Portanto, $D \cong i(D) \subseteq F$



<br>

### ⚠️ TEOREMA ⚠️

Todo domínio inteiro $D$ pode ser "mergulhado" em um corpo $F$ tal que todo elemento de $F$ pode ser escrito como um quociente de elementos de $D$ (tal corpo é chamado de **CORPO DE QUOCIENTES** de $D$)



<br>

### ⚠️ TEOREMA ⚠️

Sejam $D$ um domínio de integridade, $F$ um corpo de frações de $D$ e $L$ um corpo tal que $D \subseteq L$.

Então, existe um monomorfismo $\psi : F \rightarrow L$ tal que

```math
\displaylines{
    \psi(a)=a, \forall a \in D \\
    (\psi/D = \text{ id}_{D})
}
```

Além disso, $\psi(F)$ é isomorfo a um subcorpo de $F$



<br>

### Corolário

Sejam $D$ um domínio de integridade e $F_1, F_2$ corpos de frações de $D$. Então,

```math
F_1 \cong F_2
```




<br>

# Anéis de Polinômios

<br>

### ⚠️ TEOREMA ⚠️

- Se $R$ é um anel, então $R[x]$ é um anel
- Se $R$ é comutativo, então $R[x]$ é comutativo
- Se $R$ tem 1, então $R[x]$ tem unidade



<br>

### 💡 Proposição

Se $D$ é um domínio de integridade, então $D[x]$ é um domínio de integridade.



<br>

### ⚠️ **ALGORITMO DA DIVISÃO EM** $F[x]$ ⚠️



Sejam $F$ um corpo, $f(x),g(x) \in F[x]$ tais que $g(x) \neq 0$.

Então existem únicos $q(x),r(x)$ tais que:

```math
f(x) = q(x) \cdot g(x) + r(x)
```

onde $r(x) = 0$ ou $\text{deg}(r) < \text{deg}(g)$



<br>

### ⚠️ TEOREMA DO FATOR ⚠️

Sejam $F$ um corpo e $\alpha \in F$. Então $\alpha$ é uma raiz de $f(x) \in F[x]$ se, e somente se, $(x-\alpha)$ é um fator de $f(x)$ em $F[x]$.

```math
\displaylines{
    \phi_{\alpha} : F[x] \rightarrow F \\
    \alpha \text{ raiz de } f \Leftrightarrow \phi_{\alpha}(f) = 0
}
```



<br>

### ⚠️ TEOREMA DO RESTO ⚠️

Sejam $F$ um corpo, $\alpha \in F$ e $f(x) \in F[x], f(x) \neq 0$.

Então, o resto da divisão $f(x)$ por $(x-\alpha)$ é $f(\alpha)$.



<br>

### Corolário

Sejam $F$ um corpo, $\alpha \in F$ e $f(x) \in F[x], f(x) \neq 0$.

Se $\text{deg}(f) = n$, então $f(x)$ tem, no máximo, $n$ raízes em $F$ (contando as multiplicidades).



<br>

### ⚠️ TEOREMA ⚠️

Se $F$ é um corpo, então $F[x]$ é um domínio de ideais principais.
