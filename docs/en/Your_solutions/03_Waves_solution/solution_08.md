# Task 08 – Wave Equation Verification

## Problem Statement

Determine which functions satisfy the wave equation:

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

---

## Theory

A valid traveling wave must satisfy the wave equation.

General solution form:

$$
y(x,t) = f(x \pm vt)
$$

---

## Step-by-Step Solution

### Case (a)

$$
y = A \cos(kx^2 - \omega t)
$$

Compute derivatives:

First derivative:

$$
\frac{\partial y}{\partial x} = -A \sin(kx^2 - \omega t) \cdot 2kx
$$

Second derivative introduces nonlinear terms in $x$.

Thus:

- Not proportional to original function  
- Does not satisfy wave equation  

---

### Case (b)

$$
y = A(x - vt)^2
$$

Let:

$$
u = x - vt
$$

Then:

$$
y = A u^2
$$

Compute derivatives:

$$
\frac{\partial^2 y}{\partial x^2} = 2A
$$

$$
\frac{\partial^2 y}{\partial t^2} = 2A v^2
$$

Thus:

$$
\frac{\partial^2 y}{\partial x^2}
=
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

✔ satisfies wave equation

---

### Case (c)

$$
y = A \log(x + vt)
$$

Let:

$$
u = x + vt
$$

Then:

$$
y = A \log u
$$

Compute derivatives:

$$
\frac{\partial^2 y}{\partial x^2} = -\frac{A}{u^2}
$$

$$
\frac{\partial^2 y}{\partial t^2} = -\frac{A v^2}{u^2}
$$

Thus:

$$
\frac{\partial^2 y}{\partial x^2}
=
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

✔ satisfies wave equation

---

## Final Result

Valid solutions:

- (b)
- (c)

---

## Interpretation

A function represents a traveling wave if it depends only on:

$$
x - vt \quad \text{or} \quad x + vt
$$

This ensures that the wave shape propagates without distortion.