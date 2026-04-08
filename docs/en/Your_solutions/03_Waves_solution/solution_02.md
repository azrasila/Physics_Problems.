# Task 02 – String Harmonics

## Problem Statement

A string of length $L = 0.64 \ \text{m}$ has a fundamental frequency $f = 330 \ \text{Hz}$.

Determine the wave speed on the string.

---

## Theory

Standing waves on a string fixed at both ends satisfy boundary conditions:

$$
y(0,t) = 0, \quad y(L,t) = 0
$$

This leads to quantized wavelengths:

$$
\lambda_n = \frac{2L}{n}, \quad n = 1,2,3,\dots
$$

The fundamental mode corresponds to:

$$
n = 1
$$

Thus:

$$
\lambda_1 = 2L
$$

---

The wave relation connects speed, wavelength, and frequency:

$$
v = f \lambda
$$

---

## Step-by-Step Solution

### 1. Determine the wavelength of the fundamental mode

From:

$$
\lambda = 2L
$$

Substitute:

$$
\lambda = 2 \cdot 0.64
$$

$$
\lambda = 1.28 \ \text{m}
$$

---

### 2. Use the wave relation

$$
v = f \lambda
$$

Substitute:

$$
v = 330 \cdot 1.28
$$

---

### 3. Compute the result

$$
v = 422.4 \ \text{m/s}
$$

---

## Final Result

$$
v = 422.4 \ \text{m/s}
$$

---

## Interpretation

The wave speed is determined entirely by the **physical properties of the string** (tension and linear density):

$$
v = \sqrt{\frac{T}{\mu}}
$$

The frequency does not determine the speed; instead, it adjusts to satisfy boundary conditions for a given string.