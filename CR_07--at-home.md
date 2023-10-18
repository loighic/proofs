## proofs, assignment 07 (at-home)

Problems 6.4 - 6.8 are each worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

---

**warm-up, extra credit problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
6.1 R <-> (S & T), S & T :|-: R 
6.2 P v Q, ~Q :|-: P 
6.3 M, N v ~M :|-: N
6.4 R, S :|-: S & R 
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
6.5 ((A & B) & ~C) & F :|-: (B v E) & ~C
6.5 P & (~Q & (R & T)) :|-: (R v S) & P

6.6 N & ~G, (J -> T) <-> K, (K v G) & J :|-: ~G & T
6.6 A & ~G, (D -> B) <-> M, (M v G) & D :|-: ~G & B

6.7 L <-> (M v R), M :|-:  L
6.8 ~P, (R v ~P) <-> (P v Q) :|-: Q
~~~

You have to use the conditional introduction rule in the proof for 6.9.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
6.9 S & T :|-: R -> T
~~~

&copy; 2022 Gregory Johnson 
 
