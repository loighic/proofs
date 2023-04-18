## HW 13 (alternate)

Problems 13.5 - 13.9 are each worth 12 points, and the whole assignment is worth 100 points.

---

**warm-up, extra credit problems**

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" feedback="none" points="1" late-credit="1"}
13.1 R <-> (S & T), S & T :|-: R 
13.2 P v Q, ~Q :|-: P 
13.3 M, N v ~M :|-: N
13.4 R, S :|-: S & R 
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="12" late-credit="12"}
13.5 ((A & B) & ~C) & F :|-: (B v E) & ~C
13.5 P & (~Q & (R & T)) :|-: (R v S) & P

13.6 N & ~G, (J -> T) <-> K, (K v G) & J :|-: ~G & T
13.6 A & ~G, (D -> B) <-> M, (M v G) & D :|-: ~G & B

13.7 L <-> (M v R), M :|-:  L
13.8 ~P, (R v ~P) <-> (P v Q) :|-: Q
~~~

You have to use the conditional introduction rule in the proof for 13.9.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="12" late-credit="12"}
13.9 S & T :|-: R -> T
~~~

&copy; 2023 Gregory Johnson 
 
