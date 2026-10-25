---
title: test 3 practice problems
---

# proofs, practice problems for test 3

---

## Instructions

**This is not the pre-test. These are practice problems.**

These are optional, and you can work on them with others.

There is no feedback at the end of each line. They cannot, however, be submitted until they are correct. There won't be any problems set up like these on the test, but it will be helpful to do these as practice. 

These do not count toward your grade.

---

## Part 1A

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
1 P, (P v S) -> T :|-: T 
2 R -> (P&Q), R :|-: Q v S
3 P v Q, ~P, T :|-: Q & T
4 N v ~R, ~R-> M, ~N :|-: M
5 (M v S), (Q -> ~M), Q :|-: Q & S
6 S, P, R :|-: (P v Q) & (S & R)
7 (P v Q) <-> R, P :|-: R
8 (N & P) -> M, N, P :|-: M
~~~

## Part 1B

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
9 M <-> (N & S), (S v T), N, ~T :|-: M
10 P v ~R, R & T :|-: P & T
11 M -> R, (M -> R) <-> M :|-: R 
12 A -> (B v C), A & ~C :|-: B v ~D
13 ~P v ~Q, M & P :|-: ~Q
14 (R & T) v ~P, P & S :|-: S & T
15 (M v N) -> P, N <-> (R v S), R :|-: P
16 (Q v P) v ~(R & T), R & ~P, T :|-: Q  
~~~

---

## Part 2A

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
17 P v (R & S) :|-: ~P -> S
18 ~Q v (R & T) :|-: Q -> T
19 Q -> (S & T) :|-: Q -> T
20 P -> ~M, M v T :|-: (P & S) -> T
~~~


## Part 2B

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
21 ~R v S, S -> Q :|-: R -> Q
22 T -> (P -> Q) :|-: (T & P) -> Q 
23 S & ~T, Q -> (S -> N) :|-: (Q v T) -> N 
24 T -> P, ~P v S :|-: (Q & T) -> (Q & S)
~~~

---

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---