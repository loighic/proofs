## proofs, practice problems, set 4

---

These are optional, and you can work on them with others. They can't be submitted, but you can see whether or not you have done them correctly.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.1 ~C & ~D, (B v C) <-> (A v D) :|-: A -> B
~~~

You have to use `->I` in 0.2 and the assumption should be C.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.2 A <-> (C -> D), D & ~B :|-: A
~~~

You have to use `->I` in 0.3 and the assumption should be ~A

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.3 (~A -> B) -> C, (A v B) & D :|-: C
~~~

You have to use the negation rules in 0.4 - 0.8.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.4 P->~Q, Q :|-: ~P
0.5 PvQ, ~P->~Q :|-: P
0.6 B & C, ~(B & A) :|-: ~A
0.7 A->~B, A->B :|-: ~A
0.8 P -> ~Q :|-: ~(P & Q)
~~~

Problems 0.9 and 0.10 require two subproofs. In each, you have to use `->I` and either `~E` or `~I`. And for both, the second subproof will be within the first one.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.9 ~P :|-:  P -> Q
0.10 (B & ~Q) v G :|-: Q -> G
~~~

<p>&copy; 2021 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson.</p> 
 
---

