
# Week 02 – Problem 9: Why the No-Slip Condition Cannot Be Used with Euler’s Equations

## 🧮 Problem Statement

**Why cannot the no-slip boundary condition be used when solving Euler’s equations for fluid flow?**

Options:

- (a) Because the flow is compressible  
- (b) Because Euler’s equations do not account for body forces  
- (c) Because Euler’s equations neglect viscosity  
- (d) Because Euler’s equations assume irrotational flow  

---

## 🧠 Background

Euler’s equations describe the motion of an **inviscid fluid**, i.e., a fluid with **no viscosity**. The form is:

\[
\rho \left( \frac{\partial \vec{v}}{\partial t} + (\vec{v} \cdot \nabla)\vec{v} \right) = -\nabla p + \rho \vec{g}
\]

They are derived from the Navier–Stokes equations by **neglecting viscous stresses**.

---

## 🚫 The No-Slip Boundary Condition

The no-slip condition is a consequence of viscosity. In viscous (Navier–Stokes) flow, it enforces:

\[
\vec{v}_{\text{fluid}} = \vec{v}_{\text{wall}} \quad \text{at solid surfaces}
\]

This condition **requires** a velocity gradient near the wall — which only exists if viscosity is present.

Therefore:

> You **cannot** impose a no-slip boundary condition while solving Euler's equations, because there’s **no viscosity** to justify it.

---

## ❌ Evaluation of Options

- **(a)** Flow compressibility has nothing to do with no-slip ⇒ ❌  
- **(b)** Euler's equations do account for body forces (e.g., gravity) ⇒ ❌  
- **(c)** Euler neglects viscosity ⇒ ✅  
- **(d)** Euler’s equations do **not** assume irrotationality ⇒ ❌

---

## ✅ Final Answer

\[
\boxed{\text{(c) Because Euler’s equations neglect viscosity}}
\]
