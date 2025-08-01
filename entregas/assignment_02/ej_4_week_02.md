
# Week 02 – Problem 4: Application of Bernoulli Equation in a 2D Steady Flow

## 🧮 Problem Statement

A steady, 2-dimensional velocity field is represented by the stream function:

$$
\psi(x, y) = A(x - y)
$$

where $ A $ is a known dimensional constant.

The flow is assumed **frictionless** (i.e., inviscid). We are asked to consider two points:

- $ P = (2, 4) $
- $ Q = (4, 5) $

Which among the following statements is correct?

---

## 🧠 Step 1: Compute the Velocity Field from the Stream Function

In two-dimensional incompressible flow, the velocity components are:

$$
u = \frac{\partial \psi}{\partial y}, \quad v = -\frac{\partial \psi}{\partial x}
$$

For the given stream function $ \psi(x, y) = A(x - y) $, we obtain:

$$
u = \frac{\partial}{\partial y}[A(x - y)] = -A, \quad v = -\frac{\partial}{\partial x}[A(x - y)] = -A
$$

Thus, the velocity vector is:

$$
\vec{v} = (u, v) = (-A, -A)
$$

The velocity is **constant in space and time**, directed diagonally toward the lower-left.

---

## 🧪 Step 2: Check Steadiness

Since the velocity components $ u $ and $ v $ are constant and **do not depend on time**, we conclude:

$$
\frac{\partial \vec{v}}{\partial t} = 0
$$

✅ **Flow is steady.**

---

## 💨 Step 3: Check Incompressibility

The incompressibility condition in 2D is:

$$
\frac{\partial u}{\partial x} + \frac{\partial v}{\partial y} = 0
$$

Here:

- $ \frac{\partial u}{\partial x} = 0 $
- $ \frac{\partial v}{\partial y} = 0 $

Thus:

$$
\nabla \cdot \vec{v} = 0
$$

✅ **Flow is incompressible.**

Note: The very use of a **stream function** implies incompressibility in 2D, but we confirm it here explicitly.

---

## 🔄 Step 4: Check Irrotationality

In 2D, the scalar vorticity is:

$$
\omega_z = \frac{\partial v}{\partial x} - \frac{\partial u}{\partial y}
$$

Both derivatives are zero, since $ u = -A $ and $ v = -A $ are constants:

$$
\omega_z = 0
$$

✅ **Flow is irrotational.**

---

## 📈 Step 5: Are Points P and Q on the Same Streamline?

Recall that streamlines are defined by level curves of the stream function:

$$
\psi(x, y) = \text{constant}
$$

Evaluate:

- At $ P = (2, 4) $: $ \psi_P = A(2 - 4) = -2A $
- At $ Q = (4, 5) $: $ \psi_Q = A(4 - 5) = -A $

Since $ \psi_P \ne \psi_Q $, the points are:

❌ **Not on the same streamline.**

---

## 🧮 Step 6: Applicability of Bernoulli’s Equation

The **steady, irrotational, incompressible, inviscid** flow satisfies Bernoulli’s equation **globally** (i.e., between any two points):

$$
\frac{p}{\rho} + \frac{v^2}{2} + gz = \text{constant}
$$

Nowhere in the problem is elevation or gravity variation mentioned. Hence, we assume:

✅ The flow occurs in a **horizontal plane** $z = \text{constant}$

Thus, we can simplify Bernoulli’s equation to:

$$
\frac{p}{\rho} + \frac{v^2}{2} = \text{constant}
$$

and apply it between P and Q.

---

## ✅ Final Answer

- The flow is **steady**, **incompressible**, and **irrotational**
- Bernoulli equation is valid **between any two points**, not just along streamlines
- Even though P and Q are **not on the same streamline**, we **can apply Bernoulli**

$$
\boxed{\text{Correct option: (c)}}
$$

---
