
# Derivation of the Vorticity Equation in a Rotating Frame

We derive the vorticity equation from the **Navier–Stokes equations** expressed in **primitive variables**: velocity $\mathbf{v}$ and pressure $p$, in a **non-inertial rotating frame** with constant angular velocity $\boldsymbol{\Omega}$.

We assume:
- Incompressible flow: $\nabla \cdot \mathbf{v} = 0$
- Constant viscosity $\mu$ and density $\rho$
- Rotation is with respect to an inertial frame

---

## Step 1: Navier–Stokes in Rotating Frame

In a rotating reference frame, the Navier–Stokes equation is:

$$
\frac{D \mathbf{v}}{D t} = -\frac{1}{\rho} \nabla p + \nu \nabla^2 \mathbf{v} - 2\boldsymbol{\Omega} \times \mathbf{v} - \boldsymbol{\Omega} \times (\boldsymbol{\Omega} \times \mathbf{r}) - \frac{d \boldsymbol{\Omega}}{dt} \times \mathbf{r}
$$

Here:
- $-2\boldsymbol{\Omega} \times \mathbf{v}$: Coriolis force
- $-\boldsymbol{\Omega} \times (\boldsymbol{\Omega} \times \mathbf{r})$: centrifugal force
- $-\frac{d\boldsymbol{\Omega}}{dt} \times \mathbf{r}$: Euler force (appears if $\boldsymbol{\Omega}$ is time-dependent)

We now focus on the evolution of **vorticity**.

---

## Step 2: Vorticity Definition

Define the **vorticity vector** as:

$$
\boldsymbol{\omega} = \nabla \times \mathbf{v}
$$

Take the curl of both sides of the momentum equation:

---

## Step 3: Take Curl of Navier–Stokes

The terms become:

- $\nabla \times \frac{D\mathbf{v}}{Dt} = \frac{D \boldsymbol{\omega}}{D t} - \boldsymbol{\omega} \cdot \nabla \mathbf{v} + \mathbf{v} \cdot \nabla \boldsymbol{\omega}$  
(using vector identities and incompressibility)

- $\nabla \times \left( -\frac{1}{\rho} \nabla p \right) = 0$

- $\nabla \times (\nu \nabla^2 \mathbf{v}) = \nu \nabla^2 \boldsymbol{\omega}$

- $\nabla \times ( -2\boldsymbol{\Omega} \times \mathbf{v}) = -2 (\boldsymbol{\Omega} \cdot \nabla)\mathbf{v} + 2 (\mathbf{v} \cdot \nabla)\boldsymbol{\Omega}$

If $\boldsymbol{\Omega}$ is constant in space and time, the last term vanishes.

---

## Step 4: Final Vorticity Equation (Rotating Frame)

Combining all terms:

$$
\frac{\partial \boldsymbol{\omega}}{\partial t} + (\mathbf{v} \cdot \nabla) \boldsymbol{\omega} = (\boldsymbol{\omega} + 2\boldsymbol{\Omega}) \cdot \nabla \mathbf{v} - (\boldsymbol{\omega} + 2\boldsymbol{\Omega})(\nabla \cdot \mathbf{v}) + \nu \nabla^2 \boldsymbol{\omega}
$$

If the flow is incompressible: $\nabla \cdot \mathbf{v} = 0$.

Then:

$$
\frac{D \boldsymbol{\omega}}{D t} = (\boldsymbol{\omega} + 2\boldsymbol{\Omega}) \cdot \nabla \mathbf{v} + \nu \nabla^2 \boldsymbol{\omega}
$$

This shows that the **absolute vorticity** $\boldsymbol{\omega} + 2\boldsymbol{\Omega}$ plays the role of effective rotation in a rotating frame.

---

## Step 5: Generalization for Non-constant $\boldsymbol{\Omega}(t)$

If the rotation rate $\boldsymbol{\Omega}$ changes with time, we must include the **Euler force** and account for:

$$
\frac{d}{dt}(2\boldsymbol{\Omega}) \cdot \nabla \mathbf{v}
$$

This introduces additional time-dependent source terms in the vorticity dynamics.

---

## Conclusion

The vorticity equation in a rotating frame shows how both **local rotation (vorticity)** and **planetary rotation (Coriolis term)** combine to determine the flow's evolution. Even if $\boldsymbol{\omega} = 0$ initially, the Coriolis term can inject rotation.
