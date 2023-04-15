---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 10

Problems 10.5 - 10.9 are each worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

---

**warm-up, extra credit problems**

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" feedback="none" points="1" late-credit="1"}
10.1 R <-> ~T, ~T :|-: R 
10.2 ~P v Q, ~Q :|-: ~P 
10.3 ~N, ~N -> ~M :|-: ~M
10.4 R, S :|-: (S v T) & R 
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
10.5 B -> (~C -> D) :|-: (B & ~C) -> D
~~~

For 10.6, you need to use conditional introduction rule, but it won't be to get the conclusion (which isn't a conditional). Think about how you will get the conclusion, given that you have P before the double arrow in (P &LeftRightArrow; (&not;R &rarr; T)).

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
10.6 P <-> (~R -> T), R v T :|-: P 
~~~

For 10.7, think about what you need in order to get the conclusion. (Hint: it's a biconditional, and so you will need to use the biconditional introduction rule. Check how that rule works if you don't remember. You will also need to use the double negation rule in this proof.)

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
10.7 ~P v Q, Q -> P :|-: P <-> Q
~~~


You need to use the negation eliminaton rule in 10.8, and the negation introduction rule in 10.9. You will also need to use the reiteration rule in these two proofs.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
10.8 ~P -> ~Q, Q :|-: P
10.9 R <-> P, ~P :|-: ~R
~~~

&copy; 2022 Gregory Johnson 
 
---