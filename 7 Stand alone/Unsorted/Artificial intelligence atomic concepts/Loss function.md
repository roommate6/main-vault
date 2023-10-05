## About:

This function returns a value that is interpreted as a bad score for the model. If this function returns big numbers, it means that the model is not well trained, if the function returns small numbers, it mean that the model is ready and good to be used for any input values. The ideal value of the function's return is 0, this mean that the function is giving the exact output for the given input, without any erros.

## Notation:

$$\displaylines{J(\theta) = \frac{1}{2m} \sum_{i=1}^m (\hat y^{(i)} - y^{(i)})^2 \\
= \frac{1}{2m} \sum_{i=1}^m (h_\theta(x^{(i)}) - y^{(i)})^2 \\
= \frac{1}{2m} \sum_{i=1}^m (\theta^t \cdot x^{(i)} - y^{(i)})^2 \\
= \frac{1}{2m} (X\theta - Y)^t (X\theta - Y)}$$

The loss function can be rewrited as:

$$\displaylines{ = \frac{1}{2m} (X\theta - Y)^t (X\theta - Y) \\
= \frac{1}{2m} ((X\theta)^t - Y^t) (X\theta - Y) \\ 
= \frac{1}{2m} ((X\theta)^tX\theta - (X\theta)^tY - Y^tX\theta + Y^tY) \\
= \frac{1}{2m} (\theta^tX^tX\theta - \theta^tX^tY - Y^tX\theta + Y^tY), \text{ and because} \\ Y^tX\theta \text{ is an 1 x 1 matrix;} \\
= \frac{1}{2m} (\theta^tX^tX\theta - \theta^tX^tY - (Y^tX\theta)^t + Y^tY) \\
= \frac{1}{2m} (\theta^tX^tX\theta - \theta^tX^tY - \theta^tX^t(Y^t)^t + Y^tY) \\
= \frac{1}{2m} (\theta^tX^tX\theta - \theta^tX^tY - \theta^tX^tY + Y^tY) \\
=\frac{1}{2m} (\theta^tX^tX\theta - 2\theta^tX^tY + Y^tY) }$$
