---
title: proofs, assignment 15
--- 

# proofs, assignment 15 (meeting)

---

## warm-up problems

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam" guides="fitch" feedback="none" points="1" late-credit="1"}
1 ~P v ~Q, Q :|-: ~P
2 ~P, ~Q <-> ~P :|-: ~Q
~~~

---

## main problems

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="33" late-credit="25"}
3 M -> ~(S & T) :|-: (M & S) -> ~T
4 ~P -> Q :|-: P v Q
5 (~P -> [S -> R]), (Q -> [~P v R]), (~P -> S) :|-: (Q -> R)
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---