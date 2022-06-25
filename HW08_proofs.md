## HW 8

Problems 8.1 through 8.5 are worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

8.6 is extra credit and is worth 10 points. You have to use the negation-elimination rule in this proof.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
8.1 ~Q -> (K <-> (J & B)), ~Q & K  :|-: B
8.2 ~B v C, D & A :|-: B -> (A & C)
8.3 P -> Q, Q -> R :|-:  P -> R 
8.4 P v Q, (~P <-> R) & T :|-:  R -> Q  
8.5 P -> (Q & R), (R v ~Q) -> ( S & T), T <-> U :|-:  P -> U
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"}
8.6  ~P -> ~Q, Q :|-: P
~~~

&copy; 2022 Gregory Johnson 
 
---