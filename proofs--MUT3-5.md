---
title: t3, revision 5
---


# test 3, revision process, 5

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="20"}
1 (Q <-> P), (~T & W) :|-: ([P v T] -> Q)
2 (S -> ~T), (T v Q) :|-: ([P & S] -> [P & Q])
3 ~S -> ~T, T :|-: S
4 S <-> ~P, P v ~S :|-: P
5 ~P v ~Q	:|-: ~(P & Q)
~~~

<font size="6.5">&#9786;</font>

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
