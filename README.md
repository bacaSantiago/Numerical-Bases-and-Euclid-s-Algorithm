# Numerical Bases and Euclid's Algorithm

---

## Overview

This project explores the concepts of numerical bases and Euclid's Algorithm in the realm of mathematics and cryptography. It delves into the theorem regarding the representation of numbers in different bases, providing a step-by-step demonstration of converting a number from base 10 to base 7. Additionally, it presents algorithms to write numbers in any given base, shedding light on their implementation and showcasing their utility.

The latter part of the project focuses on Euclid's Algorithm, a fundamental tool for finding the Greatest Common Divisor (GCD) of two integers. It provides an in-depth explanation of the algorithm's workings, accompanied by a Python implementation that calculates the GCD and expresses it as a linear combination of the input numbers.

## Numeric Bases

- ### Theorem:

Given a number $b \in \mathbb{N}$ with $b \geq 2$ and $n \in \mathbb{N}$ with $n \neq 0$, there exist $l \in \mathbb{N}$ and $d_0, d_1, ..., d_l \in \mathbb{N}$ such that:

$$n=d_{0} \cdot b^0 +d_{1} \cdot b^1 +...+ d_{l−1} \cdot b^{l−1} + d_{l} \cdot b^l$$

$d_l \neq 0$ and for all $0 \leq i \leq l$, we have that $0 \leq d_i < b$.

- ### Algorithm for Base Conversion:

A step-by-step algorithm is provided to convert any number from base 10 to base 7. It involves dividing the number by 7 repeatedly and keeping track of remainders to obtain the desired representation.

- ### General Algorithm for Base Conversion:

A more generalized algorithm is presented to convert numbers into any given base $b \geq 2$. This algorithm iteratively divides the number by the base, accumulating remainders as coefficients for the respective powers of the base.

- ### Uniqueness Proof:

The uniqueness of the representation of numbers in different bases is proven. It is shown that if two representations have different lengths, they must represent different numbers. Moreover, an inductive argument demonstrates that the coefficients in these representations must also be unique.

## Euclid's Algorithm

- ### Functionality:

Euclid's Algorithm is a method for finding the Greatest Common Divisor (GCD) of two integers. The algorithm is explained, detailing its recursive nature and how it computes both the GCD and the coefficients for the linear combination of the input numbers.

- ### Python Implementation:

A Python program implementing Euclid's Algorithm is provided. It takes two integers as input and returns their GCD along with the coefficients for expressing the GCD as a linear combination of the input numbers.

---

