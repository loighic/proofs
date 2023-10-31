## test 3, revision process, 1

---


~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="10"}
1.1 P <-> (Q & T), P :|-: (Q & T)
1.2 ~P <-> (Q & T), ~P :|-: T
1.3 P <-> Q, P & ~T :|-: Q
1.4 (P -> N) & ~R, P :|-: N
1.5 Q v T, ~S & ~Q :|-: T
1.6 (R & T), (T -> Q) :|-: (Q v P)
1.7 M <-> P, P & R :|-: M v N
1.8 P -> Q, (Q -> P) & R :|-: P <-> Q
1.9 ~N v P, ~N <-> S, ~P :|-: S
~~~

If you are having trouble with 1.10, consult section 13.3, especially the subsection titled "Double negation."

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="10"}
1.10 ((~P v Q) & R), P :|-: Q
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

:)

---

