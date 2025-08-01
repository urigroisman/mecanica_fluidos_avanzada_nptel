
# Week 02 – Problem 2: Pressure Difference in a Stratified Stationary Fluid

## 🧮 Problem Statement

The density of a fluid mixture $\rho$ (in kg/m³) in a chemical reactor varies with the vertical distance $z$ (in meters) above the bottom of the reactor according to:

$$
\rho(z) = 10.1 \left[1 - \frac{z}{500} + \left( \frac{z}{1000} \right)^2 \right]
$$

Assuming the mixture is stationary, determine the pressure difference between the **bottom** and **top** of a **60 m tall reactor**.

---

## 🧠 Step 1: Governing Equation

In a **stationary fluid**, the pressure satisfies the **hydrostatic balance**:

$$
\frac{dp}{dz} = -\rho(z) g
$$

So, integrating from $z = 0$ to $z = 60$ m:

$$
p(60) - p(0) = -\int_0^{60} \rho(z) g \, dz
$$

Thus, the pressure difference is:

$$
\Delta p = p(0) - p(60) = \int_0^{60} \rho(z) g \, dz
$$

---

## 📋 Step 2: Density Profile

We are given:

$$
\rho(z) = 10.1 \left(1 - \frac{z}{500} + \left( \frac{z}{1000} \right)^2 \right)
$$

---

## 📐 Step 3: Analytical Integration

We compute:

$$
\Delta p = 10.1 \cdot g \int_0^{60} \left(1 - \frac{z}{500} + \frac{z^2}{10^6} \right) dz
$$

### Integrals:

- $\int_0^{60} 1 \, dz = 60$
- $\int_0^{60} \frac{z}{500} \, dz = \frac{1}{500} \cdot \frac{60^2}{2} = 3.6$
- $\int_0^{60} \frac{z^2}{10^6} \, dz = \frac{1}{10^6} \cdot \frac{60^3}{3} = 0.072$

Thus:

$$
\Delta p = 10.1 \cdot g \cdot (60 - 3.6 + 0.072) = 10.1 \cdot g \cdot 56.472
$$

Using $g = 9.81$ m/s²:

$$
\Delta p \approx 10.1 \cdot 9.81 \cdot 56.472 \approx 5594.73 \, \text{Pa}
$$

---

## ✅ Final Answer:

\[
\boxed{\Delta p \approx 5.59 \, \text{kPa}} \quad \text{(Option d)}
\]
