# Glossário

Página com as definições e termos usados na disciplina.


<br>


## Conteúdo

**PARTE 1 - ANEIS**

- [Anel](#anel)
- [Anel Comutativo](#anel-comutativo)
- [Identidade](#identidade)
- [Anel com Identidade](#anel-com-identidade)
- [Elemento Invertível](#elemento-invertível)
- [Anel com Divisão](#anel-com-divisão)
- [Corpo](#corpo)
- [Divisores de Zero](#divisores-de-zero)
- [Domínio Inteiro](#domínio-inteiro)
- [Característica](#característica)
- [Subanel](#subanel)

<br>

**PARTE 2 - HOMOMORFISMO E IDEAIS**

- [Homomorfismo de anéis](#homomorfismo-de-anéis)
- [Homomorfismo de anéis com unidade](#homomorfismo-de-anéis-com-unidade)
- [Tipos de Homomorfismos](#tipos-de-homomorfismos)
- [Imagem](#imagem)
- [Kernel](#kernel)
- [Ideal](#ideal)
- [Ideal Gerado](#ideal-gerado)
- [Ideais Próprios e Triviais](#ideais-próprios-e-triviais)
- [Ideal Maximal](#ideal-maximal)
- [Ideal Primo](#ideal-primo)

<br>

**PARTE 3 - ANÉIS QUOCIENTES**

- [Equivalência](#equivalência)
- [Classe](#classe)
- [Classes de Equivalência](#classes-de-equivalência)
- [Anel Quociente](#anel-quociente)
- [Projeção Canônica](#projeção-canônica)
- [Corpo de Quocientes](#corpo-de-quocientes)

<br>

# PARTE 1 - ANÉIS

## Anel

💡 O **ANEL** é um conjunto não vazio $R$, munido das operações binárias $+$ e $\cdot$ tais que $\forall a,b,c \in R$, valem as seguintes propriedades:

<br>

| Propriedade                     | Descrição                                                   |
|---------------------------------|-------------------------------------------------------------|
| Associatividade (adição)        | $(a+b)+c = a+(b+c)$                                         |
| Comutatividade (adição)         | $a + b = b + a$                                             |
| Elemento neutro                 | $\exists 0 \in R$ tal que $a + 0 = 0+a=a$                   |
| Elemento inverso                | $\forall a \in R, \exists(-a) \in R$ tal que $a + (-a) = 0$ |
| Associatividade (multiplicação) | $a(bc) = (ab)c$                                             |
| Distributividade                | $a \cdot (b+c) = ab+ac$ <br> $(a+b) \cdot c = ac+bc$        |


<br>


## Anel comutativo

💡 O **ANEL COMUTATIVO** é um anel que possui a comutatividade para a multiplicação: $a \cdot b = b \cdot a$


<br>


## Identidade

💡 A **IDENTIDADE** de um anel $A$ é um elemento $1_{A}$, diferente de zero, que se comporta como elemento neutro da multiplicação: $a \cdot 1_{A} = a = 1_{A} \cdot a, \forall a \in A$.


<br>


## Anel com Identidade

💡 Se um anel $A$ possui identidade, então ele é um **ANEL COM IDENTIDADE**.


<br>


## Elemento invertível

Seja $A$ um anel com identidade (possui $1_{A}$) e $a \in A$.

💡 Se existe um elemento $a^{-1}$ tal que $a \cdot a^{-1} = 1_{A} = a^{-1} \dot a$, então $a$ é um **ELEMENTO INVERTÍVEL**.


<br>


## Anel com divisão

Seja $A$ um anel com identidade (possui $1_{A}$).

💡 Se todos elementos $\neq 0$ de $A$ são invertíveis, então $A$ é um **ANEL COM DIVISÃO**.


<br>


## Corpo

Seja um anel $A$ comutativo com unidade (possui $1_{A}$).

💡 Se todo elemento $\neq 0$ de $A$ é invertível, então $A$ é um **CORPO**.

Em outras palavras, se $A$ é um anel com divisão comutativo, então $A$ é um corpo.


<br>


## Divisores de zero

Seja $R$ um anel e $a,b \in R$ com $a,b \neq 0$.

💡 Se $a,b$ são tais que $a \cdot b = 0$, então $a$ e $b$ são **DIVISORES DE ZERO**.


<br>


## Domínio inteiro

Seja $R$ um anel comutativo com $1$.

💡 Se $R$ não tem divisores de zero, então $R$ é um **DOMÍNIO INTEIRO**.


<br>


## Característica

💡 A **CARACTERÍSTICA** de um anel $R$ é o menor $n \in \mathbb{Z}, n \gt 0$ tal que $n \cdot x = 0, \forall x \in R$. Escrevemos $\text{char}(R) = n$

Se tal inteiro não existe, dizemos que a característica de $R$ é $0$

Obs.: $n \cdot x = (x + \cdots + x) = 0$


<br>


## Subanel

Sejam $R$ um anel e $S \subseteq R$

💡 Se $S$ é um anel com as mesmas operações de $R$, então $S$ é um **SUBANEL** de $R$


<br>


# PARTE 2 - HOMOMORFISMO E IDEAIS

## Homomorfismo de anéis

Sejam $A,B$ anéis.

💡 Uma função $\phi: A \rightarrow B$ é chamada de **HOMOMORFISMO** de anéis se, $\forall a,b \in A$, se vale que:

```math
\displaylines{
  & \phi (a+b) = \phi (a) + \phi (b) \\
  & \phi (a \cdot b ) = \phi (a) \cdot \phi (b)
}
```


<br>


## Homomorfismo de anéis com unidade

Sejam $A, B$ anéis com unidade e $\phi : A \rightarrow B$ um homomorfismo de anéis.

💡 Se $\phi (1_{A}) = 1_{B}$, então $\phi$ é um **HOMOMORFISMO DE ANEIS COM UNIDADE** (ou homomorfismo que preserva unidades).


<br>


## Tipos de homomorfismos

Sejam $A, B$ anéis e $\phi : A \rightarrow B$ um homomorfismo de anéis. Então, temos os seguintes tipos de homomorfismos:

<br>

| Tipo         | Propriedade                |
|--------------|----------------------------|
| Endomorfismo | $A = B$                    |
| Monomorfismo | $\phi$ é injetor           |
| Epimorfismo  | $\phi$ é sobrejetor        |
| Isomorfismo  | $\phi$ é bijetor           |
| Automorfismo | $\phi$ é bijetor e $A = B$ |

<br>

Seja $f:X \rightarrow Y$ uma função qualquer:

| Função    | Propriedade                                           |
|-----------|-------------------------------------------------------|
| Injetora  | Se $f(x) = f(x')$, então $x = x'$                     |
| Subjetora | $\forall y \in Y, \exists x \in X$ tal que $f(x) = y$ |
| Bijetora  | $f$ é uma função injetora E sobrejetora               |


<br>


## Imagem

Sejam $A,B$ anéis e $\phi : A \rightarrow B$ um homomorfismo de anéis.

💡 A **IMAGEM** de $\phi$ é o conjunto

```math
\text{Im } \phi = \{ b \in B \mid \exists a \in A \text{ tal que } \phi (a) = b \} \text{ ou }
```

```math
\text{Im } \phi = \{ \phi (a) \mid a \in A \}
```


<br>


## Kernel

Sejam $A,B$ anéis e $\phi : A \rightarrow B$ um homomorfismo de anéis.

💡 O **KERNEL** de $\phi$ é o conjunto

```math
\text{ker } \phi = \{ a \in A \mid \phi (a) = 0_{B} \}
```


<br>


## Ideal

Sejam $A$ um anel e $I$ um subconjunto $\neq \emptyset$ de $A$.

💡 Se $I$ é um grupo aditivo e, $\forall a \in A$ e $\forall r \in I$ tal que vale $ar, ra \in I$, então $I$ é um **IDEAL** de $A$.

Escrito de outra forma,
> Se $I$ é um subgrupo aditivo de $A$ não vazio e $aI = \\{ ar \mid r \in I \\} , Ia = \\{ ra \mid r \in I \\} \subseteq I$, então $I$ é um **IDEAL** de $A$


<br>


## Ideal Gerado

Sejam $R$ um anel comutativo com $1$ e $a \in R$.

💡 Se o conjunto \< $a$ \>  $= Ra = \\{ ra \mid r \in R \\}$ é um ideal de $R$, então \< $a$ \> é o **IDEAL PRINCIPAL GERADO POR $a$**

<br>

Sejam $R$ um anel comutativo com $1$ e $a_{1}, \cdots , a_{n} \in R$

💡 Se $I=$ \< $a_{1}, \cdots , a_{n}$ \> $= \\{ r_1 a_1 + \cdots + r_n a_n \mid r_i \in R \\}$ é um ideal de $R$, então $I$ é um **IDEAL GERADO POR** $a_{1}, \cdots , a_{n}$


<br>


## Ideais Próprios e Triviais

Seja $R$ um anel.

💡 O ideal $\{ 0 \}$ é chamado **IDEAL TRIVIAL** de $R$

💡 Se $I \triangleleft R$ tal que $I \subsetneq R$, $I$ é um **IDEAL PRÓPRIO** de $R$

💡 Se $I \triangleleft R$ que não é trivial ou próprio, então $I$ é um **IDEAL PRÓPRIO NÃO TRIVIAL**


<br>


## Ideal Maximal

Seja $R$ um anel e $M$ um ideal próprio de $R$ ( $M \subsetneq R$ ).

💡 Se, $\forall J$ ideal de $R$, vale que

```math
M \subseteq J \iff J = M \text{ ou } J = R
```

então $M$ é um **IDEAL MAXIMAL**.


<br>


## Ideal Primo

Seja $R$ um anel comutativo e $I$ um ideal próprio de $R$.

💡 Se $ab \in I$ e $a,b \in R$ implica que $a \in I$ ou $b \in I$, então $I$ é um **IDEAL PRIMO**.


<br>

# PARTE 3 - ANÉIS QUOCIENTES


## Equivalência

Sejam $A$ um anel, $I$ um ideal de $A$ e $a,b \in A$.

💡 A relação de **EQUIVALÊNCIA** é definida como segue:

```math
  a \sim b \iff a - b \in I
```

<br>

Esta relação possui as seguintes propriedades:

| Propriedade | Descrição                                    |
|-------------|----------------------------------------------|
| Reflexiva   | $a \sim a \in I$                             |
| Simétrica   | Se $a \sim b \in I$, então $b \sim a \in I$  |
| Transitiva  | Se $a \sim b$ e $b \sim c$, então $a \sim c$ |


<br>


## Classe

Sejam $A$ um anel, $I$ um ideal de $A$ e $a \in A$.

💡 Denotamos por $a + I$ a **CLASSE** de $a$. Isto é,

```math
  a + I = \{ a + b \mid b \in I \} \text{ ou}
```
``` math
a + I = \{ b \in A \mid a - b \in I \}
```


<br>


## Classes de Equivalência

Sejam $A$ um anel, $I$ um ideal de $A$ e $a \in A$.

💡 Denotamos por $A/I$ o conjunto das **CLASSES DE EQUIVALÊNCIA** de $A$ (pela relação $\sim$). Isto é,

```math
A/I = \{ a + I \mid a \in A \}
```


<br>


## Anel Quociente

Sejam $A$ um anel, $I$ um ideal de $A$ e $a \in A$.

💡  $A/I$ com as operações abaixo é um **ANEL QUOCIENTE** e possui estrutura de anel:

```math
(a + I) + (b + I) = (a + b) + I
```

```math
(a + I) \cdot (b + I) = (a \cdot b) + I
```


<br>


## Projeção Canônica

Sejam $A$ um anel e $I$ um ideal de $A$.

💡 A função $\Pi : A \rightarrow A/I$ definida por $\Phi (a) = a + I$ é chamada de **PROJEÇÃO CANÔNICA** e é um homomorfismo de anéis tal que:

- $\text{ker } \phi = I$
- $\text{Im }  \phi = A/I$



<br>


## Corpo de Quocientes

Seja um domínio inteiro $D$ e um corpo $F$.

💡 Se todo domínio inteiro $D$ pode ser "mergulhado" em um corpo $F$ tal que todo elemento de $F$ possa ser expressado como um quociente de dois elementos de $D$, então $F$ é um **CORPO DE QUOCIENTES** de $D$ (ou corpo de frações).

Para $[(a,b)], [(c,d)] \in F$, as equações

```math
\displaylines{
    [(a,b)] + [(c,d)] = [(ad+bc, bd)] \text{ e }\\
    [(a,b)] \cdot [(c,d)] = [(ac,bd)]
}
```

dão as operações bem-definidas de adição e multiplicação em $F$.
