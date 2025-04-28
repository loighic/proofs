## TFL proofs, practice problems, set 6

---

These are optional, and you can work on them with others.

These are easy to medium-difficulty problems. Feedback for each line and for the whole proof is only given when you press "Check." As preparation for the test, you should try doing each proof without the feedback for each line. Check the proof when you think that it is complete.

---

**Part 1**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam" feedback="manual" guides="fitch" submission="none"}
0.1 P, (P v S) -> T :|-: T 
0.2 R -> (P&Q), R :|-: Q v S
0.3 PvQ, ~P, T :|-: Q&T
0.4 N v ~R, ~R-> M, ~N :|-: M
0.5 (M v S), (Q -> ~M), Q :|-: Q & S
0.6 S, P, R :|-: (P v Q) & (S & R)
0.7 (P v Q) <-> R, P :|-: R
0.8 (N & P) -> M, N, P :|-: M

0.9 M <-> (N & S), (S v T), N, ~T :|-: M
0.10 P v ~R, R & T :|-: P & T
0.11 M -> R, (M -> R) <-> M :|-: R 
0.12 A -> (B v C), A & ~C :|-: B v ~D
0.13 ~P v ~Q, M & P :|-: ~Q
0.14 (R & T) v ~P, P & S :|-: S & T
0.15 (M v N) -> P, N <-> (R v S), R :|-: P
0.16 (Q v P) v ~(R & T), R & ~P, T :|-: Q  
~~~

---

**Part 2**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam" feedback="manual" guides="fitch" submission="none"}
0.17 P v (R & S) :|-: ~P -> S
0.18 ~Q v (R & T) :|-: Q -> T
0.19 ~S & T, ~P -> S :|-: P
0.20 Q -> (S & T) :|-: Q -> T 
0.21 Q v R, M <-> R, ~M :|-: Q

0.22 ~(P & ~Q), P v Q :|-: Q
0.23 ~(M v P) :|-: ~M
0.24 ~R v S, S -> Q :|-: R -> Q 
0.25 ~(P v R) :|-: ~R 
~~~

---

<p>&copy; 2022 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---