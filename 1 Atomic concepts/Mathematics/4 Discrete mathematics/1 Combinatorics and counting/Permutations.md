# Definition

A **permutation** is a sequence of **r** distinct objects taken from a [[Set]] that has a cardinality of $n,\space \text{where:}\space n,\space r \in \mathbb{N}, \space 1 \le r \le n$.

The number of permutations of n objects taken r at a time is denoted:

$$P_n^r$$

and equals:

$$P_n^r = \frac{n!}{(n - r)!}$$ ^a9e27b

# Deduction

A permutation is a sequence of a finite length, made with distinct objects from a finite [[Set]], where the sequence has a length **r** less or equal to the cardinality of the objects set, **n**.

In order to understand the formula, let's start by constructing a permutation of length n, made with objects from a set that has a cardinality r, with r <= n.

1. We will start by creating n places that will be occupied by the objects.
The places will have a property: position in sequence. The position can be imagined as a number, or any other ordonable quality that can be used to describe the order of the places in the sequence. We will start from the first place, then the second, and so on, until we reach the last place.

The places visualized:

![[Permutations_25-10-2023_20.56.41.excalidraw]]

2. The next step is to create a set of objects that will fill those gaps.

The set of objects can be visualized as:

![[Permutations_25-10-2023_21.00.40.excalidraw]]

3. In this step, we will start to put distinct objects inside the places, starting from the first place, and continuing until the last one.

Let's choose the object $o_n$ to occupy the first place. (This is an arbitrary choice)

![[Permutations_25-10-2023_21.05.08.excalidraw]]

Now, let's fill every place with distinct objects.

![[Permutations_25-10-2023_21.08.14.excalidraw]]

In how many ways we can construct such a sequence?

An easy solution for the question is to divide the question in smaller steps.

Let's name the task of filling the first position with an distinct object, T1.
In how many ways can we do T1?
In n ways, because we have n objects that can be chosen to occupy the first place.

Let's name the task of filling the second position with an distinct object, T2.
In how many ways can we do T2, knowing that T1 was already made?
In n-1 ways, because we are left with n-1 objects that haven't been yet used in our sequence. This is happening because the previous tasks (which is T1), have already used some objects from the set, and because of that, we are limiting our choosing options.

The next task, T3, is the task of filling the third position with an distinct object, knowing that tasks T1 and T2 already occurred.
The same strategy goes here, we can perform this task in n-2 ways, because, tasks 1 and 2, already chose two objects that we can't pick again for this position, so we are left with n-2 options.

After continuing this process, we will finally find the total of ways we can fill the last place with an distinct object, this will be the task r.
The task r will can be accomplished in n-(r-1) ways.

In how many ways can we create a sequence of r elements that belong to a set that has n elements, with r <= n?

The question is equivalent to this question:

In how many ways can we perform the tasks: T1, T2, T3, ..., Tr in sequence?

![[Multiplication principle of counting#^3a55a6]]

Based on the
![[Multiplication principle of counting#^1535b0]]
we can perform this sequence of tasks in:

$$n \cdot (n-1) \cdot (n-2) \cdot {...} \cdot (n-(r-1)) \text{ ways}$$

which is equal to:

$$\frac{n!}{(n-r)!}$$
