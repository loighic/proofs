## proofs HW 2

Each problem is worth 7 points, and the whole assignment is worth 105 points. Problems that are submitted late will receive 6 points. Your grade will be put on a 10 point scale when it is posted in Canvas. 

--- 

For 2.1 - 2.12, you need to use the same rules as you used in HW 1. But, for 2.3 - 2.11, each proof requires multiple steps (and so multiple applications of one or more of the rules). See sections 12.2 and 12.6 for some examples. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="7" late-credit="6"}
2.1 (P & Q) & R :|-: R
2.2 (P & Q) & R :|-: (P & Q)
~~~

For 2.3 and 2.4, just add what is needed at the far right of each line.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="7" late-credit="6"}
2.3 (P & Q) & R :|-: P
|1.(P & Q) & R
|2.P & Q
|3.P


2.4 ((R & T) & S) & ~Q :|-: (R & T)
|1.((R & T) & S) & ~Q
|2.(R & T) & S
|3.R & T
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="7" late-credit="6"}
2.5 ((R & T) & S) & ~Q :|-: R
2.6 ~R & T :|-: ~R v S
2.7 ~P & Q :|-: T v Q
~~~

For 2.8, these sentences go on the lines following the premise, but they do NOT go in this order: 

`Q`, `T`, `(Q & T)`, `(R & T)`, `(S & Q)`

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="7" late-credit="6"}
2.8 (R & T) & (S & Q) :|-: Q & T 
2.9 S & T, R & Q :|-: R & S
2.10 P & R :|-: R v ~W 
~~~

For 2.11, these sentences go on the lines following the premise, but they do NOT go in this order: 

`(T v Q)`, `((T v Q) & S)`, `S`, `T`

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="7" late-credit="6"}
2.11 S & T :|-: (T v Q) & S
~~~

To do 2.13 - 2.15, see the subsection of 12.3 titled "Double negation." 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="7" late-credit="6"}
2.12 M v N, ~M :|-: N
2.13 P :|-: ~~P
2.14 ~P v Q, P :|-: Q
2.15 R v ~T, T :|-: R
~~~

<font size="6.5">&#9786;</font>

<p>&copy; 2019 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

--- 