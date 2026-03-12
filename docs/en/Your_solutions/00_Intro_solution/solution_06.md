# Problem 6 — Function Analysis (Local Maxima and Minima)

We are given the function:

$$
f(x) = 3x^2 - 12x + 7
$$

We are asked to **identify any local maxima or minima**.

---

# Necessary Definitions and Formulas

## 1. Local Extrema

A function has a **local maximum or minimum** at a point \(x_0\) if:

$$
f'(x_0) = 0
$$

- **Local minimum:** \(f''(x_0) > 0\)  
- **Local maximum:** \(f''(x_0) < 0\)

Where \(f'\) is the **first derivative** and \(f''\) is the **second derivative**.

---

# Step-by-Step Solution

## Step 1 — Compute the first derivative

$$
f(x) = 3x^2 - 12x + 7
$$

$$
f'(x) = \frac{d}{dx}(3x^2 - 12x + 7)
$$

$$
f'(x) = 6x - 12
$$

---

## Step 2 — Solve \(f'(x) = 0\)

$$
6x - 12 = 0
$$

$$
6x = 12
$$

$$
x = 2
$$

This is our **critical point**.

---

## Step 3 — Determine the type using the second derivative

Compute second derivative:

$$
f''(x) = \frac{d}{dx}(6x - 12) = 6
$$

Since

$$
f''(2) = 6 > 0
$$

the function has a **local minimum** at \(x = 2\).

---

## Step 4 — Compute the minimum value

Substitute \(x = 2\) into \(f(x)\):

$$
f(2) = 3(2)^2 - 12(2) + 7
$$

$$
f(2) = 12 - 24 + 7
$$

$$
f(2) = -5
$$

---

# Final Answer

- Local minimum at:

$$
(x, f(x)) = (2, -5)
$$

- No local maximum exists, because the parabola opens upwards.
