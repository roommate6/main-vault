## Page:
[[Discrete mathematical structures.pdf#page=86]]

## Solution:

### Exercise 1:
In Exercises 1 through 12, prove that the statement is true by using mathematical induction.
2 + 4 + 6 + ... + 2n = n(n + 1)
For this sum of elements of the sequence of the form 2, 4, 6, ... to exist, n should be greater or equal to 1. So, if P(n) : 2 + 4 + ... + 2n = n(n + 1) is the predicate that we have to prove, then $n_0$ = 1, and the P(n) should be proven for all n $\ge$ 1.
Basis step: P(1) : 2 * 1 = 1(1 + 1) <=> 2 = 1 * (2) <=> 2 = 2 which is true.
Induction step:
Suppose that P(k) is true for all k $\ge$ 1, then P(k + 1) is true.
P(k) : 2 + 4 + 6 + ... + 2k = k(k + 1)
P(k + 1) : 2 + 4 + 6 + ... + 2k + 2(k+1) = (k + 1)((k + 1) + 1) <=>
k(k + 1) + 2(k + 1) = (k + 1)(k + 2) <=>
(k + 1)(k + 2) = (k + 1)(k + 2), which is true.
Therefore, by the principle of mathematical induction, P(n) is true for all n $\ge$ 1. $\color{green}{\square}$

### Exercise 2:
$1^2 + 3^2 + 5^2 + ... + (2n - 1)^2 = \frac{n(2n + 1)(2n - 1)}{3}$
Suppose that this is true for all n $\ge$ 1, then we have to prove this by mathematical induction.
Let P(n) : $1^2 + 3^2 + 5^2 + ... + (2n - 1)^2 = \frac{n(2n + 1)(2n - 1)}{3}$, with n $\ge$ 1.
Basis step: since $n_0 = 1$, P(1) : $(2*1 - 1)^2 = \frac{1(2*1 + 1)(2 * 1 - 1)}{3}$ <=>
$1^2 = \frac{1 * 3 * 1}{3}$ <=> 1 = 1 which is true.
Induction step:
Suppose that P(k) is true for all k $\ge$ 1, then P(k + 1) is true.
P(k) : $1^2 + 3^2 + 5^2 + ... + (2k - 1)^2 = \frac{k(2k + 1)(2k - 1)}{3}$
P(k + 1) : $1^2 + 3^2 + 5^2 + ... + (2(k + 1) - 1)^2 = \frac{(k + 1)(2(k + 1) + 1)(2(k + 1) - 1)}{3}$ <=>
P(k + 1) : $1^2 + 3^2 + 5^2 + ... + (2k + 2 - 1)^2 = \frac{(k + 1)(2k + 2 + 1)(2k + 2 - 1)}{3}$ <=>
P(k + 1) : $1^2 + 3^2 + 5^2 + ... + (2k + 1)^2 = \frac{(k + 1)(2k + 2 + 1)(2k + 2 - 1)}{3}$ <=>
P(k + 1) : $1^2 + 3^2 + 5^2 + ... + (2k - 1)^2 + (2k + 1)^2 = \frac{(k + 1)(2k + 2 + 1)(2k + 2 - 1)}{3}$ <=>
P(k + 1) : $\frac{k(2k + 1)(2k - 1)}{3} + (2k + 1)^2 = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{k(2k + 1)(2k - 1) + 3(2k + 1)^2}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)(k(2k-1) + 3(2k + 1))}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)(k(2k - 1) + 6k + 3)}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)(k(2k - 1) + 2k - 1 + 4k + 4)}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)((2k - 1)(k + 1) + 4k + 4)}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)((k + 1)(2k - 1) + 4(k + 1))}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)(k + 1)(2k - 1 + 4)}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$ <=>
P(k + 1) : $\frac{(2k + 1)(k + 1)(2k + 3)}{3} = \frac{(k + 1)(2k + 3)(2k + 1)}{3}$, which is true.
Therefore, by the principle of mathematical induction, P(n) is true for all n $\ge$ 1. $\color{green}{\square}$

### Exercise 3:
![[Draft_02-08-2023_14.23.40.excalidraw]]

### Exercise 4:
![[Draft_02-08-2023_14.46.51.excalidraw]]

### Exercise 5:
![[Draft_02-08-2023_15.00.15.excalidraw]]

### Exercise 6:
![[Draft_03-08-2023_11.22.13.excalidraw]]

### Exercise 7:
![[Draft_03-08-2023_11.53.56.excalidraw]]

### Exercise 8:
![[Draft_03-08-2023_12.05.00.excalidraw]]

### Exercise 9:
![[Draft_03-08-2023_12.48.46.excalidraw]]

### Exercise 10:
![[Draft_03-08-2023_13.01.08.excalidraw]]

### Exercise 11:
![[Draft_03-08-2023_13.10.13.excalidraw]]

### Exercise 12:
![[Draft_03-08-2023_13.24.16.excalidraw]]

### Exercise 13:
![[Draft_03-08-2023_13.39.48.excalidraw]]

### Exercise 14:
![[Draft_03-08-2023_14.06.57.excalidraw]]

### Exercise 15:
![[Draft_03-08-2023_14.42.51.excalidraw]]

### Exercise 16:
![[Draft_04-08-2023_10.50.40.excalidraw]]

### Exercise 17:
![[Draft_04-08-2023_10.50.59.excalidraw]]

### Exercise 18:
![[Draft_04-08-2023_10.52.57.excalidraw]]

### Exercise 19:
![[Draft_04-08-2023_10.53.16.excalidraw]]

### Exercise 20:
![[Draft_04-08-2023_10.53.42.excalidraw]]

### Exercise 21:
![[Draft_04-08-2023_10.54.05.excalidraw]]

### Exercise 22:
![[Draft_04-08-2023_10.54.20.excalidraw]]

### Exercise 23:
![[Draft_04-08-2023_10.54.43.excalidraw]]

### Exercise 24:
![[Draft_04-08-2023_10.54.58.excalidraw]]

### Exercise 25:
![[Draft_04-08-2023_10.55.10.excalidraw]]

### Exercise 26:
![[Draft_04-08-2023_10.55.35.excalidraw]]

### Exercise 27:
![[Draft_04-08-2023_10.55.51.excalidraw]]

### Exercise 28:
![[Draft_04-08-2023_10.56.06.excalidraw]]

### Exercise 29:
![[Draft_04-08-2023_10.56.21.excalidraw]]

### Exercise 30:
![[Draft_04-08-2023_10.56.33.excalidraw]]
