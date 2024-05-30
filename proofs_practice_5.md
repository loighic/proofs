## proofs, practice problems, set 5

---

These are optional, and you can work on them with others.

Except for the problems in part 4, the settings are different than they have been on the assignments that you've done so far. These are settings that will be used on the test. 

These problems will not count toward your grade, but, so that you can see if you did them correctly or not, each is worth 1 point.

---

__Part 1.__ There is no feedback on these proofs, either at the end of each line or when the proof is complete. They can be submitted at any time (whether they are complete or incomplete, correct or incorrect), and they can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" feedback="none" guides="fitch" points="1" late-credit="1"}
0.1 (P&Q) & (S&T) :|-: Q&S
0.2 R -> (P&Q), R :|-: Q v S
0.3 PvQ, ~P, T :|-: Q&T
~~~

---

__Part 2.__ There is no feedback on these proofs, either at the end of each line or when the proof is complete. They can only be submitted when they are complete and correct, however.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" feedback="none" guides="fitch" points="1" late-credit="1"}
0.4 P->(QvS),P&~S :|-: Qv~T
0.5 (QvS)&~P,~Q :|-: TvS
0.6 S&T,T->F :|-: F&S
~~~

---

__Part 3.__ There is feedback for these proofs---at the end of each line and there is the green bar if you finish the proof correctly. These can be submitted at any point, whether or not they are correct or complete.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" points="1" late-credit="1"}
0.7 ~Sv(Q&T) :|-: S->T
0.8 Qv(R&T) :|-: ~Q->T
~~~

---

__Part 4.__ The settings in this part are the same as they have been on the assignments, except that they can't be submitted.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.9 Q -> P :|-: P v ~Q
0.10 ~(P v Q) :|-: ~P & ~Q
0.11 ~(~C v ~(D <-> F)) :|-: C & (D <-> F)
0.12 :|-: ~(Q & ~Q)
0.13 :|-: ~(~P & P)
0.14 :|-: D -> (G -> D)
0.15 :|-: (R -> T) -> ((T -> R) -> (R <-> T))
~~~

&copy; 2021 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson 
 
---