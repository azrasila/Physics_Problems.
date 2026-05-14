# 2. Resistors

## Given

We have exactly three resistors.

Each resistor has a resistance of:

R = 1 Ω

The problem asks us to find all possible equivalent resistances that can be created using these three resistors.

We will examine all possible ways to connect them.

---

# Case 1 — All Resistors in Series

## Understanding the Connection

In a series circuit, resistors are connected one after another in a single path.

This means:

- the same current flows through all resistors
- resistances add directly together

---

## Step 1 — Use the Series Formula

Formula:

Req = R1 + R2 + R3

Substitute values:

Req = 1 + 1 + 1

Req = 3 Ω

---

## Explanation

Since all resistors are connected in one line, each resistor increases the total opposition to current.

Therefore, the equivalent resistance becomes larger than any individual resistor.

---

# Case 2 — All Resistors in Parallel

## Understanding the Connection

In a parallel circuit:

- each resistor has the same voltage
- current splits into multiple paths
- total resistance becomes smaller

---

## Step 1 — Use the Parallel Formula

Formula:

1 / Req = 1/R1 + 1/R2 + 1/R3

Substitute values:

1 / Req = 1 + 1 + 1

1 / Req = 3

Take reciprocal:

Req = 1/3 Ω

---

## Explanation

Because the current now has three different paths, the circuit becomes easier for current to pass through.

This is why the equivalent resistance is very small.

---

# Case 3 — Two Resistors in Parallel, Then One in Series

## Step 1 — Combine Two Resistors in Parallel

We first combine two 1 Ω resistors in parallel.

Formula:

Req = (R × R) / (R + R)

Substitute values:

Req = (1 × 1) / (1 + 1)

Req = 1 / 2

Req = 0.5 Ω

---

## Explanation

Two equal resistors in parallel always produce a smaller resistance.

The current can move through two paths instead of one.

---

## Step 2 — Add the Third Resistor in Series

Now we connect the third resistor in series with the previous result.

Formula:

Req = 1 + 0.5

Req = 1.5 Ω

---

## Explanation

The third resistor is added directly because series resistances simply add together.

---

# Case 4 — Two Resistors in Series, Then One in Parallel

## Step 1 — Combine Two Resistors in Series

Formula:

Req = 1 + 1

Req = 2 Ω

---

## Explanation

Two resistors in series increase the total resistance.

---

## Step 2 — Connect in Parallel with Third Resistor

Now place the 2 Ω combination in parallel with another 1 Ω resistor.

Formula:

1 / Req = 1/2 + 1

Convert:

1 / Req = 1/2 + 2/2

1 / Req = 3/2

Take reciprocal:

Req = 2/3 Ω

Req ≈ 0.67 Ω

---

## Explanation

The parallel connection reduces the resistance again because the current gains another path.

---

# Final Unique Equivalent Resistances

The possible equivalent resistances are:

- 3 Ω
- 1/3 Ω
- 1.5 Ω
- 2/3 Ω

---

# Conclusion

By arranging the same three resistors in different ways, we can create several different equivalent resistances.

Series connections increase resistance, while parallel connections decrease resistance.