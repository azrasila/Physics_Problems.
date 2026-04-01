# Task — Range Optimization

## Problem Statement

Show that maximum range occurs at $\theta = 45^\circ$.

## Theory

For projectile motion on level ground (neglecting air resistance), the horizontal range is given by:

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

where:
- $v_0$ is the initial velocity,
- $\theta$ is the launch angle,
- $g$ is the acceleration due to gravity.

This equation shows that the range depends on the sine of twice the launch angle.

---

## Step-by-Step Solution

### 1. Identify the variable to maximize

In the range formula:

$$
R(\theta) = \frac{v_0^2}{g} \sin(2\theta)
$$

The term $\frac{v_0^2}{g}$ is constant.

So maximizing $R(\theta)$ reduces to maximizing:

$$
\sin(2\theta)
$$

---

### 2. Use properties of the sine function

The sine function has a maximum value of:

$$
\sin(x) \leq 1
$$

Thus:

$$
\sin(2\theta) \leq 1
$$

The maximum occurs when:

$$
\sin(2\theta) = 1
$$

---

### 3. Solve for the angle

We know:

$$
\sin(90^\circ) = 1
$$

So:

$$
2\theta = 90^\circ
$$

$$
\theta = 45^\circ
$$

---

## Final Result

$$
\theta_{\text{max}} = 45^\circ
$$

---

## Interpretation

At $45^\circ$, the projectile achieves the optimal balance between horizontal and vertical motion.

- If the angle is too small → insufficient time in the air  
- If the angle is too large → insufficient horizontal velocity  

Thus, $45^\circ$ provides the maximum possible range.