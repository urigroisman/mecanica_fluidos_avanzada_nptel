
# Week 02 – Problem 5: Conditions for the Steady Bernoulli Equation Along a Streamline

## 🧮 Problem Statement

> For the steady-state Bernoulli equation to be applicable along a streamline, which of the following conditions need **not** be satisfied?

- (a) Irrotational  
- (b) Incompressible  
- (c) Inviscid  
- (d) Steady-state  

---

## 🧠 General Form of Bernoulli Equation (Steady Flow)

The **steady Bernoulli equation along a streamline** is:

\[
\frac{p}{\rho} + \frac{v^2}{2} + gz = \text{constant along a streamline}
\]

This result comes from integrating the **Euler equation** along a streamline under the following conditions:

| Condition       | Required? | Explanation |
|----------------|-----------|-------------|
| Steady         | ✅        | Time derivatives vanish in the derivation |
| Inviscid       | ✅        | Viscosity must be neglected (Euler equation) |
| Along streamline | ✅      | Derivation is valid **only along streamlines** unless further assumptions are made |
| Irrotational   | ❌        | Only required if Bernoulli is to be used **between any two points**, not just along a streamline |
| Incompressible | ✅        | Needed for the form involving \( \frac{p}{\rho} \). Compressible Bernoulli equation has a different form |

---

## 🧪 Evaluation of Options

### (a) Irrotational  
❌ Not required to use Bernoulli **along a streamline**.  
✅ **Correct answer**.

### (b) Incompressible  
✅ Required unless a compressible form of Bernoulli is derived separately.

### (c) Inviscid  
✅ Required. Viscous forces break the assumptions leading to Bernoulli.

### (d) Steady-state  
✅ Required. Otherwise, the unsteady Bernoulli equation must be used.

---

## ✅ Final Answer

\[
\boxed{\text{(a) Irrotational}}
\]
