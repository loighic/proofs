---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## proofs, assignment 15 (meeting)

---

**warm-up problems**

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" feedback="none" points="1" late-credit="1"}
15.1 ~P v ~Q, Q :|-: ~P
15.2 ~P v Q, ~Q :|-: ~P
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="33" late-credit="25"}
15.3 (N & ~Q) v R :|-: Q -> R
15.4 F -> (G -> H), ~J -> (F v H), F -> G :|-: ~J -> H
~~~

Start your proof for &not;(T &or; &not;W) &vdash; (&not;T & W) by assuming the opposite of the conclusion. Then, your options for a second assumption are `T`, `&not;T`, `W`, or `&not;W`. In the second sub-proof, you will get a contradiction with either the TFL sentence on line 1 or the one on line 2. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="33" late-credit="25"}
15.5 ~(T v ~W) :|-: ~T & W
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---