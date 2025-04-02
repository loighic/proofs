---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## proofs, assignment 13 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

---

**warm-up, extra credit problems**

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" feedback="none" points="1" late-credit="1"}
13.1 R <-> ~T, ~T :|-: R 
13.2 ~P v ~Q, Q :|-: ~P 
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
13.3 ~T -> ~R, R :|-: T
13.4 R <-> P, ~P :|-: ~R
13.5 R -> S, ~(S & T) :|-: ~(R & T)
13.6 M v N, M -> (N & R) :|-: N
~~~


For 13.7, think about which rules you need to use. Don't just automatically go to negation intro or negation elim.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
13.7 P <-> (~R -> T), R v T :|-: P 
~~~

<p>&copy; 2019 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---