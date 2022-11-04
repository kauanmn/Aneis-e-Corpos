# Teoremas

Página com resultados importantes, para serem usados em provas etc.


<br>


## Conteúdo

**PARTE 1 - ANEIS**

- Anel
- Anel Comutativo
- Identidade
- Anel com Identidade
- Elemento Invertível
- Anel com Divisão
- Corpo
- Divisores de Zero
- Domínio Inteiro
- Característica
- Subanel

<br>

**PARTE 2 - HOMOMORFISMO E IDEAIS**

- Homomorfismo de anéis
- Homomorfismo de anéis com unidade
- Tipos de Homomorfismos
- Imagem
- Kernel
- Ideal
- Ideal Gerado
- Ideais Próprios e Triviais
- Ideal Maximal
- Ideal Primo

<br>

**PARTE 3 - ANÉIS QUOCIENTES**

- Equivalência
- Classe
- Classes de Equivalência
- Anel Quociente
- Projeção Canônica

<br>


# PARTE 1 - ANEIS

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

# PARTE 2 - HOMOMORFISMO DE ANÉIS

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

O conjunto de classes de equivalência $A/I$ tem estrutura de anel, chamado de **ANEL QUOCIENTE** de $A$ po $I$



<br>

### 💡 Proposição

Seja $\phi : A \rightarrow B$ um homomorfismo de anéis, então:

1. $\text{ker } \phi$ é um ideal de $A$
2. $\phi$ é um homomorfismo $\iff \text{ker } \phi = \\{ 0_{A} \\}$



<br>

### 💡 Proposição

Seja $\phi : A \rightarrow B$ um homomorfismo de anéis, então:

1. Se $A_{1}$ é um subanel de $A$, então $\phi (A_{1}) é um subanel de $B$$
2. 
