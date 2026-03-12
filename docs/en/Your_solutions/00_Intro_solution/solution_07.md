# Problem 7 — Logic & Series (The Fly and the Bicycle)

We are given:

- A bicycle **10 m** from a wall, moving at **1 m/s** towards it.  
- A fly starts at the bicycle and flies at **2 m/s** towards the wall, turning back immediately when it reaches the wall.  
- The fly continues until the bicycle hits the wall.

We are asked to find **the total distance the fly travels**.

---

# Necessary Definitions and Formulas

1. **Distance formula:** 

$$
\text{distance} = \text{speed} \times \text{time}
$$

2. The **fly keeps moving continuously** until the bicycle reaches the wall.

---

# Step-by-Step Solution

## Step 1 — Time until the bicycle reaches the wall

The bicycle is **10 m** away from the wall and moves at **1 m/s**:

$$
t = \frac{\text{distance}}{\text{speed}} = \frac{10}{1} = 10\ \text{seconds}
$$

---

## Step 2 — Distance traveled by the fly

The fly moves at **2 m/s** continuously for the full time until the bicycle hits the wall.

$$
d_{\text{fly}} = \text{speed} \times \text{time} = 2 \cdot 10 = 20\ \text{meters}
$$

> **Note:** There is no need to sum infinite series of back-and-forth trips — the total distance is simply the fly's speed multiplied by the total time.

---

# Final Answer

$$
\text{Total distance traveled by the fly} = 20\ \text{meters}
$$
