

~~~{.ProofChecker .ZachFOL2019 options="fonts tabindent render" guides="fitch" points="10" late-credit="9"}
2.1 Ex~F(x), Ax(F(x) or G(x)) :|-: ExG(x) 
2.2 AxF(x) :|-: AyF(y)
2.3 Ax(F(x) -> G(x)), AxF(x) :|-: AxG(x)
2.4 Ax(F(x) -> G(x)), F(a) :|-: Ex(F(x) & G(x))
2.5 ExF(x) :|-: Ex(F(x) or G(x))
2.6 Ex(F(x) -> P), AxF(x) :|-: P
2.7 Ex(F(x) -> G(x)), AxF(x) :|-: ExG(x)
2.8 Ex(F(x) & Ay(F(y) -> P)), ~G(a) :|-: ~F(a)
2.8 Ex((F(x) & Ay(F(y) -> P)) & G(x)), ~G(a) :|-: ~F(a)
~~~


