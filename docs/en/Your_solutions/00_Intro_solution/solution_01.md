## Problem 1. Vector Algebra (step by step)

Given
[
\vec{a} = [2,,1,,-3],\qquad \vec{b} = [4,,-2,,1].
]

---

### a) Magnitude of each vector

Magnitude in 3D:
[
|\vec{v}|=\sqrt{v_x^2+v_y^2+v_z^2}.
]

For (\vec{a}):
[
|\vec{a}|=\sqrt{2^2+1^2+(-3)^2}
=\sqrt{4+1+9}
=\sqrt{14}.
]

For (\vec{b}):
[
|\vec{b}|=\sqrt{4^2+(-2)^2+1^2}
=\sqrt{16+4+1}
=\sqrt{21}.
]

So:
[
|\vec{a}|=\sqrt{14},\qquad |\vec{b}|=\sqrt{21}.
]

---

### b) Dot product (\vec{a}\cdot\vec{b})

Dot product:
[
\vec{a}\cdot\vec{b}=a_xb_x+a_yb_y+a_zb_z.
]

Compute:
[
\vec{a}\cdot\vec{b}=2\cdot 4 + 1\cdot(-2) + (-3)\cdot 1
=8-2-3
=3.
]

So:
[
\vec{a}\cdot\vec{b}=3.
]

---

### c) Cross product (\vec{a}\times\vec{b})

Use the determinant:
[
\vec{a}\times\vec{b}=
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k}\
2 & 1 & -3\
4 & -2 & 1
\end{vmatrix}.
]

Compute components:

* (\hat{i}) component:
  [
  1\cdot 1 - (-3)\cdot(-2)=1-6=-5
  ]

* (\hat{j}) component (note the minus sign):
  [
  -\Big(2\cdot 1 - (-3)\cdot 4\Big)
  =-\Big(2-(-12)\Big)
  =-14
  ]

* (\hat{k}) component:
  [
  2\cdot(-2) - 1\cdot 4 = -4-4=-8
  ]

So:
[
\vec{a}\times\vec{b}=[-5,,-14,,-8].
]

---

### d) Angle between (\vec{a}) and (\vec{b})

Use:
[
\vec{a}\cdot\vec{b}=|\vec{a}||\vec{b}|\cos\theta
\quad\Rightarrow\quad
\cos\theta=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}.
]

Substitute values:
[
\cos\theta=\frac{3}{\sqrt{14}\sqrt{21}}=\frac{3}{\sqrt{294}}.
]

Simplify (\sqrt{294}):
[
294=49\cdot 6 \Rightarrow \sqrt{294}=7\sqrt{6}.
]
So:
[
\cos\theta=\frac{3}{7\sqrt{6}}=\frac{\sqrt{6}}{14}.
]

Therefore:
[
\theta=\arccos!\left(\frac{\sqrt{6}}{14}\right)\approx 80.0^\circ.
]

---

## Final answers

[
|\vec{a}|=\sqrt{14},\quad |\vec{b}|=\sqrt{21}
]
[
\vec{a}\cdot\vec{b}=3
]
[
\vec{a}\times\vec{b}=[-5,,-14,,-8]
]
[
\theta=\arccos!\left(\frac{\sqrt{6}}{14}\right)\approx 80.0^\circ
]
