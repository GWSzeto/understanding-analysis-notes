# Understanding Analysis

## Section 1.2: Some Preliminaries

#### Theorem 1.1.1
There is not rational number whose square is 2

#### Definition of Rational Number
A number that can be expressed in the form of p/q, where p and q are integers

#### Natural Numbers Set
N = {1, 2, 3, ...}

#### Set
A set is a collection of objects, the objects being the elements of the set
Similar to a JS object, these objects can be a wide range of things like numbers to functions

#### De Morgan's Law
$(A \cap B)^c = A^c \cup B^c$ and $(A \cup B)^c = A^c \cap B^c

#### functions
a function is a mapping given a set A (domain) that associates each element of A to a single element from the set B (range)
We can write it as $f: A -> B$
${y \in B: y = f(x) for some x \in A}

#### Absolute Function
shown as |x|, it is a function that will convert any input number into the positive form, that is:
  if x < 0, then -x
  if x >= 0, then x
This can be shown as the magnitude of the number and

#### Triangle Inequality
(i) |ab| = |a||b|
(ii) |a + b| = |a| + |b|

#### Theorem 1.2.6
2 real numbers a and b are equal if for every e > 0, |a - b| < e

## Section 1.3: Axiom of Completeness

#### Axiom of Completeness
Every nonempty set of real numbers that is bounded above has a least upper bound

#### Definition 1.3.1
a set $A \subseteq R$, is bounded above if there exists a $b \in R$ such that b > a for all $a \in A$
Vice versa if it's bounded below

#### Definition 1.3.2
a real number is is the last upper bound for a set $A \subseteq R$ if:
  (i) s is an upper bound of A
  (ii) if b is any upper bound of A, then $b >= s$
This is called the supremum of A, also notated as $s = Sup A$
The vice versa would be called the infimum of A

#### Definition 1.3.3
the element $a_0$ is the maximum of A if $a_0 >= a$ for every $a \in A$ and $a_0 \in A$
similarly, the minimum of A is the vice versa

#### Lemma 1.3.8
Assume s is an upper bound for the set A
then $s = sup A$ if and only if for every choice e > 0 there exists an element $a \in A$ such that s - e < a

## Section 1.4: Consequences of Completeness

#### Theorem 1.4.1 (Nested Interval Property)
for each $n \in N$ assume we are given a closed interval $I_n = [a_n, b_n] = {x \in R: a_n <= x <= b_n}$
Assume also that each $I_n contains I_{n+1}$, so:

  $I_1 \supseteq I_2 \supseteq I_3 \supseteq ...$

Then the intersect of these closed intervals is not the empty set, $\cap_{n=1}^{\infty} I_n \neq \emptyset$

#### Theorem 1.4.2 (Archimedean Property)
(i) Given any number $x \in R$ there exists an $n \in N$ satisfying n > x
(ii) Given any real number y > 0 there exists an $n \in N$ satisfying $1/n < y$

#### Theorem 1.4.3 (Density of Q in R)
for every 2 real numbers, a and b such that a < b, there exists a rational number r satisfying a < r < b

#### Corollary 1.4.4
Given any 2 real numbers a and b such that a < b, then there exists an irrational number t satisfying a < t < b

#### Theorem 1.4.5
There exists a real number $a \in R$ satisfying $a^2 = 2$
