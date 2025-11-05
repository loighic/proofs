---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## proofs, assignment 14 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

---

**warm-up, extra credit problems**

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" feedback="none" points="1" late-credit="1"}
14.1 R <-> ~T, ~T :|-: R 
14.2 ~P v ~Q, Q :|-: ~P 
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
14.3 R <-> P, ~P :|-: ~R
14.4 R -> S, ~(S & T) :|-: ~(R & T)
14.5 M v N, M -> (N & R) :|-: N
~~~


For 14.6, think about which rules you need to use. Don't just automatically go to negation intro or negation elim.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
14.6 P <-> (~R -> T), R v T :|-: P 
14.7 ~(M & ~T) :|-: M -> T
~~~


<p>&copy; 2019 - <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---