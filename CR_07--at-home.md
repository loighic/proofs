## proofs, assignment 08 (at-home)

---

Problems 8.4 - 8.8 are each worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 15 points.

<font color="#9900FF">**Do this alone.** Contact the instructor if you need help.</font>

---

**warm-up, extra credit problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render resize" guides="fitch" points="1" late-credit="1"}
8.1 R <-> (S & T), S & T :|-: R 
8.2 P v Q, ~Q :|-: P 
8.3 M, N v ~M :|-: N
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render resize" guides="fitch" points="20" late-credit="16"}
8.4 L <-> (M v R), M :|-: L

8.5 ~P v ~R, ~R <-> S, P :|-: S & ~R
8.5 ~H -> F, ~N v ~H, N :|-: N & F

8.6 (P v R) -> Q, R, S :|-: S & Q
8.6 P & Q, (R v Q) -> T :|-: T & Q
8.6 T & Q, (~R v Q) -> S :|-: S & T 

8.7 S <-> (T v (R -> Q)), (S & ~T) & R :|-: Q
~~~

You need to use the conditional introduction rule in the proof for 8.8. See section 12.7.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render resize" guides="fitch" points="20" late-credit="16"}
8.8 P v Q :|-: ~Q -> P
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
