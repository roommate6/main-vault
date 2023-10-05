---
Date: 05.10.2023
---
# 2 parti

7 cursuri + 7 lab - programre logica
7 cursuri + 7 lab - programare functionala

Prezenta obligatorie la laborator.
Prezenta la curs facultativa.

# Evaluare

2 partiale - Programare logica + Programare functionala

# Notare

70% medie nota partiale + 30% medie teme

# Partial

2 probleme, una de nota 5 si una de nota 10. Timp de lucru: 30-45 minute.

# Examen

cele 2 partiale, daca le luam, nu mai venim

# Programare logica si functionala

## Programare imperativa - How

- prodecurala C
- oop C++, JAVA, C#, Python, etc

## Programare declarativa - What

- logica - Prolog
- functionala - Lisp, Heskell, Scala, Clojure, etc

## Exemple

```
my_list = [1,2,3,4,5]
sum = 0
for x in my_list:
	sum += x
print(x)

---

import functools
	my_list
	sum = functools.reduce(lambda x,y: x+y, my_list)
```

## Programare logica

Pleaca de la un knowladge base.

Functiile se vor numi predicate, adevarate sau false.

Se bazeaza pe lucru cu predicate( afirmatii care au valoare de adevar in anumite conditii );

O propozitie de o afirmatie care poate fi adevarata sau falsa.
Predicatele sunt adevarate in anumite conditii, determinate de niste variabile.

Se bazeaza pe interogari.

Pe baza de cunostinte, ceri ce vrei.

### Cod

parinte(ion, vasile). - fapt (True/False)

parinte(x, y) :-
	mama(x, y).

parinte(x, y) :-
	tata(x, y).

### Prolog

#### Sudoku

9x9 ,
![[course_1_05-10-2023_09.22.35.excalidraw]]

Planificari

#### Logica matematica

#### AI

#### Aplicatii practice prolog

- folosit la NLP (natural language porcessing)
- IBM watson
- analiza (parsare) sau generarea unor propozitii in baza unor sintaxe definite
- management baze de date nonsql *knowladge base*
- analiza predictiva
- recunoastere sabloane
- decision support system
- orare scolare

#### Puzzle logic

problema de deductie

#### Matematica din spate:

Propozitie (True/False)

