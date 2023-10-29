1.

``` python

def permutation(n,r):
	result = 1
	if (r <= n):
		for i in range(r):
			result = result * (n-i)
	return result

```

2.

``` python

def permutations(n,r):
	for i in range(r,n+1):
		result = 1
		for j in range(r):
			result = result * (i - j)
		print(result)

```

3.

``` python

def factorial(n):
	result = 1
	for i in range(2,n+1):
		result = result * i
	return result

def combination(n,r):
	result = 1
	max = max(n-r,r)
	for i in range(n,max,-1):
		result = result * i
	if max == (n-r):
		return result / factorial(r)
	return result / factorial(n-r)
	
```

4.

``` python

def combinations(n,r):
	for i in range(r,n+1):
		print(combination(i,r))

```

5.

``` python

fibonacci_cache = {}

def recursive_fibonacci(n):
	if n in fibonacci_cache:
		return fibonacci_cache[n]
	
	if n == 1:
		value = 0
	if n == 2:
		value = 1
	if n > 2:
		value = recursive_fibonacci(n-2) + recursive_fibonacci(n-1)
	
	fibonacci_cache[n] = value
	print(value)
	return value
	
```

6.

``` python

def nonrecursive_fibonacci(n):
	if n == 1:
		print(0)
		return
	if n == 2:
		print(1)
		return
	f_1 = 0
	f_2 = 1
	for i in range(3,n+1):
		value = f_1 + f_2
		f_1 = f_2
		f_2 = value
	print (value)

```