## About:

The big X letter, symbolize the input matrix that contains the input data from the training set, S.
The line i represents an [[Input vector]], $x^{(i)}$, $1 \le i \le m$.
The column j, corresponds to a feature, $1 \le j \le n$.

## Notation:

$$X = \left[ \matrix{x_1^{(1)} \space \space x_2^{(1)} \space \space ... \space \space x_n^{(1)} \\ x_1^{(2)} \space \space x_2^{(2)} \space \space ... \space \space x_n^{(2)} \\ . \space \space . \space \space . \\ x_1^{(m)} \space x_2^{(m)} \space ... \space x_n^{(m)}} \right]$$

In practice, this matrix has an additional column filled with 1s, that will allow the free term to exist:

$$X = \left[ \matrix{1 \space \space x_1^{(1)} \space \space x_2^{(1)} \space \space ... \space \space x_n^{(1)} \\ 1 \space \space x_1^{(2)} \space \space x_2^{(2)} \space \space ... \space \space x_n^{(2)} \\ . \space \space . \space \space . \\ 1 \space \space x_1^{(m)} \space x_2^{(m)} \space ... \space x_n^{(m)}} \right]$$
