# Backtracking

```
%---
member(X, [X|_]).

<=>

member(X, [H|T]):-
	H =:= X.
%---

member(X, [_|Rest]):-
	member(X, Rest).

```

## Stopping the recursivity

using the "!" cut operator:

```
cut/0 or !/0
```

```

teaches(dr_fred, history).
teaches(dr_fred, english).
teaches(dr_fred, drama).
teaches(dr_fiona, physics).

studies(alice, english).
studies(angus, english).
studies(amelia, drama).
studies(alex, physics).

```

```

mai_mare(X,X,X). % :- !.
mai_mare(X,Y,Y):- X<Y. % X<Y, !.
mai_mare(X,Y,X):- X>Y. % .

```

```

mai_mare(X,Y,Y):- X <= Y, !.
mai_mare(X,_,X).

```