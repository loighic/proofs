---
title: proofs, assignment 9
---


# proofs, assignment 9 (at-home, contingent)

---

## instructions

**This is a contingent assignment.** See the explanation for contingent assignments in the &ldquo;test 2 pre-test assignments&rdquo; module in Canvas.

<font color="#9900FF">**Do this alone.** Contact the instructor if you need help.</font>

---

## warm-up, extra credit problems

For 1 & 2, there is no feedback, either at the end of each line or when the proof is complete. Each one can only be submitted when it is correct, however. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent resize" guides="fitch" feedback="none" points="1" late-credit="1"}
1 ~P, ~P -> (S v T) :|-: S v T
2 L v M, ~L :|-: M 
~~~

---

## main problems

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent resize" guides="fitch" points="20" late-credit="16"}
3 L <-> M :|-: M -> L
4 S v (Q & W) :|-: ~S -> W
5 S -> T, T -> W :|-:  S -> W
~~~

In 6, you have to use the conditional introduction rule to get <font color="#9900FF">(P &rarr; W)</font>. 

There is no way just to remove the <font color="#9900FF">Q</font> from <font color="#9900FF">((P & Q) &rarr; W)</font> and get <font color="#9900FF">(P &rarr; W)</font>.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent resize" guides="fitch" points="20" late-credit="16"}
6 (P & Q) -> W, T & Q :|-: P -> W
~~~

Remember, you only start a sub-proof and make an assumption when you want to get a conditional. If you don't need a conditional, don't start a sub-proof.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent resize" guides="fitch" points="20" late-credit="16"}
7 (T & W) v P, (S v T) <-> M, ~P :|-: M & ~P
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---