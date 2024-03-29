## proofs, practice problems, set 3

These are optional, and you can work on them with others. They can't be submitted, but you can see whether or not you have done them correctly.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.1 (~E & Q) <-> K, K  :|-: Q 
0.2 A <-> (D & ~C), ~C, D  :|-: A 
0.3 P, Q, (P & Q) -> T  :|-:  T
0.4 (S <-> ~H) & N, (N<->~H) & ~A :|-: S & ~A
~~~

For 0.5 - 0.10, you need to use the `->I` rule.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.5 P v Q :|-: ~Q -> P
~~~

To use `vE` in 0.6, 0.7, and 0.9, you also have to use the double negation rule (`DN`). For instance, if you have ~P v Q on a line, you need ~~P to get Q on a line by itself.  

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.6 ~P v Q :|-: P -> Q
0.7 ~C v (B & D) :|-: C -> D
0.8 P :|-: Q -> P
0.9 ~A v D, (A <-> B) & C :|-:  B -> D
0.10 P -> (Q -> R) :|-: (P & Q) -> R
~~~

&copy; 2021 Gregory Johnson 
 
---