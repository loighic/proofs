## proofs, practice problems, set 1

These are optional, and you can work on them with others. They can't be submitted, but you can see whether or not you have done them correctly.

Problems 0.1 - 0.8 and 0.13 - 0.15 use the rules that are in sections 14.2 and 14.3. Problems 0.9 - 0.12 use those rules plus the conditional elimination rule (section 14.4).

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.1 P :|-: (P v Q) v ~R
0.2 (P & Q) & ~R :|-: Q
0.3 (S & T) & W :|-: S
0.4 (Q & P) & (R v ~P) :|-: P
0.5 (P & R) v S, ~S  :|-: R
0.6 ~R, R v (P -> T) :|-: P -> T
0.7 (A & ~C) & D :|-: ~C v B
0.7 (P & Q) & (R & T) :|-: Q & R
0.8 A v C, ~A, B :|-: C & B
0.9 B -> C, A & B :|-: C
0.10 C -> (B & A), C :|-: A
0.11 (A & C) -> B, C, A  :|-: B
0.12 A v ~B, ~B -> C, ~A :|-: C
0.13 P v Q, ~P v R, ~Q :|-: ~Q & R
0.14 ~R v ~S, S & T :|-: ~R & T
0.15 ~(B v C) v D, B :|-: D
~~~

&copy; 2021 Gregory Johnson 

---