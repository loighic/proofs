---
title: proofs, assignment 12
--- 

# proofs, assignment 12 (meeting)

---

## warm-up, extra credit problems

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam" guides="fitch" feedback="none" points="1" late-credit="1"}
1 ~P v Q, ~Q :|-: ~P
2 ~P v ~Q, Q :|-: ~P
~~~

---

## main problems

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="25" late-credit="17"}
3 R -> S, R -> ~S :|-: ~R
4 ~P & S :|-: P -> Q
5 ~(P & Q) :|-: P -> ~Q
6 P <-> (~Q & S), P & (~T -> ~S) :|-: ~Q & T 
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---