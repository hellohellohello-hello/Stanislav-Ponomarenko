# Problem 10 — Infinite Series (Final Position of an Ant)

We are asked to determine the **final position** of an ant starting at the origin, moving in the following pattern:

1. 1 m east  
2. 1/2 m north  
3. 1/3 m west  
4. 1/4 m south  
5. 1/5 m east  
6. 1/6 m north  
… and so on, **alternating directions**.

---

# Step 0 — Definitions and Formulas

1. **East-West (x) direction series:**

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This is an **alternating series** of the form:

$$
\sum_{n=0}^{\infty} \frac{(-1)^n}{2n+1} = 1 - \frac13 + \frac15 - \frac17 + \dots
$$

It converges to:

$$
\sum_{n=0}^{\infty} \frac{(-1)^n}{2n+1} = \frac{\pi}{4}
$$

---

2. **North-South (y) direction series:**

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

Factor out \(1/2\):

$$
y = \frac{1}{2} \left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)
$$

The series in parentheses is the **alternating harmonic series**, which converges to:

$$
\ln(2)
$$

Thus:

$$
y = \frac{\ln(2)}{2}
$$

---

# Step 1 — Final Coordinates

- East-West (x-axis):

$$
x = \frac{\pi}{4} \approx 0.785
$$

- North-South (y-axis):

$$
y = \frac{\ln 2}{2} \approx 0.347
$$

---

# Final Answer

The ant’s final position is:

$$
(x, y) = \left( \frac{\pi}{4}, \frac{\ln 2}{2} \right)
$$

Or approximately:

$$
(x, y) \approx (0.785, 0.347)
$$
