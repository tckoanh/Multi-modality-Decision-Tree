# Logarithms

This chapter provides a review of logarithms and can be skipped if you already have a strong understanding of the topic.

## Definition

Let $b \in \mathbb{R}$ satisfy $b > 0$ and $b \neq 1$.

The exponential function is defined as:

$f(x) = b^x, \quad x \in \mathbb{R}$

Since $f$ is strictly monotonic and continuous, it is bijective from $\mathbb{R} \to (0, \infty)$.

Therefore, it has an inverse function, called the logarithm:

$\log_b : (0, \infty) \to \mathbb{R}$

defined by:

$\log_b(x) = y \iff b^y = x$

---

## Well-definedness

Since $b^x$ is bijective on $\mathbb{R} \to (0,\infty)$:

- For every $x > 0$, there exists a unique $y \in \mathbb{R}$
- Therefore $\log_b(x)$ is well-defined and unique

---

## Fundamental inverse identities

From inverse function properties:

$\log_b(b^x) = x \quad \forall x \in \mathbb{R}$

$b^{\log_b(x)} = x \quad \forall x > 0$

---

## Monotonicity

Since $b^x$ is:

- strictly increasing if $b > 1$
- strictly decreasing if $0 < b < 1$

its inverse $\log_b(x)$ preserves strict monotonicity accordingly.

---

## Domain and codomain

$\log_b : (0,\infty) \to \mathbb{R}$

- Domain restriction arises because $b^x > 0$
- Codomain is all real numbers because exponential spans all positive reals

---

## Uniqueness of representation

For any $x > 0$, there exists a unique $y \in \mathbb{R}$ such that:

$x = b^y$

Thus logarithms provide a unique exponent representation of positive real numbers.

---

## Logarithm laws (derived formally)

### Product law

Let:

$\log_b(x) = a, \quad \log_b(y) = c$

Then:

$x = b^a, \quad y = b^c$

Multiplying:

$xy = b^a b^c = b^{a+c}$

Applying $\log_b$:

$\log_b(xy) = a + c$

Hence:

$\log_b(xy) = \log_b(x) + \log_b(y)$

---

### Quotient law

$\frac{x}{y} = \frac{b^a}{b^c} = b^{a-c}$

Thus:

$\log_b\left(\frac{x}{y}\right) = a - c$

So:

$\log_b\left(\frac{x}{y}\right) = \log_b(x) - \log_b(y)$

---

### Power law

$x = b^a \Rightarrow x^k = (b^a)^k = b^{ak}$

Thus:

$\log_b(x^k) = ak = k \log_b(x)$

---

## Change of base theorem

Let $x > 0 $, and $ a, b > 0, a \neq 1, b \neq 1$.

Let:

$y = \log_b(x) \Rightarrow b^y = x$

Taking $\log_a$ on both sides:

$\log_a(b^y) = \log_a(x)$

Using power rule:

$y \log_a(b) = \log_a(x)$

Solving:

$y = \frac{\log_a(x)}{\log_a(b)}$

Thus:

$\log_b(x) = \frac{\log_a(x)}{\log_a(b)}$

---

## Summary

- Logarithm is the inverse of exponential functions
- Defined on $(0,\infty)$
- Converts multiplication into addition
- All algebraic identities follow from exponent laws
- Fully determined by functional equation $f(xy)=f(x)+f(y)$
