# Continued Fraction of Prime Cascade

This repository explores a constant constructed from the continued fraction whose partial denominators are the prime numbers.  The constant is defined by

\[
\alpha = [0; p_1, p_2, p_3, \ldots] = \cfrac{1}{p_1 + \cfrac{1}{p_2 + \cfrac{1}{p_3 + \ddots}}}
\]

where $p_n$ denotes the $n$‑th prime.  The accompanying article (written in LaTeX) outlines a proof that this constant is transcendental.

## Web Demo

Open `index.html` in your web browser to see the continued fraction rendered with MathJax.

## Repository Structure

- `README.md` – project overview and background information.
- `index.html` – simple web page displaying the constant with LaTeX‑style formatting via MathJax.

## Background

The primes grow without bound, and the denominators in the continued fraction become correspondingly large.  Classical results on continued fractions with rapidly growing partial denominators imply that the limit above cannot satisfy any non‑zero polynomial with integer coefficients.  Hence $\alpha$ is a transcendental number, illustrating a "prime cascade" through continued fractions.

