# Equation Solver

A Python package for solving and analyzing linear and quadratic equations.

## Features

- Solve linear equations (ax + b = 0)
- Solve quadratic equations (ax² + bx + c = 0) 
- Detailed equation analysis (slopes, intercepts, concavity, etc.)
- Clean string representation of equations
- Type checking and input validation

## Installation

```bash
pip install equation-solver
```
## Usage
**Example**
```bash
from equation_solver import LinearEquation, QuadraticEquation, solver

# Create and solve equations
lin = LinearEquation(2, 3)  # 2x + 3 = 0
quad = QuadraticEquation(1, -5, 6)  # x² -5x + 6 = 0

print(solver(lin))
print(solver(quad))

# Direct access to solutions
print(lin.solve())  # [-1.5]
print(quad.solve())  # [3.0, 2.0]

# Equation analysis
print(lin.analyze())  # {'slope': 2, 'intercept': 3}
print(quad.analyze())  # Vertex, concavity info
```
**Output Format**
**Solutions are presented in a clean format:**
```bash
---Linear Equation---

       2x +3 = 0        

-------Solutions-------

       x = -1.500       

-------Details-------

slope =            2.000
y-intercept =      3.000
```
## Requirements
Python 3.8+

No external dependencies

## Contributing
Pull requests welcome! Please include tests for new features.

## Support

If you find this project useful and would like to support its development, you can:

⭐ **Star the Repository:** Show your appreciation by starring this project on GitHub.

💬 **Provide Feedback:** Open an issue or discussion to share your thoughts or suggestions.

🤍 **Donate via PayPal:** If you'd like to support me financially, you can donate via PayPal:
[![PayPal](https://img.shields.io/badge/Donate-PayPal-blue?logo=paypal)](https://paypal.me/basic1man?country.x=MA&locale.x=en_US)


## Author

**Mohamed Moukbil**
