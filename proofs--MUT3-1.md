---
title: t3, revision 1
---


# test 3 revision process 1

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="10" late-credit="10"}
1 P <-> (Q & T), P :|-: (Q & T)
2 ~P <-> (Q & T), ~P :|-: T
3 P <-> Q, P & ~T :|-: Q
4 (P -> N) & ~R, P :|-: N
5 Q v T, ~S & ~Q :|-: T
6 (R & T), (T -> Q) :|-: (Q v P)
7 M <-> P, P & R :|-: M v N
8 P -> Q, (Q -> P) & R :|-: P <-> Q
9 ~N v P, ~N <-> S, ~P :|-: S
~~~

If you are having trouble with 10, consult section 12.3, especially the subsection titled "Double negation."

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="10" late-credit="10"}
10 ((~P v Q) & R), P :|-: Q
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---

