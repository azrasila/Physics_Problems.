# Solutions goes here

...# Task 01 – Projectile Motion

## Problem Statement

A projectile is launched with initial velocity $v_0 = 100 \ \text{m/s}$ at an angle $\theta = 37^\circ$. Neglect air resistance.

Determine:
- equations of motion,
- time of flight,
- maximum height,
- range.

## Theory

Projectile motion is decomposed into two independent motions:

- Horizontal motion: constant velocity
- Vertical motion: constant acceleration $-g$

Initial velocity components:

$$
v_{0x} = v_0 \cos\theta, \qquad v_{0y} = v_0 \sin\theta
$$

## Step-by-Step Solution

### Differential Equations

Horizontal:

$$
\frac{d^2 x}{dt^2} = 0
$$

Vertical:

$$
\frac{d^2 y}{dt^2} = -g
$$

---

### Time of Flight

Vertical position:

$$
y(t) = v_{0y} t - \frac{1}{2} g t^2
$$

At landing $y=0$:

$$
t (v_{0y} - \frac{1}{2} g t) = 0
$$

Non-zero solution:

$$
T = \frac{2 v_{0y}}{g}
$$

---

### Maximum Height

At peak $v_y = 0$:

$$
v_y = v_{0y} - g t = 0 \Rightarrow t = \frac{v_{0y}}{g}
$$

Height:

$$
H = \frac{v_{0y}^2}{2g}
$$

---

### Range

$$
R = v_{0x} T = v_0 \cos\theta \cdot \frac{2 v_0 \sin\theta}{g}
$$

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

## Final Result

$$
T = \frac{2 v_0 \sin\theta}{g}, \quad
H = \frac{v_0^2 \sin^2\theta}{2g}, \quad
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

## Interpretation

Horizontal and vertical motions are independent. The trajectory is parabolic, and gravity only affects the vertical component.