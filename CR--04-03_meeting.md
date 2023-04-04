## Monday, April 3 meeting

These are the proofs that we went over in our class meeting on April 3. They are not an assignment, and you won't get credit for doing them. But if you want to do them again as practice, you can. Or, if you missed this class meeting, you can try them.

---

**warm-up problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
1. M v N, ~M :|-: N
2. ~M v N, M :|-: N
3. P, (S v P) -> T :|-: T 
~~~

---

**main problems**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
4. P -> ~Q, (~Q v R) -> ~S, P & T :|-: ~S 
5. H & ~G, (D -> L) <-> M, (M v G) & D :|-: ~G & L
~~~

In four of the next five proofs, you need to use the conditional introduction rule.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" submission="none"}
6. P & Q :|-: M -> P
7. N v (M & R) :|-: ~N -> R
8. P -> Q, Q -> R :|-: P -> R
9. (R & T) & N, (N & R) <-> S, S -> (Q v ~R) :|-: Q
10. Q -> (S & T) , (P <-> Q) & R :|-: P -> T
~~~


&copy; 2023 Gregory Johnson 
 
