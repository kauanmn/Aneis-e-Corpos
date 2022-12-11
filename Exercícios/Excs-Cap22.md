# A First Course in Abstract Algebra
**John B. Fraleigh**<br>

## Chapter 22 - Exercises

<br>

**In Exercises 1 through 4, find the sum and the product of the given polynomials in the given polynomial ring.**

### Exercise 1

$f(x) = 4x - 5, g(x) = 2x^2 - 4x + 2$ in $\mathbb{Z}_8[x]$














<br>

### Exercise 2

$f(x) = x + 1, g(x) = x + 1$ in $\mathbb{Z}_2[x]$














<br>

### Exercise 3

$f(x) = 2x^2 + 3x + 4, g(x) = 3x^2 + 2x + 3$ in $\mathbb{Z}_6[x]$














<br>

### Exercise 4

$f(x) = 2x^3 + 4x^2 + 3x + 2, g(x) = 3x^4 + 2x + 4$ in $\mathbb{Z}_5[x]$














<br>

### Exercise 5

How many polynomials are there of degree $\le 3$ in $\mathbb{Z}_2[x]$? (include 0).














<br>

### Exercise 6

How many polynomials are there of degree $\le 2$ in $\mathbb{Z}_5[x]$? (include 0).














<br>
<br>

**In Exercises 7 and 8, $F = E = \mathbb{C}$ in theorem 22.4. Compute for the indicated evaluation homomorphism:**

### Exercise 7

$\phi_2(x^2 + 3)$














<br>

### Exercise 8

$\phi_{i}(2x^3 - x^2 + 3x + 2)$














<br>
<br>

**In Exercises 9 through 11, $F = E = \mathbb{Z}_7$ in Theorem 22.4. Compute for the indicated evaluation homomorphism.**

### Exercise 9

$\phi_{3}[(x^4 + 2x)(x^3 - 3x^2 + 3)]$














<br>

### Exercise 10

$\phi_{5}[(x^3 + 2)(4x^2 + 3)(x^7 + 3x^2 + 1)]$














<br>

### Exercise 11

$\phi_{4}(3x^{106} + 5x^{99} + 2x^{53})$














<br>
<br>

**In Exercises 12 through 15, finda all zeros in the indicated finite field of the given polynomial with coefficients in that field. [Hint: one way is simply to try all candidates]**

### Exercise 12

$x^2 + 1$ in $\mathbb{Z}_2$














<br>

### Exercise 13

$x^3 + 2x + 2$ in $\mathbb{Z}_7$














<br>

### Exercise 14

$x^5 + 3x^3 + x^2 + 2x$ in $\mathbb{Z}_5$














<br>

### Exercise 15

$f(x)g(x)$ where $f(x) = x^3 + 2x^2 + 5$ and $g(x) = 3x^2 + 2x$ in $\mathbb{Z}_7$














<br>
<br>

# Solutions

<br>

## Exercise 1

$f(x) + g(x) = 2x^2 + 5$

$f(x)g(x) = 6x^2 + 4x + 6$

---

<br>

## Exercise 2

$f(x) + g(x) = 0$

$f(x)g(x) = x^2 + 1$

---

<br>

## Exercise 3

$f(x) + g(x) = 5x^2 + 5x + 1$

$f(x)g(x) = x^3 + 5x$

---

<br>

## Exercise 4

$f(x) + g(x) = 3x^4 + 2x^3 + 4x^2 + 1$

$f(x)g(x) = x^7 + 2x^6 + 4x^5 + x^3 + 2x^2 + x + 3$

---

<br>

## Exercise 5

Polynomials in $\mathbb{Z}_2[x]$ with degree $\le 3$ have the following form:

$a_{3}x^3 + a_{2}x^2 + a_{1}x + a_{0}$

Each coefficient $a_i$ has 2 possibilities: 0, 1. So, we have $2 \cdot 2 \cdot 2 \cdot 2 = 16$ possible polynomials.

---

<br>

## Exercise 6

Polynomials in $\mathbb{Z}_5[x]$ with degree $\le 2$ have the following form:

$a_{2}x^2 + a_{1}x + a_{0}$

Each coefficient $a_i$ has 5 possibilities: 0, 1, 2, 3, 4. So, we have $5 \cdot 5 \cdot 5 = 125$ possible polynomials.

---

<br>

## Exercise 7

$\phi_2(x^2 + 3) = (2^2 + 3) = 7$

---

<br>

## Exercise 8

$\phi_{i}(2x^3 - x^2 + 3x + 2) = 2i^3 - i^2 + 3i + 2 = i + 3$

---

<br>

## Exercise 9

```math
\phi_{3}[(x^4 + 2x)(x^3 - 3x^2 + 3)] = (3^4 + 2*3)(3^3 - 3*3^2 + 3) = 2
```

---

<br>

## Exercise 10

```math
\phi_{5}[(x^3 + 2)(4x^2 + 3)(x^7 + 3x^2 + 1)] = (5^3 + 2)(4*5^2 + 3)(5^7 + 3*5^2 + 1) = 6
```

---

<br>

## Exercise 11

```math
\phi_{4}(3x^{106} + 5x^{99} + 2x^{53}) = (3*4^{106} + 5*4^{99} + 2*4^{53}) = 0
```
(I used `pow()` python's function to calculate this :D)

---

<br>

## Exercise 12

| $x$ | $x^2 + 1$ |
|-----|-----------|
| 0   | 1         |
| 1   | 0         |

Zeroes: $\\{ 1 \\}$

---

<br>

## Exercise 13

| $x$ | $x^3 + 2x + 2$ |
|-----|----------------|
| 0   | 2              |
| 1   | 5              |
| 2   | 0              |
| 3   | 0              |
| 4   | 4              |
| 5   | 4              |
| 6   | 6              |

Zeroes: $\\{ 2, 3 \\}$

---

<br>

## Exercise 14

| $x$ | $x^5 + 3x^3 + x^2 + 2x$ |
|-----|-------------------------|
| 0   | 0                       |
| 1   | 2                       |
| 2   | 4                       |
| 3   | 4                       |
| 4   | 0                       |

Zeroes: $\\{ 0, 4 \\}$

---

<br>

## Exercise 15

| $x$ | $f(x)g(x)$ |
|-----|------------|
| 0   | 0          |
| 1   | 5          |
| 2   | 0          |
| 3   | 5          |
| 4   | 0          |
| 5   | 5          |
| 6   | 6          |

Zeroes: $\\{ 0, 2, 4 \\}$

---

<br>

## Exercise 16

---

<br>

## Exercise 17

---

<br>

## Exercise 18

---

<br>

## Exercise 19

---

<br>

## Exercise 20

---

<br>

## Exercise 21

---

<br>

## Exercise 22

---

<br>

## Exercise 23

---

<br>

## Exercise 24

---

<br>

## Exercise 25

---

<br>

## Exercise 26

---

<br>

## Exercise 27

---

<br>

## Exercise 28

---

<br>

## Exercise 29

---

<br>

## Exercise 30

---

<br>

## Exercise 31
