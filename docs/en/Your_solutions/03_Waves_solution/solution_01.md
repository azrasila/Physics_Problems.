# Task 01 – Wave Properties

## Problem Statement

A sound wave has frequency $f = 440 \ \text{Hz}$.

Determine its wavelength:
- in air, where $v_{\text{air}} = 343 \ \text{m/s}$,
- in water, where $v_{\text{water}} = 1482 \ \text{m/s}$.

---

## Theory

### 1. Definition of a Traveling Wave

A sinusoidal traveling wave can be written as:

$$
y(x,t) = A \sin(kx - \omega t)
$$

where:

- $A$ → amplitude,
- $k$ → wave number,
- $\omega$ → angular frequency.

---

### 2. Relation Between $k$, $\omega$, $\lambda$, and $f$

The wave number is defined as:

$$
k = \frac{2\pi}{\lambda}
$$

The angular frequency is:

$$
\omega = 2\pi f
$$

---

### 3. Derivation of Wave Speed

The phase of the wave is:

$$
\phi = kx - \omega t
$$

A point of constant phase satisfies:

$$
kx - \omega t = \text{const}
$$

Differentiate with respect to time:

$$
k \frac{dx}{dt} - \omega = 0
$$

Thus:

$$
\frac{dx}{dt} = \frac{\omega}{k}
$$

Therefore, wave speed is:

$$
v = \frac{\omega}{k}
$$

Substitute definitions:

$$
v = \frac{2\pi f}{2\pi / \lambda}
$$

$$
v = f \lambda
$$

---

### 4. Physical Interpretation

This equation means:

- If frequency increases → wavelength must decrease (for fixed $v$),
- If speed increases → wavelength increases (for fixed $f$).

---

### 5. Behavior Across Media

When a wave passes into another medium:

- The **frequency remains constant** (source-dependent),
- The **wave speed changes** (medium-dependent),
- Therefore:

$$
\lambda \propto v
$$

---

## Step-by-Step Solution

### 1. Wavelength in Air

Start from:

$$
\lambda = \frac{v}{f}
$$

Substitute:

$$
\lambda_{\text{air}} = \frac{343}{440}
$$

Perform division:

$$
\lambda_{\text{air}} = 0.7795 \ \text{m}
$$

---

### 2. Wavelength in Water

Apply the same formula:

$$
\lambda_{\text{water}} = \frac{1482}{440}
$$

Compute:

$$
\lambda_{\text{water}} = 3.368 \ \text{m}
$$

---

## Final Result

$$
\lambda_{\text{air}} \approx 0.78 \ \text{m}
$$

$$
\lambda_{\text{water}} \approx 3.37 \ \text{m}
$$

---

## Interpretation

The wavelength in water is significantly larger because:

- The wave speed is much higher in water,
- The frequency remains unchanged,
- Therefore, the spatial distance between wave crests increases.

Mathematically:

$$
\frac{\lambda_{\text{water}}}{\lambda_{\text{air}}}
=
\frac{v_{\text{water}}}{v_{\text{air}}}
$$

This confirms that wavelength scales linearly with propagation speed.

---

## Key Takeaways

- Wave speed is given by:

$$
v = \frac{\omega}{k} = f \lambda
$$

- Frequency is invariant across media.
- Wavelength adapts to maintain the wave relation.