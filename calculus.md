## Calculus: Notes

**1. How is a mathematical function defined in the context of calculus?** 
<details>
  <summary>Expand to see Answer</summary>
  
A function is a relation between two sets that associates every element of one set to exactly one element of the other. It formalizes how a dependent variable varies with respect to an independent variable, often expressed in the notation y = f(x).
</details>

**2. What is the geometric interpretation of a derivative?** 
<details>
  <summary>Expand</summary>

Geometrically, the derivative f'(x) is interpreted as the slope of the line tangent to the function f(x) at a specific point x. It represents the instantaneous rate of change of the function at that single instant.
</details>

**3. What is the relationship between the continuity of a function and its differentiability?**
<details>
  <summary>Expand</summary>

To be differentiable at a point, a function must be continuous at that point, as a limit cannot exist otherwise. however, being continuous everywhere does not guarantee differentiability everywhere; for example, if the left and right-hand limits of the derivative quotient do not agree at a point, the derivative is undefined.
</details>

**4. Explain the "Product Rule" for differentiation.**
<details>
  <summary>Expand</summary>

The product rule is a method used to find the derivative of a function that is the product of two other functions, f(x) = u(x) \cdot v(x). The formula states that the derivative is the first function times the derivative of the second, plus the second function times the derivative of the first (f' = uv' + vu').
</details>

**5. What are stationary points, and how are they identified?** 
<details>
  <summary>Expand</summary>
  
Stationary points are points on a function where the first derivative is equal to zero (f'(a) = 0). At these points, the line tangent to the graph is horizontal, indicating a potential local maximum, minimum, or saddle point.
</details>

**6. Under what conditions does a stationary point represent a local minimum?**
<details>
  <summary>Expand</summary>
  
A function has a local minimum at a stationary point x = a if it satisfies both a necessary and a sufficient condition. The necessary condition is that f'(a) = 0, and the sufficient condition is that the second derivative is greater than zero (f''(a) > 0).
</details>

**7. What is the primary purpose of using Taylor polynomials?** 
<details>
  <summary>Expand</summary>
  
Taylor polynomials are used to approximate complicated, infinitely differentiable functions (like trigonometric or exponential functions) using simpler polynomial functions. These approximations are highly accurate near a specific expansion point, such as x_0 = 0, making complex calculations more efficient for tools like pocket calculators.
</details>

**8. How does the Fundamental Theorem of Calculus connect differentiation and integration?** 
<details>
  <summary>Expand</summary>
  
The theorem establishes that differentiation and integration are inverse operations, meaning the derivative of an integral returns the original integrand. It also provides a method to evaluate definite integrals by using the antiderivative: \int_{a}^{b} f(x) \, dx = F(b) - F(a).
</details>

**9. What does a double integral represent geometrically?** 
<details>
  <summary>Expand</summary>
  
While a single integral represents the area under a curve, a double integral of a positive function f(x, y) represents the volume between the surface defined by the function and a specific area R in the xy-plane. It is calculated by performing two nested single integrals.
</details>

**10. Define a partial derivative and describe its notation.** 
<details>
  <summary>Expand</summary>
  
A partial derivative measures the rate of change of a multivariate function with respect to one variable while holding all other variables constant. It is denoted using the symbol \partial (e.g., \frac{\partial f}{\partial x}), indicating that only a "partial" change of the function is being observed along one axis.
</details>