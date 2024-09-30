## proofs & truth tables

---

Each problem is worth 12 points, and the whole assignment is worth 100 points (although you can get 108). Problems that are submitted late will receive 10 points. Your grade will be put on a 10 point scale when it is posted in Canvas. 

---

Read sections 12.1 - 12.3. The first problem (1.1) is done for you. Just hit submit.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="12" late-credit="10"}
1.1 (P & Q) & T :|-: P & T
|1.(P & Q) & T	:PR
|2.(P & Q)	:&E 1
|2.T	:&E 1
|3.P	:&E 2
|4.P & T	:&I 2,3
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="12" late-credit="10"}
1.2 P :|-: T v P 
1.3 P, S :|-: S & (T v P)
1.4 P v Q, ~P :|-: ~P & Q
~~~

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
1.5 (S v ~T), ~(~S & T)
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.6 Which one of the following is correct about (S &or; &not;T), the first sentence in 1.5?
|* This sentence is a tautology.
| This sentence is a contradiction.
| This sentence is contingent.
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.7 Which one of the following is correct about &not;(&not;S &amp; T), the second sentence in 1.5?
|* This sentence is a tautology.
| This sentence is a contradiction.
| This sentence is contingent.
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.8 Which one of the following is correct about (S &or; &not;T), &not;(&not;S &amp; T), the sentences in 1.5?
|* The sentences are equivalent.
| The sentences are jointly inconsistent.
| The sentences are jointly consistent (but not equivalent).
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---
