
# Week 02 – Problem 3: Velocity from Piezometer and Pitot Tube Readings

## 🧮 Problem Statement

A piezometer measures **static pressure head**, and a Pitot tube measures the **total pressure head**. Both are connected to a 5 cm diameter horizontal water pipe.

- Height of water column in piezometer: \( h_s = 16 \, \text{cm} \)
- Height of water column in Pitot tube: \( h_t = 36 \, \text{cm} \)
- Assume: \( g = 10 \, \text{m/s}^2 \)

**Determine the velocity at the center of the pipe.**

---

## 🧠 Physical Principle

Use **Bernoulli’s equation** for incompressible, steady flow between a point in the free stream and a stagnation point:

\[
p + \frac{1}{2} \rho v^2 = p_0
\]

This implies:

\[
v = \sqrt{2g(h_t - h_s)}
\]

where:

- \( h_t \): total head from Pitot tube
- \( h_s \): static head from piezometer

---

## 📐 Step-by-Step Calculation

Given:
- \( h_t = 0.36 \, \text{m} \)
- \( h_s = 0.16 \, \text{m} \)
- \( g = 10 \, \text{m/s}^2 \)

\[
\Delta h = h_t - h_s = 0.36 - 0.16 = 0.20 \, \text{m}
\]

\[
v = \sqrt{2 \cdot 10 \cdot 0.20} = \sqrt{4} = 2 \, \text{m/s}
\]

---

## ✅ Final Answer

\[
\boxed{v = 2 \, \text{m/s}} \quad \text{(Option b)}
\]
