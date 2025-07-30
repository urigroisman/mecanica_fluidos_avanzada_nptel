
## Problem 8 – Locus of a Fluid Particle

**Given**:
- Velocity field:
  \[
  u = 0, \quad v = \frac{y}{t + t_0}, \quad w = 0
  \]
- A coloured particle is injected at \( A(x_0, y_0, z_0) \) at time \( t = t_0 \)

**Find**: The equation of the *pathline* (locus of particle) that passes through this point at \( t = t_0 \)

---

### Step 1: Particle position equations

From:
- \( u = \frac{dx}{dt} = 0 \Rightarrow x(t) = x_0 \)
- \( w = \frac{dz}{dt} = 0 \Rightarrow z(t) = z_0 \)

So, only \( y \) varies.

We solve:

\[
\frac{dy}{dt} = \frac{y}{t + t_0}
\Rightarrow \frac{dy}{y} = \frac{dt}{t + t_0}
\]

Integrate both sides:

\[
\int \frac{1}{y} \, dy = \int \frac{1}{t + t_0} \, dt
\Rightarrow \ln y = \ln(t + t_0) + C
\Rightarrow y = C_1 (t + t_0)
\]

Use initial condition: \( y(t_0) = y_0 \Rightarrow y_0 = C_1 (2t_0) \Rightarrow C_1 = \frac{y_0}{2t_0} \)

Hence:
\[
y(t) = \frac{y_0}{2t_0}(t + t_0)
\]

---

### Step 2: Eliminate time

From \( x = x_0 \), and expression above:

\[
\Rightarrow \frac{y}{y_0} = \frac{t + t_0}{2t_0}
\Rightarrow \frac{y - y_0}{2t_0} = \frac{t - t_0}{2t_0}
\Rightarrow t = \frac{y - y_0}{2t_0} + t_0
\]

Now plug into:
\[
x = x_0 \Rightarrow \frac{x}{x_0} = 1
\]

Final equation:

\[
\boxed{\frac{x}{x_0} - \frac{y - y_0}{2t_0 v_0} = 1}
\]

---

### ✅ Final Answer:
\[
\boxed{\text{(a)} \quad \frac{x}{x_0} - \frac{y - y_0}{2t_0 v_0} = 1}
\]
