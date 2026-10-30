---
title: t3, revision 2
---


# test 3 revision process 2

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="20"}
1 P -> Q, R <-> P, P :|-: Q & R
2 (T & Q) & R,  (T & R) -> S :|-: S
3 R -> (Q v M), R & ~M :|-: Q
4 ~P v ~R, ~R <-> S, P :|-: S & ~R
5 P & Q, (~R v Q) -> S :|-: S & P
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---
