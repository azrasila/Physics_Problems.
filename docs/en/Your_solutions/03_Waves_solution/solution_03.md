# Task 03 – Superposition Principle

## Problem Statement

Given:

$$
y_1 = A \sin(kx - \omega t), \quad y_2 = A \sin(kx + \omega t)
$$

Find the resulting wave and node positions.

---

## Theory

### 1. Linear Superposition

For linear wave equations:

$$
y = y_1 + y_2
$$

---

### 2. Trigonometric Identity

$$
\sin a + \sin b = 2 \sin\left(\frac{a+b}{2}\right)\cos\left(\frac{a-b}{2}\right)
$$

---

## Step-by-Step Solution

### 1. Add the waves

$$
y = A\sin(kx - \omega t) + A\sin(kx + \omega t)
$$

---

### 2. Apply identity

Let:

$$
a = kx - \omega t, \quad b = kx + \omega t
$$

Then:

$$
\frac{a+b}{2} = kx, \quad \frac{a-b}{2} = -\omega t
$$

Thus:

$$
y = 2A \sin(kx)\cos(\omega t)
$$

---

### 3. Node condition

Nodes occur when displacement is zero for all $t$:

$$
\sin(kx) = 0
$$

$$
kx = n\pi
$$

Using:

$$
k = \frac{2\pi}{\lambda}
$$

$$
x = \frac{n\lambda}{2}
$$

---

## Final Result

$$
y(x,t) = 2A \sin(kx)\cos(\omega t)
$$

---

## Interpretation

- The wave no longer propagates → standing wave
- Energy is stored in oscillations between nodes and antinodes
- Nodes are fixed points where destructive interference occurs