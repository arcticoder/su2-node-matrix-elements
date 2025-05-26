---
layout: default
title: Closed-Form Matrix Elements for Arbitrary-Valence SU(2) Nodes via Generating Functionals
---

# Closed-Form Matrix Elements for Arbitrary-Valence SU(2) Nodes via Generating Functionals

<p class="author">Arcticoder</p>
<p class="date">May 25, 2025</p>

<div class="abstract">
<strong>Abstract:</strong> We derive closed-form expressions for SU(2) operator matrix elements on arbitrary-valence nodes by extending the universal generating functional approach with source terms. Our central result is a determinant-based formula incorporating group-element dependence, which yields all matrix elements via a single Gaussian integral and hypergeometric expansion.
</div>

You can read this paper directly on this page or [view the PDF version](Closed-Form Matrix Elements for Arbitrary-Valence SU(2) Nodes via Generating Functionals.pdf).

## Introduction

The computation of SU(2) recoupling coefficients has seen recent advances:
uniform closed-form representation of 12j symbols [[1]](https://arcticoder.github.io/su2-3nj-uniform-closed-form/), a universal generating
functional [[2]](https://arcticoder.github.io/su2-3nj-generating-functional/), closed-form
finite recurrences [[3]](https://arcticoder.github.io/su2-3nj-recurrences/), and a
hypergeometric product formula [[4]](https://arcticoder.github.io/su2-3nj-closedform/). We
build on these to obtain operator matrix elements for any node valence and spin labels.

## Generating Functional with Sources

Introduce source spinors \\(J_v(g)\\) for each vertex \\(v\\) to encode group-element dependence:

$$
G(\{x_e\},g)
=\int\prod_v\frac{d^2w_v}{\pi}
\exp\Bigl[
-\sum_v\bar w_v w_v
+\sum_{e=(i,j)}x_e\,\epsilon(w_i,w_j)
+\sum_v(\bar w_v J_v+\overline J_v w_v)
\Bigr].
$$

[View the full paper](./index.html)
