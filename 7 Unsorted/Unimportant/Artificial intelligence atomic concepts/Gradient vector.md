## About:

The gradient vector is a column vector containing all the partial derivatives of the loss function.

## Notation:

$$\nabla_\theta J = \left[ \matrix{\frac{\partial}{\partial \theta_0}J \\ \frac{\partial}{\partial \theta_1}J \\ ... \\ \frac{\partial}{\partial \theta_n}J} \right]$$

And because, the partial derivative is a linear operator, the partial derivative of a function summation, is the sum of the functions partial derivatives:

$$\nabla_\theta J(\theta) = \frac{1}{2m} [\nabla_\theta(\theta^tX^tX\theta - 2\nabla_\theta (\theta^tX^tY)) + \nabla_\theta(Y^tY)]$$

And because $Y^tY$ does not depend on $\theta$, we obtain the gradient vector:

$$\nabla_\theta J(\theta) = \frac{1}{m} (X^tX\theta - X^tY) = \frac{1}{m} X^t (X\theta - Y)$$ ^9b391b
