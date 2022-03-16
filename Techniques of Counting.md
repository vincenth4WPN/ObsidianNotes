Tags: #lecture #CISC102 
Topics:[[Discrete Math]]

## Techniques of Counting (Chapter 5 of DM)
### Product Rule Principle
Let $A\times{B}$ be the cross product of sets A and B
Then $|A\times{B}| = |A|\times{|B|}$

Event E occurs in m ways and event F occurs in n ways, two independent events.
Combination of event E and F occur in $m\times{n}$ ways.

### Sum Rule Principle
Event E occurs in m ways and event F occurs in n ways, two events do NOT occur at once, then E OR F occurs in $m + n$ ways.

### Pigeon Hole Principle
With n+1 amount of pigeons and n pigeon holes, at least one pigeon hole needs 2 pigeons.
	- This can be used as a counting tool

If there are $kn+1$ pigeons, that all must sleep in a pigeon hole, and $n$ pigeon holes, then there is at least one pigeon hole where (at least) $k+1$ pigeons sleep

6,000,000 > 500,000, therefore there must be at least multiple things that satisfy lower condition

### Permutations
- Counting where ORDER MATTERS

P(n) = n!

#### Permutation of a Subset
- Ways to select 2 balls from 5 balls
	- 6!/4! = 6x5
- Notation:
$$P(n,k) = \frac {n!}{n-k} $$
- Example:
$$\frac{6!}{4!} = \frac{6\times5\times\cancel{4\times3\times2\times1}}{\cancel{4\times3\times2\times1}} $$

#### Permutations with Repetition
- Notation:
$$P(n) = \frac {n!}{n_1!n_2!n_3!}$$
Look for elements that are the "same" and group them together
Example: Order the letters MISSISSIPPI
$$\frac{11!}{1!M\times4!I\times4!S\times2!P}$$
### Combinations
Counting where order does not matter

$$\frac {n!}{k!(n-k)!}$$

### Counting paradigms
Selection with ordering and replacement
- Select k from n with replacement
$$n^k$$

- Select k from n without replacement
$$\frac{n!}{(n-k)}!$$
- Select k from n without ordering and without replacement
$$\frac{n!}{k!(n-k)!} = \binom{n}{k}$$
- Select k from n without order and with replacement [[#Permutations with Repetition]]
$$P(n) = \frac {n!}{n_1!n_2!n_3!}$$
