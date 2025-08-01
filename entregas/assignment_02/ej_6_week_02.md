
# Week 02 – Problem 6: Water Draining from a Cylindrical Tank

## 🍰 One more piece of cake — but we’ll frost it with physics!

We’re asked to determine the **instantaneous rate of change of the water depth** \( \frac{dh}{dt} \) in a cylindrical tank as water flows out the bottom.

---

## 🧮 Problem Setup

- **Tank shape**: Vertical cylinder  
- **Tank diameter**: \( D \)  
- **Water depth**: \( h(t) \)  
- **Outflow hole area**: \( A_0 \)  
- **Outflow velocity**: \( V_0 \)  
- **Goal**: Find \( \frac{dh}{dt} \)

---

## 🧠 Step 1: Conservation of Volume (Mass)

For an **incompressible fluid**, the **rate of volume change** inside the tank equals the **volumetric flow rate out**:

\[
\frac{dV}{dt} = -Q_{\text{out}} = -A_0 V_0
\]

---

## 🧊 Step 2: Volume of Water in the Tank

\[
V = A_{\text{tank}} \cdot h = \left( \frac{\pi D^2}{4} \right) h
\]

Differentiate:

\[
\frac{dV}{dt} = \frac{\pi D^2}{4} \cdot \frac{dh}{dt}
\]

---

## 🧮 Step 3: Equating Rates

\[
\frac{\pi D^2}{4} \cdot \frac{dh}{dt} = -A_0 V_0
\quad \Rightarrow \quad
\frac{dh}{dt} = -\frac{4 A_0 V_0}{\pi D^2}
\]

---

## ✅ Final Answer

\[
\boxed{ \frac{dh}{dt} = -\frac{4 A_0 V_0}{\pi D^2} } \quad \text{(option d)}
\]

Sweet, simple, and served with conservation laws!
