---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 14

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

In each problem, the sentence that is after the turnstile is a theorem. That means that a proof can be given with no premises. (Hint: You will have to make an assumption to begin the proof.)

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
14.1 :|-: P -> (P v Q)
14.1 :|-: T -> (S v T)
14.1 :|-: M -> (~L v M)
14.2 :|-: (P & Q) -> (P v R)
14.2 :|-: (L & P) -> (P v Q)
14.3 :|-: P -> ~~P
14.4 :|-: ~((Q -> P) & (Q & ~P))
14.4 :|-: ~((R & ~T) & (R <-> T))
14.4 :|-: ~((Q <-> S) & (Q & ~S))
14.4 :|-: ~((M & ~P) & (M -> P))
14.5 :|-: (S v T) -> (~T -> S)
14.5 :|-: (P <-> Q) -> (P -> Q)
14.5 :|-: (M v ~P) -> (P -> M)
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson.</p>
 
---