# Task 05 – Echo Ranging

## Problem Statement

A person shouts toward a cliff and hears the echo after $t = 1 \ \text{s}$.

Determine the distance to the cliff.  
Speed of sound: $v = 343 \ \text{m/s}$.

---

## Theory

### 1. Physical Description of the Process

The sound wave travels:

1. From the person to the cliff  
2. From the cliff back to the person  

Thus, the total distance traveled by the wave is:

$$
\text{total distance} = 2d
$$

---

### 2. Relation Between Distance, Speed, and Time

The general kinematic relation is:

$$
\text{distance} = \text{speed} \times \text{time}
$$

Thus:

$$
2d = vt
$$

Solving for $d$:

$$
d = \frac{vt}{2}
$$

---

## Step-by-Step Solution

### Step 1: Write governing equation

$$
d = \frac{vt}{2}
$$

---

### Step 2: Substitute known values

$$
d = \frac{343 \cdot 1}{2}
$$

---

### Step 3: Compute

$$
d = 171.5 \ \text{m}
$$

---

## Final Result

$$
d = 171.5 \ \text{m}
$$

---

## Interpretation

The factor $\frac{1}{2}$ is essential because:

- The measured time includes **both forward and return paths**
- The actual distance to the cliff is only **half** of the total path

---

## Physical Insight

This method is an example of **time-of-flight measurement**, widely used in:

- sonar systems  
- radar systems  
- ultrasonic distance sensors  

The general principle:

$$
d = \frac{vt}{2}
$$

applies whenever a signal is reflected and returns to the source.