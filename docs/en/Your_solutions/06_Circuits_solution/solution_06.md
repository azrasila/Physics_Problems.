# 15. Resistor Cube

## Given

A cube is constructed from 12 identical resistors placed on its edges.

Each resistor has resistance **R**.

We are asked to find the equivalent resistance between two opposite corners of the cube.

---

# Step 1 — Understand the Structure

A cube has:

- 8 corners
- 12 edges

Each edge contains one resistor.

Current enters from one corner and exits from the opposite corner.

Because the cube is perfectly symmetrical, the current divides equally along identical paths.

This symmetry helps simplify the circuit.

---

# Step 2 — Analyze the First Corner

From the starting corner, there are 3 resistors connected outward.

Since the cube is symmetric, the total current divides equally into the three branches.

If the total current is:

I

then each branch carries:

I / 3

These 3 resistors behave like parallel resistors.

Using the parallel resistor formula:

1 / R₁ = 1 / R + 1 / R + 1 / R

Simplify:

1 / R₁ = 3 / R

Take the reciprocal:

R₁ = R / 3

So the first section becomes:

R₁ = R / 3

---

# Step 3 — Analyze the Middle Section

The current now reaches the middle vertices of the cube.

Because symmetric points have equal potential:

- no current flows between equal-potential nodes
- the middle section simplifies

The six middle resistors combine into equivalent paths.

After symmetry simplification, the middle section becomes:

R₂ = R / 6

---

# Step 4 — Analyze the Final Corner

Near the exit corner, the situation is identical to the entrance corner.

Again, there are 3 equal resistors sharing the current equally.

Using the same parallel formula:

1 / R₃ = 1 / R + 1 / R + 1 / R

Simplify:

1 / R₃ = 3 / R

Take the reciprocal:

R₃ = R / 3

So:

R₃ = R / 3

---

# Step 5 — Combine All Sections

Now the cube is simplified into three resistive sections connected in series.

For series resistors:

R(eq) = R₁ + R₂ + R₃

Substitute the values:

R(eq) = R / 3 + R / 6 + R / 3

Find a common denominator:

R(eq) = 2R / 6 + R / 6 + 2R / 6

Add the fractions:

R(eq) = 5R / 6

---

# Explanation

The equivalent resistance becomes smaller than a single resistor because the current has multiple possible paths through the cube.

More parallel paths reduce the total resistance.

---

# Final Answer

R(eq) = 5R / 6