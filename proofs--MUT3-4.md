---
title: t3, revision 4
---


# test 3, revision process, 4

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="16" late-credit="16"}
1 P v Q :|-: ~P -> Q
2 P -> (S & T) :|-: P -> T
3 Q v (R & T) :|-: ~Q -> T
4 P v Q, (~P <-> R) & T :|-:  R -> Q 
5 ~S v R, Q & W :|-: S -> (R & W)
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="20"}
6 ((P v S) -> (~Q ∨ M)) :|-: ((P & Q) -> M)
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
