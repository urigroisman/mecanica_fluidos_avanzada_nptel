## Problem 2

We are given the differential equation:

$$
x^2 y'' + 5x y' + 3y = \ln(x), \quad x > 0
$$

Let us try a change of variable: $x = e^t$, then $y(x) = Y(t)$.

Using known transformation rules:

- $\frac{dy}{dx} = \frac{1}{x} \frac{dY}{dt}$
- $\frac{d^2y}{dx^2} = \frac{1}{x^2} \left( \frac{d^2Y}{dt^2} - \frac{dY}{dt} \right)$

Substitute into the equation and simplify. Eventually, the solution becomes:

$$
y(x) = A e^{-x} + B e^{-3x} + \frac{x}{3} - \frac{4}{9}
$$

### ✅ Final Answer: (d)