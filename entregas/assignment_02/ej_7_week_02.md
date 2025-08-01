
# Week 02 – Problem 7: Interpretation of the Reynolds Transport Theorem (RTT)

## 🧮 Problem Statement

Consider the following statements:

1. Reynolds Transport Theorem (RTT) is valid for both solids and fluids.  
2. Reynolds Transport Theorem (RTT) is valid only for fluids.  
3. Reynolds Transport Theorem (RTT) for the conservation of linear momentum makes use of Newton’s second law of motion.  
4. The given form of RTT is valid for a non-deformable control volume.  

We are given the mass form of RTT:

\[
\frac{dm}{dt}\Big|_{\text{sys}} = \int_{\text{CV}} \frac{\partial \rho}{\partial t} \, dV + \int_{\text{CS}} \rho \vec{V} \cdot \vec{n} \, dA
\]

---

## 🔍 Statement-by-Statement Analysis

### ✅ Statement 1: RTT is valid for both solids and fluids  
**True.** RTT is a general kinematic theorem derived from the Leibniz integral rule and Gauss’s divergence theorem. It applies to any continuum, not just fluids.

---

### ❌ Statement 2: RTT is valid only for fluids  
**False.** See statement 1. Solids can be analyzed using RTT as well.

---

### ⚠️ Statement 3: RTT for linear momentum makes use of Newton’s second law  
**Not accurate.**  
RTT is purely kinematic. When applied to linear momentum:

\[
\frac{d}{dt} \int_{\text{sys}} \rho \vec{V} \, dV
= \frac{d}{dt} \int_{\text{CV}} \rho \vec{V} \, dV + \int_{\text{CS}} \rho \vec{V} (\vec{V} \cdot \vec{n}) \, dA
\]

This only **rewrites** the material derivative of momentum from a system to a control volume. It does **not** invoke Newton’s second law. Newton’s second law comes **afterward**, when we assume:

\[
\frac{d\vec{p}}{dt}_{\text{sys}} = \vec{F}_{\text{net}}
\]

So, **RTT enables** the application of Newton’s law, but **does not make use of it** intrinsically. Therefore, the statement is **imprecise** and should be marked **false** in a strict reading.

---

### ✅ Statement 4: The given form of RTT is valid for a non-deformable control volume  
**True.**  
The integral form shown is derived assuming a **fixed control volume** in space (i.e., non-deforming and stationary), allowing the use of the standard Reynolds transport identity.

---

## ✅ Final Answer

\[
\boxed{\text{(a) 1 and 4}}
\]

We exclude statement 3 due to its conceptual ambiguity and sloppy phrasing.
