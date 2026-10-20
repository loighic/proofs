---
title: proofs, assignment 08
---


# proofs, assignment 08 (meeting)

---

## warm-up, extra credit problems

For 1 - 3, there is no feedback, either at the end of each line or when the proof is complete. Each one can only be submitted when it is correct, however. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent resize" guides="fitch" feedback="none" points="1" late-credit="1"}
1 P v Q, ~Q :|-: P 
2 ~N, ~N -> ~M :|-: ~M
3 R, S :|-: (S v T) & R 
~~~

---

## main problems

~~~{.ProofChecker .JohnsonSL options="fonts tabindent resize" guides="fitch" points="20" late-credit="15"}
4 Q v (R & T) :|-: ~Q -> T
5 P -> (Q & T) :|-: P -> Q
6 P -> Q, Q -> R :|-:  P -> R
7 P, (T & P) -> S, (P v Q) <-> (R & T) :|-: S
8 ~Q v R, S & T :|-: Q -> (T & R)
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---