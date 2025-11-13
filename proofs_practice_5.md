## proofs, practice problems, set 5

---

These are optional, and you can work on them with others.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.1 Q -> P :|-: P v ~Q
0.2 ~(P v Q) :|-: ~P & ~Q
0.3 ~(~C v ~(D <-> F)) :|-: C & (D <-> F)
0.4 P -> ~Q, (S & T) -> (P & Q) :|-: S -> ~T
0.5 ~P -> (R & Q), S, ~(S & P) :|-: Q
0.6 ([S & ~M] -> [M <-> ~R]), (S & [P -> Z]) :|-: (~M -> R)
0.7 ([S <-> Q] <-> ~W), (~W -> S), (R -> ~[T v Q]) :|-: (R -> W)
0.8 (P <-> Q) :|-: ([P & Q] v [~P & ~Q])
~~~

Theorems: See section 15.1.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.9 :|-: ~(B & ~B)
0.10 :|-: ~(~P & P)
0.11 :|-: D -> (G -> D)
0.12 :|-: (R -> T) -> ((T -> R) -> (R <-> T))
~~~

<p>&copy; 2021 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson.</p>
 
---