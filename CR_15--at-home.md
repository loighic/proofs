---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## proofs, assignment 17 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

---

**Remember!** To begin, see if you can do conjunction elimination, disjunction elimination, conditional elimination, or biconditional elimination. 

Next, determine if you need a conditional. If you  do, then you will need to use the conditional introduction rule. When using this rule, you know what the assumption will be and what will be on the last line of the sub-proof.

Finally, if you need to use the negation intro or elim rules, then, when choosing the assumption, think about what you want when the sub-proof is finished. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="15"}
17.1 R <-> P, ~P :|-: ~R
17.2 ~P -> (R <-> S) :|-: (S & ~P) -> R
17.3 T v ~W :|-: ~(~T & W)
17.4 (R & T) <-> ~S :|-: ~R -> S
17.5 Q & R, Q -> (P v S), ~(S & R)  :|-: P
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---