---
title: proofs, assignment 13
--- 

# proofs, assignment 13 (at-home)

---

## Instructions

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

---

## warm-up, extra credit problems

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam" guides="fitch" feedback="none" points="1" late-credit="1"}
1 R <-> ~T, ~T :|-: R 
2 ~P v ~Q, Q :|-: ~P 
~~~

---

## main problems

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="20"}
3 R <-> P, ~P :|-: ~R
4 R -> S, ~(S & T) :|-: ~(R & T)
5 M v N, M -> (N & R) :|-: N
~~~


For 6, think about which rules you need to use. Don't just automatically go to negation intro or negation elim.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="20"}
6 P <-> (~R -> T), R v T :|-: P 
7 ~(M & ~T) :|-: M -> T
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---