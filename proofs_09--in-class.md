---
title: proofs, assignment 10
---


# proofs, assignment 10 (meeting)

---

## Instructions

For **1 - 4**, there is no feedback, either at the end of each line or when the proof is complete. Each one can be submitted if it is correct or incorrect.

---

## warm-up, extra credit problems


~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam resize" guides="fitch" feedback="none" points="1" late-credit="1"}
1 P v Q, ~P :|-: Q 
2 N, ~P, (~P & N) -> ~T :|-: ~T
3 P, T :|-: T & (P v Q) 
~~~

---

## main problems

~~~{.ProofChecker .JohnsonSL options="fonts tabindent exam" guides="fitch" feedback="none" points="12" late-credit="9"}
4 ~S v ~T :|-: S -> ~T 
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="22" late-credit="17"}
5 ~Q -> (K <-> (J & N)), ~Q & K  :|-: N
6 P -> S, ~Q :|-: (P v Q) -> S
7 P v Q, (~P <-> R) & T :|-:  R -> Q  
8 W -> (Q & R), (R v ~Q) -> ( S & T), T <-> M :|-:  W -> M
~~~

<font size="6.5">&#x1F383;</font>


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---