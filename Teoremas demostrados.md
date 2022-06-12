# Teoremas demostrados 
Recordemos que la teoria de la aritmetica de peano es:
Lista de constantes y operaciones {S, P, +, *, -,^,0, 1, 2, 3, 4, 5, 6, 7, 8, 9} de aridad 1, 1, 2, 2, 2, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0  respectivamente y se usaran como variables las letras n, m , r, x, y, z, w, etc ( a esta lista se le llama firma de la teoria). Se enuncian la lista de predicados que se usaran, en este caso se usara el predicado de la igualdad = binario (de dos argumentos o que predica sobre dos sujetos), el predicado <<, \leq≤, >> y  \geq≥ binarios.
1) No existe n tal que S(n)=0
2) Si S(n)=S(m) entonces n=m      (Esta diciendo que S es una funcion inyectiva)
3) Sea \varphi(n)φ(n) una formula en el lenguaje de la aritmetica. Si es cierto \varphi(0)φ(0)
y tambien para cada n se tiene que \varphi(n)\Rightarrow\varphi(S(n))φ(n)⇒φ(S(n)), entonces (\forall n|:\varphi(n))
4) 1=S(0)
5) 2=S(1)
6) 3=S(2)
7) 4=S(3)
8) 5=S(4)
9) 6=S(5)
10) 7=S(6)
11) 8=S(7)
12) 9=S(8)
13) n + 0 = n
14) n + S(m) = S(n+m)
15) n*0 = 0
16) n* S(m)=n* m+n
17) $n^{0}=1$
18) $n^{m+1}=n^{m}*n^{1}$
19) P(0)=0   P es predecesor, se define asi porque el cero no tiene predecesor
20) P(S(n))=n
21) n-0 = n
22) n-S(m)=P(n-m)
23) $n \leq m  \equiv (\exists k|:n+k=m)$ 
24) $n < m \equiv n\leq m\wedge n\neq$
25) $n\geq m \equiv m\leq n$
26) $n > m \equiv n\geq m\wedge n\neq m$
27) $(n < m < p) \equiv n < m \wedge m < p $ 
28) $n\leq m\leq p\equiv n\leq m\wedge m\leq p$
29) $n< m\leq p\equiv n< m\wedge m\leq p$
30) $n\leq m< p\equiv n\leq m\wedge m< p$
31) $n\neq m \equiv \neg(n=m)n$
# Clase 4
- Teorema: para todo n se tiene que n*1=n
- Lema: Para todo n se tiene que 0*n=0
- Teorema: ($\forall n∣:(\forall m∣:$ n∗m=m∗n))
- Teorema: ($\forall p|:(\forall n|:(\forall m|:$ (m+n)* p = m* p + n* p)
- Teorema: ($\forall n|:(\forall m|:(\forall p|:$ (n* m)* p =n*(m* p))))

# Clase 5 
- Teorema:  para todo n se tiene que \$n \leq n$ 
- Teorema: si $k'+k=0$ entonces $k'=0$
- Teorema:  para todo $n$ y $m$ se tiene que si \$ m \leq n$ y  $ n \leq m$ entonces n=m   
- Teorema **(Transitividad del menor o igual)**: Para todo $n$, $m$ y $p$ se tiene que $ n\leq m \wedge m \leq p \Rightarrow n \leq p$

# Clase 6

- [Teorema6.1:](#teorema6.1:): $p*(m+n)=p* m+ p* n$
- Teorema6.2:  $n-n=0$
- Teorema6.3:  $m\leq n\Rightarrow m+p\leq n +p$
- Teorema6.4:  $m\leq n \Rightarrow 0\leq n-m$ 
- Teorema6.5: Si $m < n$ , entonces se tiene que $n\leq p\Rightarrow n-m\leq p-m$ 
- Teorema (para demostrar en la practica): Si $a\leq n \wedge a \leq m$, entonces $n \neq m\equiv n-a\neq m-a$ donde $a$ es una constante.

# Clase 6
   
   ## Teorema6.1: 
   
   Demostracion:




