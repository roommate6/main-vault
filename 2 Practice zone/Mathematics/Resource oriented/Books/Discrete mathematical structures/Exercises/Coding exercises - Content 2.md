---
Page: "[[Discrete mathematical structures.pdf#page=89]]"
---
1. Write a program that will print a truth table for p Ʌ (~q).
2. Write a program that will print a truth table for (p V q) → r.
3. Write a program that will print a truth table for two-variable propositional function.
4. Write a subroutine EQUIVALENT that determines if two logical expressions are equivalent.
5. Write a subroutine that determines if a logical expression is a tautology, a contingency, or an absurdity.

### 1:
```
ALGORITHM CREATE_TABLE
	1. PRINT('p | q | (~q) | p Ʌ (~q)')
	2. PRINT_NEW_LINE()
	3. FOR p = 0 THRU 1
		a. FOR q = 0 THRU 1
			1. PRINT(p)
			2. PRINT(' | ')
			3. PRINT(q)
			4. PRINT(' | ')
			5. IF (q = 0)
				a. q = 1
			6. ELSE
				a. q = 0
			7. PRINT(q)
			8. PRINT(' | ')
			9. IF (p = 0 OR q = 0)
				a. PRINT('0')
			10. ELSE
				a. PRINT('1')
			11. PRINT_NEW_LINE()
END OF ALGORITHM CREATE_TABLE
```

### 2:
```
ALGORITHM CREATE_TABLE
	1. PRINT('p | q | r | p V q | (p V q) → r')
	2. PRINT_NEW_LINE()
	3. FOR p = 0 THRU 1
		a. FOR q = 0 THRU 1
			1. FOR r = 0 THRU 1
				a. PRINT_FORMATED('(p) | (q) | (r) | ')
				b. IF (p = 1 OR q = 1)
					1. orValue ← 1
				c. ELSE
					1. orValue ← 0
				d. PRINT_FORMATED('(orValue) | ')
				e. IF (orValue = 0)
					1. PRINT('1')
				f. ELSE
					1. PRINT_FORMATED('(r)')
				g. PRINT_NEW_LINE()
END OF ALGORITHM CREATE_TABLE
```

### 3:
```
ALGORITHM CREATE_TABLE(f)
	1. PRINT('p | q | f(p,q)')
	2. PRINT_NEW_LINE()
	3. FOR p = 0 THRU 1
		a. FOR q = 0 THRU 1
			1. PRINT_FORMATED('(p) | (q) | (f(p,q))')
			2. PRINT_NEW_LINE()
END OF ALGORITHM CREATE_TABLE
```

### 4:
```
SUBROUTINE EQUIVALENT(p, q; r)
	1. r = true
	2. IF (p ≠ q)
		a. r = false
	3. RETURN
END OF SUBROUTINE EQUIVALENT
```

### 5:
```
SUBROUTINE TAUTOLOGY_CONTINGENCY_ABSURDITY(expression)
	1. allTrue = true
	2. allFalse = true
	3. FOR x IN DOMAIN_OF(expression)
		1. IF (expression(x) = true)
			a. allFalse = false
		2. ELSE
			a. allTrue = false
		3. IF (allFalse = false AND allTrue = false)
			1. PRINT('contingency')
			2. GO TO 6.
	4. IF (allTrue = true)
		a. PRINT('tautology')
	5. ELSE
		a. PRINT('absurdity')
	6. RETURN
END OF SUBROUTINE TAUTOLOGY_CONTINGENCY_ABSURDITY
```