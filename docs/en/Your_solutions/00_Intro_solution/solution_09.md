# Problem 9 — Optimization Problem (Maximum Rectangle Area)

We are asked to find the rectangle of **maximum area** under the curve:

$$
y = 3 - x^2
$$

in the **first quadrant** (where \(x \ge 0, y \ge 0\)).

---

# Step 0 — Definitions and Formulas

1. **Area of a rectangle:**

If the rectangle has width \(x\) and height \(y\), then

$$
A = x \cdot y
$$

2. **Optimization using calculus:**

- Compute derivative of the area function: \(A'(x)\)  
- Set \(A'(x) = 0\) to find critical points  
- Check second derivative \(A''(x)\) to confirm maximum  

---

# Step 1 — Express area in terms of \(x\)

The height of the rectangle is given by the curve:

$$
y = 3 - x^2
$$

So the area function is:

$$
A(x) = x \cdot y = x (3 - x^2)
$$

Simplify:

$$
A(x) = 3x - x^3
$$

---

# Step 2 — Compute derivative

$$
A'(x) = \frac{d}{dx}(3x - x^3) = 3 - 3x^2
$$

---

# Step 3 — Solve \(A'(x) = 0\)

$$
3 - 3x^2 = 0
$$

Divide both sides by 3:

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1 \quad (\text{only positive value in first quadrant})
$$

---

# Step 4 — Find height \(y\)

Substitute \(x = 1\) into the curve:

$$
y = 3 - (1)^2 = 3 - 1 = 2
$$

---

# Step 5 — Maximum area

$$
A_{\text{max}} = x \cdot y = 1 \cdot 2 = 2
$$

---

# Final Answer

- Width: 

$$
x = 1
$$

- Height: 

$$
y = 2
$$

- Maximum area:

$$
A_{\text{max}} = 2
$$
