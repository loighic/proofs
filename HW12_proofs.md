---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 12

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.1 Q & R, Q -> (P v S), ~(S & R)  :|-: P
~~~

In 12.2, you have to make two assumptions. The first assumption is made so that you can use the conditional introduction rule. The second assumption will be discharged with either the negation introduction or negation elimination rule.

You also have to make two assumptions in problem 12.3. Both of those assumptions will be discharged with either the negation introduction or negation elimination rule. (Hint for 12.3: On line 2, make your assumption the opposite of what you, eventually, want.)

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.2 F -> (G -> H), ~J -> (F v H), F -> G :|-: ~J -> H
~~~

In 12.3, you are given the assumptions that you need. Carnap formats these lines with a single space for the indents. Ideally, you should use a tab space, but for these two, either just use single spaces for all of your indents or change the single spaces to tab spaces. Also, be aware of your spacing and how you are formating the sub-proofs. If you need to delete everything that is in the box and type the proof yourself. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.3 P v Q :|-: Q v P
|P v Q :PR
| ~(P v Q) :AS
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
