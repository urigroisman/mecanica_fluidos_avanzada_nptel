
## Problem 10: Validity of Euler’s Equations Near a Wall

### ❓ Question

In the context of fluid flow over a flat plate, why is Euler’s equation not valid near the wall?

(a) The pressure gradient is zero near the wall  
(b) The flow near the wall has high Reynolds number  
(c) Viscous effects dominate in the flow near the wall  
(d) The statement is false. Euler equation is valid near the wall

---

### 🧠 Background: Euler’s Equations

Euler’s equations describe the motion of an inviscid (non-viscous) fluid:

$$
\rho \left( \frac{\partial \vec{v}}{\partial t} + \vec{v} \cdot \nabla \vec{v} \right) = -\nabla p + \rho \vec{g}
$$

These equations **neglect viscous stresses** and therefore **cannot model the effects of viscosity**, including boundary layers and no-slip conditions.

---

### 🧪 Flow Over a Flat Plate

For flow over a flat plate at high Reynolds number:
- A **boundary layer** forms near the surface.
- Inside this thin layer, **velocity gradients** are large.
- The **viscous terms** become dominant.
- Therefore, **Navier–Stokes equations** are needed.

Euler’s equations are only valid **outside** the boundary layer.

---

### 🔍 Evaluation of Options

- **(a) False** – The pressure gradient is not necessarily zero near the wall.
- **(b) False** – While the overall flow may have high Reynolds number, viscosity is still dominant near the wall.
- **(c) ✅ True** – Euler’s equations neglect viscosity, which dominates near the wall.
- **(d) False** – Euler’s equations are not valid near the wall due to the importance of viscosity there.

---

### ✅ Final Answer:

$$
\boxed{\text{(c) Viscous effects dominate in the flow near the wall}}
$$
