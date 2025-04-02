## test 3, revision process, 3

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="14" late-credit="14"}
3.1 P -> Q, R <-> P, P :|-: Q & R
3.2 (T & Q) & R,  (T & R) -> S :|-: S
3.3 P & Q, (~R v Q) -> S :|-: S & P 
3.4 (P v Q) -> (S v T), Q & ~S :|-: T
3.5 ~P v ~R, ~R <-> S, P :|-: S & ~R
3.6 S <-> (P & Q), (T -> P) & (Q & T) :|-: S
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="16" late-credit="16"}
3.7 ~(P v T) v (M & Q), T & S :|-: M
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---

