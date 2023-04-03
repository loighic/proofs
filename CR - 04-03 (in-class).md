## in-class assignment: 04/03

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="17" late-credit="14"}
6.1 S & T :|-: R -> T
6.2 ~P, (R v ~P) <-> (P v Q) :|-: Q
6.3 (M -> P) & R, S & M, N <-> (P & S) :|-: N
6.4 ~S v ~T :|-: S -> ~T
6.5 P v Q, (~P <-> R) & T :|-: R -> Q
~~~

For 6.6, you need to make an assumption. Like always, when you plan to use the conditional introduction rule, the assumption should be the antecedent of the conditional.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="17" late-credit="14"}
6.6 R -> Q, Q -> T :|-: (S & R) -> T
~~~

---

&copy; 2023 Gregory Johnson 
 
