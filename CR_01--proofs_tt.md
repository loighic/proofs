## proofs & truth tables

---

Each problem is worth 10 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 8 points. Your grade will be put on a 10 point scale when it is posted in Canvas. 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"}
1.1 (P & Q) & T :|-: P & T
~~~

You just have to take one step (and use one rule) to complete the proof in 1.2.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"}
1.2 P :|-: T v P
~~~

See sections 12.1 and 12.2 (or anywhere else in chapter 12) for how to begin when an argument contains more than one premise. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"} 
1.3 P, S :|-: S & (T v P)
1.4 P v Q, ~P :|-: ~P & Q
~~~

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample autoAtoms" points="10" late-credit="8"}
1.5 (S v ~T), ~(~S & T)
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.6 Which one of the following is correct about (S &or; &not;T), the first sentence in 1.5?
| This sentence is a tautology.
| This sentence is a contradiction.
|* This sentence is contingent.
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.7 Which one of the following is correct about &not;(&not;S &amp; T), the second sentence in 1.5?
| This sentence is a tautology.
| This sentence is a contradiction.
|* This sentence is contingent.
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.8 Which one of the following is correct about (S &or; &not;T), &not;(&not;S &amp; T), the sentences in 1.5?
|* The sentences are equivalent.
| The sentences are jointly inconsistent.
| The sentences are jointly consistent (but not equivalent).
~~~


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash autoAtoms" points="10" late-credit="8"}
1.9 P <-> ~S, S v ~T :|-: T -> P
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
1.10 Which one of the following is correct about the argument in the previous problem?
| This argument is valid.
|* This  argument is invalid.
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---
