# Task 04 – Phase Difference

## Problem Statement

Two points on a wave are separated by a distance $\lambda/3$.

Determine the phase difference between these two points in radians.

---

## Theory

### 1. Mathematical Form of a Traveling Wave

A sinusoidal traveling wave can be written as:

$$
y(x,t) = A \sin(kx - \omega t)
$$

The argument of the sine function is called the **phase**:

$$
\phi(x,t) = kx - \omega t
$$

---

### 2. Definition of Phase Difference

The phase difference between two points $x_1$ and $x_2$ at the same time $t$ is:

$$
\Delta \phi = \phi(x_2,t) - \phi(x_1,t)
$$

Substitute the phase expression:

$$
\Delta \phi = kx_2 - \omega t - (kx_1 - \omega t)
$$

The time-dependent terms cancel:

$$
\Delta \phi = k(x_2 - x_1)
$$

Thus:

$$
\Delta \phi = k \Delta x
$$

---

### 3. Relation Between Wave Number and Wavelength

The wave number is defined as:

$$
k = \frac{2\pi}{\lambda}
$$

This connects spatial periodicity with phase.

---

## Step-by-Step Solution

### Step 1: Identify spatial separation

Given:

$$
\Delta x = \frac{\lambda}{3}
$$

---

### Step 2: Use phase difference formula

$$
\Delta \phi = k \Delta x
$$

Substitute $k$:

$$
\Delta \phi = \frac{2\pi}{\lambda} \cdot \frac{\lambda}{3}
$$

---

### Step 3: Simplify

$$
\Delta \phi = \frac{2\pi}{3}
$$

---

## Final Result

$$
\Delta \phi = \frac{2\pi}{3}
$$

---

## Interpretation

This result means:

- A shift of $\lambda/3$ corresponds to a phase shift of $120^\circ$
- One full wavelength corresponds to $2\pi$ radians

Thus:

$$
\frac{\Delta x}{\lambda} = \frac{\Delta \phi}{2\pi}
$$

---

## Key Insight

Phase is a measure of position within a wave cycle.

- $\Delta \phi = 0$ → same point in cycle  
- $\Delta \phi = \pi$ → opposite phase  
- $\Delta \phi = 2\pi$ → identical state  

Here:

$$
\Delta \phi = \frac{2\pi}{3}
$$

represents a significant phase shift but not complete opposition.