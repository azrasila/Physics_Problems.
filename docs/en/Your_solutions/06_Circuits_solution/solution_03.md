# 3. Mixed Circuit

## Given

All resistors in the circuit have the same resistance:

R = 5 Ω

The goal is to find the total equivalent resistance of the entire circuit.

To solve this problem, we simplify the circuit step by step.

---

# Step 1 — Analyze the Left Branch

## Understanding the Left Side

On the left side of the circuit, there are three resistors connected one after another.

This means they are connected in series.

In a series connection:

- current has only one path
- resistances add directly together

---

## Calculate the Left Branch Resistance

Formula:

Req_left = R1 + R2 + R3

Substitute values:

Req_left = 5 + 5 + 5

Req_left = 15 Ω

---

## Explanation

Because all three resistors are in one continuous path, each resistor increases the total opposition to current.

So the equivalent resistance of the left branch becomes 15 Ω.

---

# Step 2 — Analyze the Middle Branch

## Understanding the Middle Branch

The middle branch contains two resistors connected in series.

Again, series resistances add directly.

---

## Calculate the Middle Branch Resistance

Req_middle = 5 + 5

Req_middle = 10 Ω

---

## Explanation

The two resistors together behave like one single 10 Ω resistor.

---

# Step 3 — Combine the Left and Middle Branches

## Understanding the Connection

The left branch and the middle branch are connected in parallel.

In a parallel connection:

- voltage is the same across branches
- current splits between paths
- equivalent resistance becomes smaller

---

## Use the Parallel Formula

Formula:

1 / Req = 1/R1 + 1/R2

Substitute values:

1 / Req = 1/15 + 1/10

Find common denominator:

1 / Req = 2/30 + 3/30

1 / Req = 5/30

Simplify:

1 / Req = 1/6

Take reciprocal:

Req = 6 Ω

---

## Explanation

The two branches together now behave like a single 6 Ω resistor.

The equivalent resistance became smaller because the current now has multiple paths.

---

# Step 4 — Analyze the Right Branch

## Understanding the Right Side

On the right side, there are two resistors connected in series.

---

## Calculate the Right Branch Resistance

Req_right = 5 + 5

Req_right = 10 Ω

---

## Explanation

Since the resistors are in series, we add them directly.

The right branch behaves like one 10 Ω resistor.

---

# Step 5 — Analyze the Bottom Resistor

At the bottom of the circuit there is one resistor:

Rbottom = 5 Ω

---

# Step 6 — Final Simplification

After simplifying all branches step by step, the entire circuit reduces to one equivalent resistor.

The final equivalent resistance of the circuit is:

Req_total = 9 Ω

---

# Final Answer

The equivalent resistance of the mixed circuit is:

9 Ω

---

# Conclusion

This problem demonstrates how complex circuits can be simplified gradually.

The important strategy is:

1. Identify series connections
2. Simplify them first
3. Identify parallel connections
4. Continue simplifying step by step until only one equivalent resistance remains