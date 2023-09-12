## Page:
[[Discrete mathematical structures.pdf#page=63]]

## Solution:
![[Pasted image 20230725180039.png]]

### Exercise 1:
A $\cup$ B:
```
function Union(A array, B array) -> array:
	1. let AuB an array
	2. put all elements of A inside AuB
	3. for every element elementB of B:
		a. let isCommon an bool = false
		b. for every element elementA of A:
			1. if elementB = elementA:
				a. isCommon = true
				b. break for loop
		c. if isCommon = true:
			1. continue
		d. add elementB in AuB
	4. return AuB
```

### Exercise 2:
A $\cap$ B:
```
function Intersection(A array, B array) -> array:
	1. let AnB an array
	2. for every element elementA of A:
		a. let isCommon an bool = false
		b. for every element elementB of B:
			1. if elementA = elementB:
				a. isCommon = true
				b. break for loop
		c. if isCommon = true:
			1. add elementA in AnB
	3. return AnB
```

### Exercise 3:
A - B:
```
function Difference(A array, B array) -> array:
	1. let A_B an array
	2. for every element elementA of A:
		a. let isCommon an bool = false
		b. for every element elementB of B:
			1. if elementA = elementB:
				a. isCommon = true
				b. break for loop
		c. if isCommon = true:
			1. continue
		d. add elementA in A_B
	1. return A_B
```

### Exercise 4:
![[Pasted image 20230725195522.png]]

```
function g(n integer) -> integer:
	1. if (n < 1):
		a. error undefined 
	2. if (n = 1):
		a. return 1
	3. if (n = 2):
		a. return -1
	4. return (-2) * g(n - 2) + 3 * g(n - 1)
```

(b)
```
function printFirstNtermsOfG(n integer) -> void:
	1. for i in range 1, n:
		a. print(g(n))
	2. return
```

(a)
```
function printFirst20TermsOfG() -> void:
	1. printFirstNtermsOfG(20)
	2. return
```

### Exercise 5:
![[Pasted image 20230725200547.png]]

```
function GCD(a, b) -> integer:
	1. if (a = b):
		a. return a
	2. if (a > b):
		a. return GCD(a - b, b)
	3. return GCD(a, b - a)
```

```
function LCM(a, b) -> integer:
	1. return (a * b) / GCD(a, b)
```