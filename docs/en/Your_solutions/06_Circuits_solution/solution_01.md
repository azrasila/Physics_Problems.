# 1. Series and Parallel Circuit

## Given

- R1 = 15 Ω
- R2 = 30 Ω
- R3 = 50 Ω
- Battery voltage: V = 12 V

We will solve the problem in two different cases:

1. All resistors connected in **series**
2. All resistors connected in **parallel**

---

# Part A — Series Connection

In a **series circuit**:

- resistors are connected one after another
- the same current flows through every resistor
- total resistance is found by adding all resistances together

---

## Step 1 — Calculate Equivalent Resistance

For series resistors:

Req = R1 + R2 + R3

Req = 15 + 30 + 50

Req = 95 Ω

---

## Step 2 — Calculate Current

Using Ohm’s Law:

I = V / R

I = 12 / 95

I ≈ 0.126 A

---

## Step 3 — Voltage Across Each Resistor

Using:

V = I × R

### Voltage across R1

V1 = 0.126 × 15

V1 ≈ 1.89 V

### Voltage across R2

V2 = 0.126 × 30

V2 ≈ 3.78 V

### Voltage across R3

V3 = 0.126 × 50

V3 ≈ 6.30 V

Check:

1.89 + 3.78 + 6.30 ≈ 12 V

Correct.

---

# Part B — Parallel Connection

In a **parallel circuit**:

- all resistors are connected to the same voltage source
- voltage is the same across every resistor
- current divides between branches

---

## Step 1 — Calculate Equivalent Resistance

For parallel resistors:

1 / Req = 1/R1 + 1/R2 + 1/R3

1 / Req = 1/15 + 1/30 + 1/50

1 / Req = 0.0667 + 0.0333 + 0.0200

1 / Req = 0.12

Req ≈ 8.33 Ω

---

## Step 2 — Calculate Total Current

Using Ohm’s Law:

I = V / R

I = 12 / 8.33

I ≈ 1.44 A

---

## Step 3 — Current Through Each Resistor

### Current through R1

I1 = 12 / 15

I1 = 0.8 A

### Current through R2

I2 = 12 / 30

I2 = 0.4 A

### Current through R3

I3 = 12 / 50

I3 = 0.24 A

Check:

0.8 + 0.4 + 0.24 = 1.44 A

Correct.

---

# Final Answers

## Series Circuit

- Equivalent resistance: 95 Ω
- Total current: 0.126 A

Voltages:

- V1 = 1.89 V
- V2 = 3.78 V
- V3 = 6.30 V

---

## Parallel Circuit

- Equivalent resistance: 8.33 Ω
- Total current: 1.44 A

Branch currents:

- I1 = 0.8 A
- I2 = 0.4 A
- I3 = 0.24 A