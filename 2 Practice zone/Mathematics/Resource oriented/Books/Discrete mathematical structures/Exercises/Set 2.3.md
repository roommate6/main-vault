## Page:
[[Discrete mathematical structures.pdf#page=81]]

## Solution:

### Exercise 1:
![[Pasted image 20230729144415.png]]
Let q: I drive to work, r: I arrive tired.
((q $\to$ r) $\land$ ~r)  $\to$ ~q is a tautology, and is true for all values of q and r. Therefore, the argument is valid.

### Exercise 2:
![[Pasted image 20230729171408.png]]
Invalid: ((q $\to$ r) $\land$ r)  $\to$ q is false for q false and r true.

### Exercise 3:
![[Pasted image 20230729172329.png]]
Invalid: ((q $\to$ r) $\land$ ~q) $\to$ ~r is false for q false and r true.

### Exercise 4:
![[Pasted image 20230729172833.png]]
Valid: ((q $\to$ r) $\land$ q) $\to$ r is tautology.

### Exercise 5:
![[Pasted image 20230729173310.png]]
p: I become famous, r: I become a writer.
Valid: ((p $\lor$ ~r) $\land$ r) $\to$ p is tautology.

### Exercise 6:
![[Pasted image 20230729173926.png]]
Valid: ((p $\lor$ r) $\land$ ~r) $\to$ p is tautology.

### Exercise 7:
![[Pasted image 20230729174220.png]]
q: I try hard, p: I have talent, r: I become musician, s: I am happy
Valid: (((q $\land$ p) $\to$ r) $\land$ (r $\to$ s)) $\to$ (~s $\to$ (~q $\lor$ ~p)) $\leftrightarrow$ (q $\land$ p) $\to$ s

### Exercise 8:
![[Pasted image 20230729175002.png]]
(a) If a and b are two even numbers, then a = 2$k_a$ and b = 2$k_b$, where $k_a \space and \space k_b$ are two integers. a + b = 2$k_a$ + 2$k_b$ = 2($k_a + k_b$) which is even as well. $\color{green}{\square}$
(b) If a and b are two odd numbers, then a = 2$k_a + 1$ and b = 2$k_b + 1$, where $k_a \space and \space k_b$ are two integers. a + b = $2k_a + 1 + 2k_b + 1$ = $2k_a + 2k_b + 2$ = 2($k_a + k_b + 1$) which is even. $\color{green}{\square}$

### Exercise 9:
![[Pasted image 20230729201250.png]]
(a) If a and b are two even integers, then a = 2$k_a$ and b = 2$k_b$, where $k_a \space and \space k_b$ are two integers. ab =  $2k_a2k_b$ = $4k_ak_b$ = $2(2k_ak_b)$ which is even. $\color{green}{\square}$
(b) If a and b are two odd integers, then a = 2$k_a$ + 1 and b = 2$k_b$ + 1, where $k_a \space and \space k_b$ are two integers. ab = $(2k_a + 1)(2k_b + 1)$ = $4k_ak_b + 2k_a + 2k_b + 1$ = $2(2k_ak_b + k_a + k_b) + 1$ which is odd. $\color{green}{\square}$

### Exercise 10:
![[Pasted image 20230729201927.png]]
Let q: $n^2$ is even and p: n is even. To prove q $\leftrightarrow$ p, we first prove p $\to$ q, then q $\to$ p. If n is even, then n = 2k, where k is an integer. $n^2 = 2k2k = 4k^2 = 2(2k^2)$ which is even, so p $\to$ q. If we prove ~p $\to$ ~q, which is the contrapositive of q $\to$ p, then we are done with the proof of the main statement. If n is odd, then n = 2k + 1, where k is an integer. $n^2$ = (2k + 1)(2k + 1) = $4k^2 + 2k + 2k + 1$ = $2(2k^2 + 2k) + 1$ which is odd, so ~p $\to$ ~q, so the main statemnt is proved. $\color{green}{\square}$

### Exercise 11:
![[Pasted image 20230729203146.png]]
If A = B, then A $\subseteq$ A = B $\land$ B = A $\subseteq$ A. If A $\neq$ B, then we got 3 cases, A and B are disjoint sets, A $\subset$ B or B $\subset$ A. If they are disjoint sets, then A $\nsubseteq$ B and B $\nsubseteq$ A which makes the statemnt A $\nsubseteq$ B OR B $\nsubseteq$ A always true as well. If the A $\subset$ B, then A $\subseteq$ B and B $\nsubseteq$ A, which makes the statement A $\nsubseteq$ B OR B $\nsubseteq$ A always true. And, if B $\subset$ A, then B $\subseteq$ A and A $\nsubseteq$ B, which makes the statement A $\nsubseteq$ B OR B $\nsubseteq$ A always true, too. This mean that the contrapositive of the second part of the proof, which is A $\subseteq$ B and B $\subseteq$ A $\to$ A = B, is true, so the second part of the proof is also true, so we proved the main statement. $\color{green}{\square}$

### Exercise 12:
![[Pasted image 20230729205451.png]]
If A and B are two sets, then $\overline{\text{A}}$ = U - A and $\overline{\text{B}}$ = U - B.
If A $\subseteq$ B, then A = B - S, where S = B - A.
$\overline{\text{A}}$ = $\overline{\text{B - S}}$ = U - (B - S) = (U - B) $\cup$ S = $\overline{\text{B}}$ $\cup$ S
$\overline{\text{B}}$ = U - B
$\overline{\text{B}}$ $\subseteq$ $\overline{\text{B}}$ $\cup$ S <=> $\overline{\text{B}}$ $\subseteq$ $\overline{\text{A}}$ (1)
If $\overline{\text{B}}$ $\subseteq$ $\overline{\text{A}}$, then $\overline{\text{B}}$ = $\overline{\text{A}}$ - S', where S' = $\overline{\text{A}}$ - $\overline{\text{B}}$.
B = $\overline{\overline{\text{B}}}$ = $\overline{\overline{\text{A}} - S'}$ = $\overline{(U - A) - S'}$ = $\overline{U - (A \cup S')}$ = $A \cup S'$ $\supseteq$ A (2)
From (1) and (2) we have proven the main statement. $\color{green}{\square}$

### Exercise 13:
![[Pasted image 20230729221429.png]]
(a):
Let A and B be two sets.
B $\subseteq$ B $\cup$ A = A $\cup$ B
If A $\subseteq$ B, then A $\cup$ B $\subseteq$ B $\cup$ B <=> A $\cup$ B $\subseteq$ B.
And because B $\subseteq$ A $\cup$ B $\subseteq$ B, it means that B = A $\cup$ B. (1)
Let A and B be two sets.
If A $\cup$ B = B, then A $\subseteq$ A $\cup$ B = B. (2) $\color{green}{\square}$
(b):
Let A and B be two sets.
A $\cap$ B $\subseteq$ A
If A $\subseteq$ B, then A $\cap$ A $\subseteq$ B $\cap$ A <=> A $\subseteq$ A $\cap$ B.
And because A $\subseteq$ A $\cap$ B $\subseteq$ A, it means that A = A $\cap$ B. (1)
Let A and B be two sets.
If A $\cap$ B = A, then A = A $\cap$ B $\subseteq$ B. (2) $\color{green}{\square}$

### Exercise 14:
![[Pasted image 20230729224303.png]]
For n = -1, $n^2 + 41n + 41 = 1 -41 +41 = 1$ which is not prime, so $\exists$ n for which $n^2 + 41n + 41$ is not prime, which means that the statement $\forall$ n, $n^2 + 41n + 41$ is prime, is false. $\color{green}{\square}$

### Exercise 15:
![[Pasted image 20230729224910.png]]
Let $n_1, n_2, n_3, n_4, and \space n_5$ be 5 consecutive integers =>
$n_2$ = $n_1 + 1$
$n_3 = n_2 + 1 = n_1 + 1 + 1 = n_1 + 2$
$n_4 = n_3 + 1 = n_1 + 1 + 1 + 1 = n_1 + 3$
$n_5 = n_4 + 1 = n_1 + 1 + 1 + 1 + 1 = n_1 + 4$
so, $n_1 + n_2 + n_3 + n_4 + n_5 = n_1 + n_1 + 1 + n_1 + 2 + n_1 + 3 + n_1 + 4$ = $5n_1 + 10$ = $5(n_1 + 2)$ which is divisible by 5. $\color{green}{\square}$

### Exercise 16:
![[Pasted image 20230729225715.png]]
1:For n = 1, $n^3 - n = 1 - 1 = 0$ which 3 divides.
2:Assume true for n = k:
$k^3 - k = 3j$, where j is any positive integer.
3: Prove true for n = k + 1:
$(k  + 1)^3 - (k + 1) = (k^3 + k^2 + k^2 + k + k^2 + k + k + 1) - k - 1$ = $(k^3 + 3k^2 + 3k + 1) - k + 1$ = $k^3 + 3k^2 + 2k$ = $k^3 - k + 3k^2 + 3k$ =
$3j + 3k^2 + 3k$ = $3(j + k^2 + k)$ which is devisible by 3. $\color{green}{\square}$

### Exercise 17:
![[Pasted image 20230729231833.png]]
For x = -1, $x^3 = -1 \lt x^2 = 1$, so there are x, such that, $x^3 \gt x^2$ is false, then $\forall \space x \space x^3 \gt x^2$ is false. $\color{green}{\square}$

### Exercise 18:
![[Pasted image 20230729232359.png]]
Let p and q be two prime numbers.
We know that all prime numbers are odd numbers, so p and q can be written:
p = $2k_1 + 1$
q = $2k_2 + 1$
$k_1 \space and \space k_2$ are integers.
So p + q = $2k_1 + 1 + 2k_2 + 1 = 2k_1 + 2k_2 + 2 = 2(k_1 + k_2 + 1)$ which is devisible by 2, so it is not a prime number. $\color{green}{\square}$

### Exercise 19:
Exercise: Prove that if two lines are each perpendicular to a third line in the plane, then the two lines are parallel.
Solution: If $\alpha$ is a plane and a, b, and c are three lines in $\alpha$, with the property that a is perpendicular on c, and b is perpendicular on c. This mean that a and b are both perpendicular on c, and still beeing in the same plane. In other words, c is perpendicular on both a and b, which are all in $\alpha$. Because c is perpendicular to a, this mean that the angle between a and c is 90. Because c is perpendicular to b, this mean that the angle between b and c is 90. If a and b will not be parallel, then the angle between a and b will not equal 0, and because c is makes an angle of 90 with a, then the angle made with b will be 90 - the angle between a and b, which is not 0 so c will no longer be perpendicular to b. Thus, we have a contradiction, so a and b must form a 0 degree angle (they must be parallel). $\color{green}{\square}$

### Exercise 20:
Exercise: Prove that if x is a rational number and y is an irrational number, then x + y is an irrational number.
Solution: Let q: x is rational, p: y is irrational, and r: x+y is irrational. We have to prove (q $\land$ p) $\to$ r, which is equivalent with ~r $\to$ (~q $\lor$ ~p). If x + y is rational, it means that the number is also rational bacuse of the [[1.6 Mathematical structures#Closure property of mathematical structures]] of the sum operation in rational numbers. $\color{green}{\square}$
