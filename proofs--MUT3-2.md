---
title: t3, revision 2
---


# test 3 revision process 2

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="17" late-credit="17"}
1 P -> Q, R <-> P, P :|-: Q & R
2 (T & Q) & R,  (T & R) -> S :|-: S
3 W & R, (R v S) -> Q :|-: Q
4 R -> (Q v M), R & ~M :|-: Q
5 ~P v ~R, ~R <-> S, P :|-: S & ~R
6 P & Q, (~R v Q) -> S :|-: S & P
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---
