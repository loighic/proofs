---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 12

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
12.1 P v Q, P -> T, Q -> T  :|-: T
12.2 P -> Q :|-: ~PvQ
12.2 ~P->Q :|-: PvQ
12.2 ~Q -> P :|-: PvQ
12.3 ~P -> (S -> R), Q -> (~P v R), (~P -> S) :|-: (Q -> R)
12.3 (S -> R), ~Q -> (S v T), S -> (R -> T) :|-: (~Q -> T)
12.4 N & (P v S) :|-: (N & P) v (N & S)  
12.5 ~(~T v ~R) :|-: T & R
~~~

&copy; 2022 Gregory Johnson 
 
---