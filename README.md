Solving the exact DE:

Given: (y^3 - y^2 sin(x) - x)dx + (3xy^2 + 2y cos(x))dy = 0

1. Verify exactness:
P = y^3 - y^2 sin(x) - x
Q = 3xy^2 + 2y cos(x)

∂P/∂y = 3y^2 - 2y sin(x)
∂Q/∂x = 3y^2 - 2y sin(x)

Since ∂P/∂y = ∂Q/∂x, the equation is exact.

2. Find potential function f(x, y):
∫P dx = ∫(y^3 - y^2 sin(x) - x) dx
f(x, y) = xy^3 - y^2 cos(x) - x^2/2 + g(y)

3. Differentiate f(x, y) w.r.t y and set to Q:
∂f/∂y = 3xy^2 - 2y cos(x) + g'(y)
3xy^2 - 2y cos(x) + g'(y) = 3xy^2 + 2y cos(x)

4. Solve for g'(y):
g'(y) = 0
g(y) = C

5. General solution:
f(x, y) = xy^3 - y^2 cos(x) - x^2/2 + C
Solution: xy^3 - y^2 cos(x) - x^2/2 = C
