Tags: #lecture #CISC102
Topics: [[Discrete Math]]

# Congruence Relations
$$ [x]_m = {a \in \mathbb{Z} : a \equiv {x \mod m}}$$
Congruence (mod m) partitions integers into x number of classes that are divisible by m denoted as above

Recall in [[Relations]] equivalence relations is reflexive, symmetric and transitive.

**Reflexive**
$a\equiv a\mod {m}$ ,for all integer a since $m | (a-a)$

**Symmetric**
if $a \equiv b \mod m$ then $b \equiv a \mod m$ because if $m | (a-b)$ then $m|-(a-b)$ 
or $m|(b-a)$

**Transitive**

## Arithmetic with congruence
Suppose $a \equiv b \mod m$ and $c \equiv d \mod m$
	Then
	$$a + c \equiv (b+d) \mod m$$
	$$a - c \equiv (b-d) \mod m$$
$$ac \equiv (bd) \mod m$$

Example:
$5 = 2(\mod 3)$ and $10 \equiv 1(\mod3)$ 
$$\frac{5-2}{3} = \frac{3}{3}(\text{integer})$$ 
$5 + 10 = (2+1)(\mod 3)$, that is $15 = 3(\mod3)$ 
$$\frac{15-3}{3} = \frac{12}{3} = 4(\text{integer})$$
$5 - 10 = (2-1)(\mod 3)$, that is $-5 = 1(\mod3)$ 
$$\frac{-5-1}{3} = -\frac{6}{3} = -2(\text{integer})$$
Note: By Division Theorem, $-5 = \colorbox{green}{-2}(3) + 1$
$5\times10 = (2\times1)(\mod 3)$, that is $50 = 2(\mod3)$ 
$$\frac{50-2}{3} = \frac{48}{3} = 16(\text{integer})$$

