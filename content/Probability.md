# Probability

This chapter provides a review of Probability and can be skipped if you already have a strong understanding of the topic.

## Probability basics

A probability function satisfies:

$0 \leq P(A) \leq 1$

$P(\Omega) = 1$

where $\Omega$ is the sample space.

---

## Complement rule

$P(A^c) = 1 - P(A)$

---

## Addition rule

For any events $A$ and $B$:

$P(A \cup B) = P(A) + P(B) - P(A \cap B)$

---

## Conditional probability

$P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \quad P(B) > 0$

---

## Independence

Two events are independent if:

$P(A \cap B) = P(A)P(B)$

Equivalent form:

$P(A \mid B) = P(A)$

---

## Law of total probability

If $B_1, B_2, \dots, B_n$ partition the space:

$P(A) = \sum_{i=1}^{n} P(A \mid B_i) P(B_i)$

---

## Bayes’ theorem

$P(A \mid B) = \frac{P(B \mid A)P(A)}{P(B)}$

---

## 10. Log–probability interaction

Since $0 < p(x) \leq 1$:

$\log_2 p(x) \leq 0$

---

## Summary

- Probability measures likelihood
- Conditional probability refines information with conditions
- Independence simplifies joint distributions
- Logarithms convert probabilities into information contributions
