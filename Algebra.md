## Polynomials:

- **Zero of Factor:** For a polynomial $p(x)$, $x=a$ is a factor of the polynomial if $p(a)=0$.
- **Remainder Theorem:** The remainder of $\dfrac{p(x)}{(x-a)}$ is $p(a)$.

- **Important Identities:**
  - $(a+b)^2=a^2+2ab+b^2$
  - $(a-b)^2=a^2-2ab+b^2$
  - $a^2-b^2=(a+b)(a-b)$
  - $a^2+b^2=(a+b)^2-2ab$
  - $(a+b+c)^2=a^2+b^2+c^2+2ab+2bc+2ac$
  - $(a-b-c)^2=a^2+b^2+c^2-2ab+2bc-2ac$
  - $(x+a)(x+b)=x^2+x(a+b)+ab$
  - $(a+b)^3=a^3+3a^2b+3ab^2+b^3=a^3+b^3+3ab(a+b)$
  - $(a-b)^3=a^3-3a^2b+3ab^2-b^3=a^3-b^3-3ab(a-b)$
  - $a^3+b^3=(a+b)(a^2-ab+b^2)=(a+b)^3-3ab(a+b)$
  - $a^3-b^3=(a-b)(a^2+ab+b^2)=(a-b)^3+3ab(a-b)$
  - $\dfrac{a^3+b^3+c^3-3abc}{a^2+b^2+c^2-ab-bc-ac}=a+b+c$. If $(a+b+c)=0$, then $a^3+b^3+c^3=3abc$

## Indices:

- **Laws:**
  - $a^m \times a^n = a^{m+n} $
  - $a^m \div a^n = a^{m-n} $
  - $(a^m)^n = (a^n)^m = a^{m \times n}$
  - $a^n \times b^n = (ab)^n$
  - $a^n \div b^n = (a \div b)^n$
  - $a^0=1$
  - $a^{-n} = \dfrac{1}{a^n}$
  - $\sqrt[n]{a} = a^{(\frac{1}{n})}$
  - $(\sqrt[n]{a})^m = a^{(\frac{m}{n})}$

## Quadratic Equations:

- **Solving Quadratics:**

  Following are the ways to find roots of a quadratic equation $ax^2+bx+c=0$.
  - **Factorization:**

    Steps:
    1. Find two numbers $m$, and $n$ such that $mn=ac$, and $m+n=b$
    2. Split the middle term, $bx$, using the numbers: $ax^2+mx+nx+c=0$
    3. Take the common factors out and simplify.

  - **Quadratic Formula:** $\dfrac{-b \pm \sqrt{b^2-4ac}}{2a}$
  <!--
      Derivation:
      1. Divide the equation by $a$ $\Rightarrow x^2+\dfrac{b}{a}x+\dfrac{c}{a}=0$
      2. Move constant to the right $\Rightarrow x^2+\dfrac{b}{a}x=-\dfrac{c}{a}$
      3. Take half the coefficient of $x$, square it and add to both sides $\Rightarrow x^2+\dfrac{b}{a}x+\left(\dfrac{b}{2a}\right)^2=-\dfrac{c}{a}+\left(\dfrac{b}{2a}\right)^2$
      4. Factor $\Rightarrow \left(x+\dfrac{b}{2a}\right)^2=-\dfrac{c}{a}+\left(\dfrac{b}{2a}\right)^2$
      5. Take the square root $\Rightarrow x+\dfrac{b}{2a}=\sqrt{-\dfrac{c}{a}+\left(\dfrac{b}{2a}\right)^2}$
      6. Solve for $x \Rightarrow x=-\dfrac{b}{2a}\pm\sqrt{-\dfrac{c}{a}+\left(\dfrac{b}{2a}\right)^2}$
      7. Simplifying further you get the quadratic equation -->

- **Important Points:**
  - If $a=c$, the roots are reciprocals of each other.
  - If $c=0$, one of the roots is $0$.
  - If $a=-c$, the roots are reciprocals of each other, and negative.

- **If $\alpha,\beta$ are the roots of a quadratic:**
  - $\alpha+\beta=\dfrac{-b}{a}$
  - $\alpha\beta=\dfrac{c}{a}$
  - Quadratic Equation $\Rightarrow x^2-(\alpha+\beta)x+\alpha\beta=0$
  - If $\alpha,\beta$ are the roots of a quadratic equation $ax^2+bx+c=0$, then $\dfrac{1}{\alpha},\dfrac{1}{\beta}$ are the roots of $cx^2+bx+a=0$

## Logarithms:

- **Log rules:**
  - $\log_b(m \times n)=\log_b m + \log_b n$
  - $\log_b(m \div n)=\log_b m - \log_b n$
  - $\log_b(m^n)=n\log_b m$
  - $\log_b m = \dfrac{\log_a m}{\log_a b}$
  - $\log_b a = \dfrac{1}{\log_a b}$
  - $m^{\log_b n} = n^{\log_b m}$ because $m^{\log_b n} = (b^{\log_b m})^{\log_b n} = (b^{\log_b n})^{\log_b m} = n^{\log_b m}$
  - $\log_{b^n}a=\dfrac{\log_b a}{n}$
  - $\log_{\sqrt[n]{b}}a=n\log_b a$
  - $\log _{b}(a+c)=\log _{b}a+\log _{b}\left(1+{\dfrac{c}{a}}\right)$ because $( a + c ) = a\times \left(1+{\dfrac {c}{a}}\right)$

  - $\log _{b}(a-c)=\log _{b}a+\log _{b}\left(1-{\dfrac{c}{a}}\right)$ because $( a - c ) = a\times \left(1-{\dfrac {c}{a}}\right)$

## Progressions:

### Arithmetic Progressions:

- **Definition:** A series where $t_n-t_{n-1} = d$
- **nth Term of AP:** $t_n=a+(n-1)d$
<!-- - **Number of terms in an AP:** $n=\dfrac{t_n-t_1}{d}+1$ -->
- **Sum of n terms in AP:** $S_n = \dfrac{n}{2}[t_1+t_n] = \dfrac{n}{2}[2a+(n-1)d]$
- **Sum of first n natural numbers:** $S_n=\dfrac{n(n+1)}{2}$
<!-- - For any term $t_n$ in AP, $2t_n=t_{n-k}+t_{n+k}$ -->

### Geometric Progressions:

- **Definition:** A series where $\dfrac{t_n}{t_{n-1}} = r$
- **nth Term of GP:** $t_n=ar^{n-1}$
- **Sum of n terms in GP:** $S_n \begin{cases}
 \dfrac{a(r^n-1)}{r-1} \text{ where } r > 1 \\
 \dfrac{a(1-r^n)}{1-r} \text{ where } r < 1
\end{cases}$
- **Sum of infinte terms in GP:** $S_\infty = \dfrac{a}{1-r}$ where $|r|<1$

### Means:

- **Arithmetic mean (A):** $\dfrac{a+b}{2}$

- **Geometric mean (G):** $\sqrt{ab}$

- **Harmonic mean (H):** $\dfrac{2ab}{a+b}$

- **Relation between the means:**
  - $A>G>H$
  - $G=\sqrt{AH}$

## Permutation and Combination:

### Permutation:

- **Without repetition:** $^nP_r=\dfrac{n!}{(n-r)!}$
- **With repetition:** $^nP_r=n^r$
- **With duplicates:** $P_n=\dfrac{n!}{x_1!x_2!x_3! ...}$ where $x_1,x_2,x_3,...$ are the number of times each item is duplicated. $x_1+x_2+x_3+...=n$
- **Circular Permutation:**
  - **Formula:**
    - If $n\not=r \Rightarrow$ $\dfrac{^nP_r}{r}$
    - If $n=r \Rightarrow$ $(n-1)!$
  - If no distinction is made between clockwise and anti-clockwise, divide by 2.

### Combination:

- **Without repetition:** $^nC_r=\dfrac{n!}{r!(n-r)!}$
- **With repetition:** $^{n+r-1}C_r=\dfrac{(n+r-1)!}{r!(n-1)!}$

## Binomial Theorem:

- $(a+b)^n={^nC_0 \cdot a^n}+{^nC_1 \cdot a^{n-1} \cdot b}+{^nC_2 \cdot a^{n-2} \cdot b^2}+...+{^nC_{n-2} \cdot a^2 \cdot b^{n-2}}+{^nC_{n-1} \cdot a \cdot b^{n-1}}+{^nC_n \cdot b^n}$
- $(r+1)^{th}$ term in the expansion of $(a+b)^n \Rightarrow t_{r+1} = {^nC_r} \cdot a^{n-r} \cdot b^r$
- $k^{th}$ term from the end is $(n-k+2)^{th}$ term from the beginning
