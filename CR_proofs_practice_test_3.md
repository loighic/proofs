## proofs, practice problems for test 3

---

**This is not the pre-test. These are practice problems.**

These are optional, and you can work on them with others.

There is no feedback at the end of each line. They cannot, however, be submitted until they are correct. There won't be any problems set up like these on the test, but it will be helpful to do these as practice. 

These do not count toward your grade.

---

__Part 1A__

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
0.1 P, (P v S) -> T :|-: T 
0.2 R -> (P&Q), R :|-: Q v S
0.3 P v Q, ~P, T :|-: Q & T
0.4 N v ~R, ~R-> M, ~N :|-: M
0.5 (M v S), (Q -> ~M), Q :|-: Q & S
0.6 S, P, R :|-: (P v Q) & (S & R)
0.7 (P v Q) <-> R, P :|-: R
0.8 (N & P) -> M, N, P :|-: M
~~~

__Part 1B__

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
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

__Part 2A__

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
0.17 P v (R & S) :|-: ~P -> S
0.18 ~Q v (R & T) :|-: Q -> T
0.19 Q -> (S & T) :|-: Q -> T
0.20 P -> ~M, M v T :|-: (P & S) -> T
~~~


__Part 2B__

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
0.21 ~R v S, S -> Q :|-: R -> Q
0.22 T -> (P -> Q) :|-: (T & P) -> Q 
0.23 S & ~T, Q -> (S -> N) :|-: (Q v T) -> N 
0.24 T -> P, ~P v S :|-: (Q & T) -> (Q & S)
~~~

---

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---