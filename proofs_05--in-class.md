---
title: proofs, assignment 5
---

# proofs, assignment 05 (meeting)

---

## warm-up, extra credit problems

Remove the questions marks and &ldquo;...&rdquo; in 2 and 3 and complete the proofs. 

~~~{.ProofChecker .JohnsonSL options="tabindent render" guides="fitch" points="1" late-credit="1"}
1 (N & R) -> P, N & R :|-: P
~~~
~~~{.ProofChecker .JohnsonSL options="tabindent render" guides="fitch" points="1" late-credit="1"}
2 ~~S, ~S v T :|-: T
|~~S		:PR
|~S v T		:PR
|?		:vE ...
~~~
~~~{.ProofChecker .JohnsonSL options="tabindent render" guides="fitch" points="1" late-credit="1"}
3 S, ~S v T :|-: T
|S	:PR
|~S v T		:PR
|?		:DN 1
|?		:vE ...
~~~

---

## main problems

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
4 P <-> N, ~S v P, S :|-: N 
5 T <-> S, T -> W, S :|-: T & W
6 Q -> (P v S), R v Q, ~R :|-: P v S
7 (T & Q) & ~R,  (T & ~R) -> S :|-: S
8 ([S & Q] & T), ~(R v N) <-> [S & T], W v (R v N) :|-: W
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---

