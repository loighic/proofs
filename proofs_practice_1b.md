## proofs, practice problems, set 1b

---


~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.1 (P & Q), (Q -> S) :|-: S
0.2 S & T :|-: T & (S v P)
0.3 P <-> W, (S & W) & Q :|-: P
0.4 S v Q, P & ~S :|-: P & Q
0.5 (M v H) & (~M & ~P) :|-:  H & ~P
~~~

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
0.6 (Q & P) & (R v ~P) :|-: R
0.7 (P & W) -> Q, W, P  :|-: Q
0.8 ~Q -> W, T v ~Q, ~T :|-: W
0.9 P v Q, P -> R, ~Q :|-: ~Q & R
0.10 (T & W) & R, (T & R) -> (S & W) :|-: W
~~~

<p>&copy; 2021 - <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p> 

---