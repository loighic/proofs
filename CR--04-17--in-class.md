---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## in-class assignment: 04/17

---

In 9.3 and 9.5, you are given the assumption or assumptions that you need. Carnap formats these lines with a single space for the indents. Ideally, you should use a tab space, but for these two, either just use single spaces for all of your indents or change the single spaces to tab spaces.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
9.1 P -> Q, P -> ~Q :|-: ~P
9.2 Q <-> P, ~(Q v R) :|-: ~P 
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
9.3 P -> Q :|-: ~(P & ~Q)
|P -> Q :PR
| P & ~Q :AS
| 
~~~

For 9.4, do all of the `&E` and `<->E` that you can before making an assumption for `~E`.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
9.4 P <-> (~Q & S), P & (~T -> ~S) :|-: ~Q & T 
~~~

This proof (in 9.5) requires two subproofs. Assume P first (for `->I`) and then assume ~Q (for `~E`). Also, take a look at section 14.10 in the textbook (&lsquo;Even more examples&rsquo;). A sub-proof inside a sub-proof looks like the fourth example in that section. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
9.5 ~(P & ~Q) :|-: P -> Q 
|~(P & ~Q) :PR
| P :AS
|  ~Q :AS
|  
~~~

&copy; 2023 Gregory Johnson
 
---