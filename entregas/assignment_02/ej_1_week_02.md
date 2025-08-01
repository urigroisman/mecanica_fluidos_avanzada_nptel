
# Week 02 – Problem 1: Conceptual Question on Vorticity and Rotation

## Problem Statement

**Which of the following statements is correct?**

(a) Fluid flow past a solid surface is always irrotational  
(b) Coriolis force can turn an irrotational flow into a rotational flow  
(c) Coriolis force can turn a rotational flow into an irrotational flow  
(d) Thermal stratification ensures that an irrotational flow remains irrotational

---

## Analysis of Each Statement

### (a) Fluid flow past a solid surface is always irrotational

❌ **Incorrect.**  
This is physically false. Near solid surfaces, **viscous effects dominate**, and the **no-slip boundary condition** implies **non-zero vorticity** (i.e., the flow is rotational). In fact, **vorticity is generated at solid boundaries** and diffuses into the fluid.

> In boundary layers, the vorticity is very strong and plays a fundamental role in the dynamics of the flow.

---

### (b) Coriolis force can turn an irrotational flow into a rotational flow

✅ **Correct.**  

This is the **true** statement. Let's explore this in detail.

#### Coriolis Force and Vorticity Equation

In a rotating reference frame, the vorticity equation for an inviscid, barotropic fluid is:

$$
\frac{D \boldsymbol{\omega}}{D t} = (\boldsymbol{\omega} + 2\boldsymbol{\Omega}) \cdot \nabla \mathbf{u} - (\nabla \cdot \mathbf{u})(\boldsymbol{\omega} + 2\boldsymbol{\Omega})
$$

Even if the initial flow is irrotational, i.e., $\boldsymbol{\omega} = 0$, the term $2\boldsymbol{\Omega} \cdot \nabla \mathbf{u}$ may generate **non-zero vorticity** in time. Hence:

> The **Coriolis force** can indeed **induce rotation** in an initially irrotational flow.

A classical example is in **geophysical flows** like the ocean or atmosphere: the Earth’s rotation induces vorticity in large-scale flows through the Coriolis effect.

---

### (c) Coriolis force can turn a rotational flow into an irrotational flow

❌ **Incorrect.**  
The Coriolis force **does not remove vorticity**. It can generate or redistribute it, but it **cannot cancel it out** in general. Once a flow has vorticity (is rotational), the Coriolis force alone **will not make it irrotational**.

---

### (d) Thermal stratification ensures that an irrotational flow remains irrotational

❌ **Incorrect.**  
Thermal stratification introduces **buoyancy effects** that can create **baroclinic torques**.

In the presence of a temperature gradient, and when **density is a function of temperature**, the term:

$$
\frac{1}{\rho^2} \nabla \rho \times \nabla p
$$

can be **non-zero**, even in the absence of viscosity, thus **generating vorticity**. This is especially important in **stratified fluids**, where temperature (and hence density) varies with position.

> Therefore, thermal stratification **can create vorticity** and **invalidate** the assumption of irrotationality.

---

## ✅ Final Answer

**(b) Coriolis force can turn an irrotational flow into a rotational flow.**
