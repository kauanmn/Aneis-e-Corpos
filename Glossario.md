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

**PARTE 2 - HOMOMORFISMO DE ANEIS**

- [Homomorfismo de anéis](#homomorfismo-de-anéis)
- [Homomorfismo de anéis com unidade](#homomorfismo-de-anéis-com-unidade)
- [Tipos de Homomorfismos](#tipos-de-homomorfismos)
- [Ideal](#ideal)
- [Ideais Gerados](#ideais-gerados)


<br>


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


## Ideal

Sejam $A$ um anel e $I$ um subconjunto $\neq \emptyset$ de $A$.

💡 Se $I$ é um grupo aditivo e, $\forall a \in A$ e $\forall r \in I$ tal que vale $ar, ra \in I$, então $I$ é um **IDEAL** de $A$.

Escrito de outra forma,
> Se $I$ é um subgrupo aditivo de $A$ não vazio e $aI = \\{ ar / r \in I \\} , Ia = \\{ ra / r \in I \\} \subseteq I$, então $I$ é um **IDEAL** de $A$


<br>


## Ideais Gerados

Sejam $R$ um anel comutativo com $1$ e $a \in R$.

💡 Se o conjunto \< $a$ \>  $= Ra = \\{ ra / r \in R \\}$ é um ideal de $R$, então \< $a$ \> é o **IDEAL PRINCIPAL GERADO POR $a$**

<br>

Sejam $R$ um anel comutativo com $1$ e $a_{1}, \cdots , a_{n} \in R$

💡 Se $I=$ \< $a_{1}, \cdots , a_{n}$ \> $= \\{ r_1 a_1 + \cdots + r_n a_n / r_i \in R \\}$ é um ideal de $R$, então $I$ é um **IDEAL GERADO POR** $a_{1}, \cdots , a_{n}$
