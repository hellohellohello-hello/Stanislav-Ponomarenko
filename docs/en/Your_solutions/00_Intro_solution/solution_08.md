# Problem 8 — Definite Integrals (Area under a Curve)

We are asked to calculate the **area under the curve** of:

$$
f(x) = \sin(x)
$$

from 

$$
x = 0 \quad \text{to} \quad x = \pi
$$

---

# Necessary Definitions and Formulas

1. **Definite integral:**

The area under a curve \(f(x)\) from \(x = a\) to \(x = b\) is

$$
\text{Area} = \int_a^b f(x)\,dx
$$

2. **Integral of sine function:**

$$
\int \sin(x) dx = -\cos(x) + C
$$

Where \(C\) is the constant of integration (not needed for definite integrals).

---

# Step-by-Step Solution

Compute the definite integral:

$$
\int_0^\pi \sin(x) dx
$$

---

## Step 1 — Find the antiderivative

$$
\int \sin(x) dx = -\cos(x)
$$

---

## Step 2 — Apply the limits of integration

$$
\int_0^\pi \sin(x) dx = [-\cos(x)]_0^\pi
$$

$$
= -\cos(\pi) + \cos(0)
$$

---

## Step 3 — Evaluate cosine values

- \(\cos(\pi) = -1\)  
- \(\cos(0) = 1\)

Substitute:

$$
-\cos(\pi) + \cos(0) = -(-1) + 1 = 1 + 1 = 2
$$

---

# Final Answer

$$
\text{Area under the curve} = 2
$$
