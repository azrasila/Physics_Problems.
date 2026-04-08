# Task 09 – Damped Harmonic Oscillator

## Problem Statement

Consider the differential equation:

$$
m \frac{d^2 x}{dt^2} + b \frac{dx}{dt} + k x = 0
$$

Analyze the system and classify its behavior depending on the damping coefficient.

---

## Theory

### 1. Reduction to Standard Form

Divide the equation by $m$:

$$
\frac{d^2 x}{dt^2} + \frac{b}{m} \frac{dx}{dt} + \frac{k}{m} x = 0
$$

Introduce parameters:

$$
\gamma = \frac{b}{2m}, \quad \omega_0 = \sqrt{\frac{k}{m}}
$$

Then the equation becomes:

$$
\ddot{x} + 2\gamma \dot{x} + \omega_0^2 x = 0
$$

---

### 2. Characteristic Equation

Assume solution:

$$
x(t) = e^{rt}
$$

Substitute:

$$
r^2 + 2\gamma r + \omega_0^2 = 0
$$

Solve:

$$
r = -\gamma \pm \sqrt{\gamma^2 - \omega_0^2}
$$

---

## Step-by-Step Analysis

### Case 1: Underdamped Motion

Condition:

$$
\gamma < \omega_0
$$

Then:

$$
r = -\gamma \pm i\omega
$$

where:

$$
\omega = \sqrt{\omega_0^2 - \gamma^2}
$$

Solution:

$$
x(t) = e^{-\gamma t}(C_1 \cos \omega t + C_2 \sin \omega t)
$$

---

### Case 2: Critically Damped Motion

Condition:

$$
\gamma = \omega_0
$$

Then:

$$
r = -\gamma
$$

Solution:

$$
x(t) = (C_1 + C_2 t)e^{-\gamma t}
$$

---

### Case 3: Overdamped Motion

Condition:

$$
\gamma > \omega_0
$$

Roots are real:

$$
r_1, r_2 < 0
$$

Solution:

$$
x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}
$$

---

## Final Result

The motion is classified by comparing $\gamma$ and $\omega_0$:

- $\gamma < \omega_0$ → oscillatory decay  
- $\gamma = \omega_0$ → fastest return without oscillation  
- $\gamma > \omega_0$ → slow exponential decay  

---

## Interpretation

The damping coefficient controls how energy is dissipated:

- Weak damping → oscillations persist  
- Strong damping → motion becomes monotonic  

This system models real physical processes such as:

- mechanical vibrations  
- electrical circuits  
- fluid resistance