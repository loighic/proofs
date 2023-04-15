---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 12

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.1 Q & R, Q -> (P v S), ~(S & R)  :|-: P
~~~

---

The proofs in 12.2 and 12.3 are started for you. Carnap formats these lines with a single space for the indents. Ideally, you should use a tab space, but for these two, either just use single spaces for all of your indents or change the single spaces to tab spaces. Also, be aware of your spacing and where the sub-proofs are. If it will be easier, delete everything that is in the box (or everything after the premises) and type the proof yourself. 

---

In 12.2, you have to make two assumptions. The first assumption is made so that you can use the conditional introduction rule. The second assumption will be discharged with either the negation introduction or negation elimination rule.

Replace the `?` on line 4, and when you do so, make sure that the &not;H on line 5 remains as the beginning of the second sub-proof.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.2 F -> (G -> H), ~J -> (F v H), F -> G :|-: ~J -> H
|F -> (G -> H) :PR
|~J -> (F v H) :PR
|F -> G :PR
| ? :AS
|  ~H :AS
|  
~~~


~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.3 P v Q :|-: Q v P
|P v Q :PR
| ~(Q v P) :AS
|  ~P :AS
|  
|  
|  
| P
| 
| 
|Q v P
~~~


~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.4 ~P v ~Q :|-: ~(P & Q)
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.5 (A -> B) & (~A -> C), ~B :|-: C
~~~

&copy; 2023 Gregory Johnson 
 
---
