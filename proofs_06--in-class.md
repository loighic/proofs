---
title: proofs, assignment 7b
---


# proofs, assignment 07b (meeting)

---

~~~{.ProofChecker .JohnsonSL options="tabindent render" guides="fitch" points="20" late-credit="16"}
1 ~S v (P -> T), (S & P) :|-: T
2 ~P, (R v ~P) <-> (P v Q) :|-: Q
3  R, ~(R & S) v (Q -> W), Q & S :|-: W
4 N & ~G, (J -> T) <-> K, (K v G) & J :|-: ~G & T
~~~

For 5, list the premise as you normally do. On line 2, hit tab and then put the assumption. Hit tab again and put `:AS`. 

As long as you are working in the sub-proof, continue to hit tab before you put the TFL sentence. All of the rules that you already know can be used inside the sub-proof.

~~~{.ProofChecker .JohnsonSL options="tabindent render" guides="fitch" points="20" late-credit="16"}
5 (S & Q) <-> T :|-: T -> S 
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>

---
 
