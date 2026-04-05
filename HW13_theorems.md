---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## HW 13

---

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points.

In each problem, the sentence that is after the turnstile is a theorem. That means that a proof can be given with no premises. So, you will have to make an assumption to begin the proof. When you are making that assumption, think about whether you are going to be using the conditional introduction rule or one of the negation rules.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
13.1 :|-: P -> (P v Q)
13.1 :|-: T -> (S v T)
13.1 :|-: M -> (~L v M)

13.2 :|-: P -> (P v Q) & P
13.2 :|-: T -> (S v T) & T

13.3 :|-: P -> ~~P
13.3 :|-: S -> ~~S

13.4 :|-: (P & Q) -> Q
13.4 :|-: (P & Q) -> P
13.4 :|-: (S & T) -> T

13.5 :|-: ~(T & ~T)
13.5 :|-: ~(P & ~P)
13.5 :|-: ~(~R & R)
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson.</p>
 
---