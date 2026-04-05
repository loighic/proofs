---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 14

---

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

In each problem, the sentence that is after the turnstile is a theorem. That means that a proof can be given with no premises. So, you will have to make an assumption to begin the proof. When you are making that assumption, think about whether you are going to be using the conditional introduction rule or one of the negation rules.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
14.1 :|-: (P & S) -> (P v Q)
14.1 :|-: (T & M) -> (S v T)
14.1 :|-: (M & R) -> (~L v M)

14.2 :|-: ~((P & Q) & ~Q)
14.2 :|-: ~((R & S) & ~R)

14.3 :|-: ((M v ~P) -> (P -> M))
14.3 :|-: (S v ~Q) -> (Q -> S)
14.3 :|-: (~T v W) -> (T -> W)
14.3 :|-: (P <-> Q) -> (P -> Q)

14.4 :|-: ~((Q -> P) & (Q & ~P))
14.4 :|-: ~((R & ~T) & (R <-> T))
14.4 :|-: ~((Q <-> S) & (Q & ~S))
14.4 :|-: ~((M & ~P) & (M -> P))

14.5 :|-: (~P & ~Q) -> ~(P v Q) 
14.5 :|-: (~R & ~T) -> ~(R v T)
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson.</p>
 
---