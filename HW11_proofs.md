---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 11

Problem 11.5 - 11.9 are each worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

---

**warm-up, extra credit problems**

There is no feedback, either at the end of each line or when the proof is complete. Each can be submitted at any time (whether it is complete or incomplete, **correct or incorrect**), and each can only be submitted once.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render exam" guides="fitch" feedback="none" points="1" late-credit="1"}
11.1 P v Q, ~Q :|-: P
11.2 P v ~Q, Q :|-: P
11.3 ~P v Q, ~Q :|-: ~P
11.4 ~P v ~Q, Q :|-: ~P
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
11.5 P -> Q, P -> ~Q :|-: ~P
11.6 Q <-> P, ~(Q v R) :|-: ~P 
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
11.7 P -> Q :|-: ~(P & ~Q)
|P -> Q :PR
| P & ~Q :AS
| 
~~~

For 11.8, do all of the `&E` and `<->E` that you can before making an assumption for `~E`.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
11.8 P <-> (~Q & S), P & (~T -> ~S) :|-: ~Q & T 
~~~

This proof (in 11.9) requires two subproofs. Assume P first (for `->I`) and then assume ~Q (for `~E`). Also, take a look at section 14.10 in the textbook (&lsquo;Even more examples&rsquo;). A sub-proof inside a sub-proof looks like the fourth example in that section. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
11.9 ~(P & ~Q) :|-: P -> Q 
~~~

&copy; 2022 Gregory Johnson 
 
---