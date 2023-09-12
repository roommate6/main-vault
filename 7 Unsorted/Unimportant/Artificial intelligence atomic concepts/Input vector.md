## About:

The input vector is a column vector that stores the fetures that the input object have.

## Notation:

$$x^{(i)}, 1 \le i \le m$$

m - represents the total number of input vectors from the training set.
(i) - represents the index of a vector from the data set.

Such vector contains n numerical values, called features:

$$x^{(i)} = (x_1^{(i)}, x_2^{(i)}, \text{...}, x_n^{(i)})^t$$

In practice, x has an additional column, with value 1, allowing the model to have a free term, $\theta_0$, that will offset all the values of the model by a certan amount:

$$x^{(i)} = (x_0^{(i)} = 1, x_1^{(i)}, x_2^{(i)}, \text{...}, x_n^{(i)})^t \in R^{n+1}$$ ^2c331e
