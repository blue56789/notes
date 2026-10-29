# Probability

- $P(A \cup B) = P(A) + P(B) + P(A \cap B)$

- $P(A \cap B) = P(A) \times P(B)$ if $A$ and $B$ are independent

- $P(A \cap B) = 0$ if $A$ and $B$ are mutually exclusive. Ex. $A \cap A^c = \varnothing$

## Conditional Probability:

- $P(A \cap B) = P(A) \times P(B \mid A) = P(B) \times P(A \mid B)$ if $A$ and $B$ are dependent

- $\therefore P(A \mid B) = \dfrac{P(A \cap B)}{P(B)} = \dfrac{P(A) \times P(B \mid A)}{P(B)}$ (Baye's Theorem)

- if $A$ and $B$ are independent, $P(A \mid B) = P(A)$

## Random Variable:

Literally just a function that maps the sample set to numbers.
<br/> Example: Mapping $\{H,T\}$ of a coin toss to $\{1,-1\}$

- Expected value $E(X) = $ Mean $\mu = \sum{(x \times P(x))}$

- If $c$ is a constant:
  - $E(c) = c$
  - $E(cX) = cE(X)$
  - $E(c+X) = c+E(X)$
  - $E(X+Y) = E(X)+E(Y)$

- Variance $V(X) = \sigma^2 = E(X^2) - (E(X))^2$

## Probability Distribution:

- Expected value = Mean = First moment = $\displaystyle E(X) = \sum_{i=0}^n{(x_i \times P(x_i))}$

- Raw Second moment = $\displaystyle E(X^2) = \sum_{i=0}^n{(x_i^2 \times P(x_i))}$

- Variance = Central Second moment = $\displaystyle Var(X) = \sigma^2 = E(X^2) - [E(X)]^2$

- Standard Deviation = $\sigma$

### Discrete Distribution:

<div style="overflow-x:scroll; width:100%; white-space: nowrap;">

| Distribution           | Description                                                                       | Probability Mass Function $P(X=x)$                                         | Cumulative Distribution Function $P(X \le x)$                                                                                                            | Mean $E(X)$                   | Variance $\text{Var}(X)$           |
| ---------------------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------- |
| **Binomial**           | Number of successes in $n$ independent Bernoulli trials with probability $p$.     | $\displaystyle \binom{n}{x} p^x (1-p)^{n-x}$ for $x = 0, 1, \dots, n$      | $\displaystyle \sum_{i=0}^{\lfloor x \rfloor} \binom{n}{i} p^i (1-p)^{n-i}$                                                                              | $\displaystyle np$            | $\displaystyle np(1-p)$            |
| **Poisson**            | Number of events occurring in a fixed interval with rate $\lambda$.               | $\displaystyle \frac{e^{-\lambda} \lambda^x}{x!}$ for $x = 0, 1, 2, \dots$ | $\displaystyle e^{-\lambda} \sum_{i=0}^{\lfloor x \rfloor} \frac{\lambda^i}{i!}$ or $\frac{\Gamma(\lfloor x \rfloor + 1, \lambda)}{\lfloor x \rfloor !}$ | $\displaystyle \lambda$       | $\displaystyle \lambda$            |
| **Geometric**          | Number of trials needed to get the first success, with success probability $p$.   | $\displaystyle (1-p)^{x-1} p$ for $x = 1, 2, 3, \dots$                     | $\displaystyle 1 - (1-p)^{\lfloor x \rfloor}$ for $x \ge 1$                                                                                              | $\displaystyle \frac{1}{p}$   | $\displaystyle \frac{1-p}{p^2}$    |
| **Negative Binomial**  | Number of trials needed to get $r$ successes, with success probability $p$.       | $\displaystyle \binom{x-1}{r-1} p^r (1-p)^{x-r}$ for $x = r, r+1, \dots$   | $\displaystyle \sum_{i=r}^{\lfloor x \rfloor} \binom{i-1}{r-1} p^r (1-p)^{i-r}$                                                                          | $\displaystyle \frac{r}{p}$   | $\displaystyle \frac{r(1-p)}{p^2}$ |
| **Uniform (Discrete)** | A finite number of equally likely outcomes between $a$ and $b$ ($n = b - a + 1$). | $\displaystyle \frac{1}{n}$ for $x = a, a+1, \dots, b$                     | $\displaystyle \frac{\lfloor x \rfloor - a + 1}{n}$ (for $a \le x \le b$)                                                                                | $\displaystyle \frac{a+b}{2}$ | $\displaystyle \frac{n^2 - 1}{12}$ |

</div>

### Continuous Distribution:

<div style="overflow-x:scroll; width:100%; white-space: nowrap;">

| Distribution                 | Description                                                        | PDF $f(x)$                                                                                             | CDF $P(X \le x)$                                                                         | Mean $E(X)$                       | Variance $\text{Var}(X)$            |
| ---------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- | --------------------------------- | ----------------------------------- |
| **Uniform** $(a, b)$         | Constant probability over a bounded interval $[a, b]$              | $\displaystyle \frac{1}{b-a}$ _(for $a \le x \le b$)_                                                  | $\displaystyle \frac{x-a}{b-a}$ _(for $a \le x \le b$)_                                  | $\displaystyle \frac{a+b}{2}$     | $\displaystyle \frac{(b-a)^2}{12}$  |
| **Exponential** $(\lambda)$  | Models time between independent events (rate $\lambda$)            | $\displaystyle \lambda e^{-\lambda x}$ _(for $x \ge 0$)_                                               | $\displaystyle 1 - e^{-\lambda x}$ _(for $x \ge 0$)_                                     | $\displaystyle \frac{1}{\lambda}$ | $\displaystyle \frac{1}{\lambda^2}$ |
| **Normal** $(\mu, \sigma)$   | Symmetric bell-shaped curve defined by mean and standard deviation | $\displaystyle \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{1}{2}z^2}$ <br> where $z = \frac{x-\mu}{\sigma}$ | $\displaystyle \frac{1}{2}\left[1 + \text{erf}\left(\frac{z}{\sqrt{2}}\right)\right]$    | $\displaystyle \mu$               | $\displaystyle \sigma^2$            |
| **Standard Normal** $(0, 1)$ | Normal distribution with zero mean and unit $\sigma$               | $\displaystyle \frac{1}{\sqrt{2\pi}} e^{-\frac{x^2}{2}}$ <br> ($x$ acts as the $z$-value here)         | $\displaystyle \Phi(x) = \frac{1}{\sqrt{2\pi}} \int_{-\infty}^{x} e^{-\frac{t^2}{2}} dt$ | $\displaystyle 0$                 | $\displaystyle 1$                   |

</div>
