---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 13

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
13.1 P v Q, P -> T, Q -> T  :|-: T
13.2 P -> Q :|-: ~PvQ
13.2 ~P->Q :|-: PvQ
13.2 ~Q -> P :|-: PvQ
13.3 ~P -> (S -> R), Q -> (~P v R), (~P -> S) :|-: (Q -> R)
13.3 (S -> R), ~Q -> (S v T), S -> (R -> T) :|-: (~Q -> T)
13.4 N & (P v S) :|-: (N & P) v (N & S)  
13.5 ~(~T v ~R) :|-: T & R
~~~

&copy; 2022 Gregory Johnson 
 
---