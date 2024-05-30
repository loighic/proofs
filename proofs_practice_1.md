## proofs, practice problems, set 1

These are optional, and you can work on them with others. They can't be submitted, but you can see whether or not you have done them correctly.

Problems 0.1 - 0.6 are the same as the proofs that I did in the first set of videos (where I was writing) that are posted in Canvas. 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.1 (P & R) & T :|-: R
0.2 S :|-: R v (S v P)
0.3 (P & R) -> Q, (P & T) & R :|-: Q
0.4 ((P & Q) & ~R) & T :|-: P & T
0.5 (G v D) & (F & ~G) :|-:  D & F
0.6 S & T, Q v R, ~R :|-: Q & T
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.7 (P & R) v S, ~S  :|-: R
0.8 ~R, R v (P -> T) :|-: P -> T
0.9 (P & Q) & (R & T) :|-: Q & R
0.10 L v M, ~L, R :|-: L & R
~~~

In some of these proofs, you have to use the double negation rule (right before you use the disjunction elimination rule) and the conditional elimination rule.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.11 (Q & P) & (R v ~P) :|-: R
0.12 Q -> W, P & Q :|-: W
0.13 W -> (Q & P), W :|-: P
0.14 (P & W) -> Q, W, P  :|-: Q
0.15 P v ~Q, ~Q -> W, ~P :|-: W
0.16 P v Q, ~P v R, ~Q :|-: ~Q & R
0.17 ~R v ~S, S & T :|-: ~R & T
0.18 ~(Q v W) v Y, Q :|-: Y
~~~

&copy; 2021 Gregory Johnson 

---