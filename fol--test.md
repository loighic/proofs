

~~~{.ProofChecker .ZachFOL2019 options="fonts tabindent render" guides="fitch" points="10" late-credit="9"}
2.1 Ex~F(x), Ax(F(x) or G(x)) :|-: ExG(x) 
2.2 AxF(x) :|-: AyF(y)
2.3 Ax(F(x) -> G(x)), AxF(x) :|-: AxG(x)
2.4 Ax(F(x) -> G(x)), F(a) :|-: Ex(F(x) & G(x))
2.5 ExF(x) :|-: Ex(F(x) or G(x))
2.6 Ex(F(x) -> P), AxF(x) :|-: P
2.7 Ex(F(x) -> G(x)), AxF(x) :|-: ExG(x)
2.8 Ex((F(x) & Ay(F(y) -> y=x)) & G(x)), ~G(a) :|-: ~F(a)
~~~

~~~{.ProofChecker .ZachFOLPlus2019 options="fonts tabindent render" guides="fitch" points="10" late-credit="9"}
3.1 Ex~F(x), Ax(F(x) or G(x)) :|-: ExG(x) 
3.2 G(a) <-> H(a), a=d :|-: G(d) <-> H(d)
3.3 Ax(G(x,a) -> x=a), G(b,a) :|-: Ax(G(x,b) -> x=b)
3.4 M(a) \/ N(b), N(b) -> b=d, ~M(a) :|-: N(d)
3.5 a=b, M(b,a) :|-: ExM(x,x)
3.6 Ax(F(x) & G(x)) :|-: AxF(x) 
3.7 :|-: AxAyAz((F(x,y) & F(y,z)) -> F(x,z))
~~~
