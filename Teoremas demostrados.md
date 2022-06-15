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

- [Teorema6.1:](#teorema6.1) $p*(m+n)=p* m+ p* n$
- [Teorema6.2:](#teorema6.2) $n-n=0$
- [Teorema6.3:](#teorema6.3)  $m\leq n\Rightarrow m+p\leq n +p$
- [Teorema6.4:](#teorema6.4)  $m\leq n \Rightarrow 0\leq n-m$ 
- [Teorema6.5:](#teorema6.5) Si $m < n$ , entonces se tiene que $n\leq p\Rightarrow n-m\leq p-m$ 
- [Teorema6.6 (para demostrar en la practica):](#teorema6.6) Si $a\leq n \wedge a \leq m$, entonces $n \neq m\equiv n-a\neq m-a$ donde $a$ es una constante.

# Clase 6

   <a name="teorema6.1"></a>
   - ## Teorema6.1:  $p*(m+n)=p* m+ p* n$
   
   Demostracion: partiendo de un lado.
   
   $p*(m+n)$
$\equiv$ <Conmutividad>
   
  $(m+n)*p$
   
$\equiv$ < Distributiva >
   
  $m*p+n*p$
$\equiv$ < Conmutatividad dos veces >
  
  $p*m+p*n$
   
  <a name="teorema6.2"></a>
  - ## Teorema6.2: $n~-~n=0$
   
   $n~-~n=0$
   
   **Caso base: n=0**

   0-0
$\equiv$ < Axioma 21 >
   
   0
   
 **Paso inductivo: sea n arbitrario**
   
   Hipotesis inductiva: $n-n=0$  
   Tesis inductiva: $n-S(n)=0$
   
   $S(n)-S(n)=0$
  
   $\equiv$   < Axioma 22 >
   
   $P(S(n)-n)=0$
   
   $\equiv$   < Definicion de sucesor >
   
   $P((n+1)-n)=0$
   
   $\equiv$   < Comutatividad >
   
   $P((1+n)-n)=0$
   
   $\equiv$   < Teorema de sumar y restar >
   
   $P(0)=0$
   
   $\equiv$   < Reflexividad de la igualdad >
   
   $True$
   
  <a name="teorema6.3"></a>
   - ## Teorema6.3:  $m\leq n \Rightarrow m+p\leq n +p$
   
   $m\leq n$
   
   $\equiv$ < Axioma 23 >
   
   $(\exists k|: m+k=n)$  
   
   $\equiv$ < Leibniz como axioma y paridad >
   
   $(\exists k|:(m+k) + p =n + p)$  
   
   $\equiv$ < Asociatividad >
   
   $(\exists k|:m+ (k + p) =n + p)$ 
   
   $\equiv$ < Comutatividad >
   
   $(\exists k|:m+ (p + k) =n + p)$ 
   
   $\equiv$ < Asociatividad >
   
   $(\exists k|:(m+p) + k = n + p)$ 
   
   $\equiv$ < Axioma 23>
   
   $(m+p\leq n+p)$
   
   <a name="teorema6.4"></a>
   - ## Teorema6.4:  $m\leq n \Rightarrow 0\leq n-m$ 
   
   $m\leq n$
   
   $\equiv$ < Axioma 23 >
   
   $(\exists k|: m+k=n)$ 
   
   $\equiv$ < Leibniz como axioma y paridad >
   
   $(\exists k|:(m+k) -m  =n -m)$  
   
   $\equiv$ < Comutatividad >
   
   $(\exists k|:(k +m)-m =n -m)$
   
   $\equiv$ < Teorema de sumar y restar >
   
   $(\exists k|: k =n -m)$
   
   $\equiv$ < Neutro de la suma >
   
   $(\exists k|:0+k=n-m)$
   
   $\equiv$ < Def del menor o igual, o Ax 23>
   
   $(0 \leq n-m)$
   
   Se ha demostrado por debilitamiento el teorema.
   
   <a name="teorema6.5"></a>
   - ## Teorema6.5: Si $m < n$ , entonces se tiene que $n\leq p\Rightarrow n-m\leq p-m$ 
                              
     Demostracion: Se asume como hipotesis que $m\leq n$
     Por induccion sobre m
     
     Caso base m= 0                               

     $(n\leq p \Rightarrow n-0\leq p-0)$ 
     
Se debe demostrar que $n\leq p\Rightarrow n-0\leq p-0$ pero esto aplicando el axioma 21 seria equivalente a $n\leq p\Rightarrow n\leq p$ lo cual es una tautologia

**Paso inductivo: Sea m arbitrario**
                              
Hipotesis Inductiva: $(n\leq p \Rightarrow n-m\leq p-m)$    
Tesis Inductiva: $(n\leq p \Rightarrow n-S(m)\leq p-S(m))$ 
                              
   $(n\leq p \Rightarrow n-S(m)\leq p-S(m))$ 
   
   $\equiv$ < Axioma 22 >
   
   $(n\leq p \Rightarrow P(n-m)\leq P(p-m))$ 
   
   $\equiv$ < Axioma 6.3 >
   
   $(n\leq p \Rightarrow P(n-m)+1\leq P(p-m)+1)$  
   
   $\equiv$ < Definicion de sucesor >
   
   $(n\leq p \Rightarrow S(P(n-m))\leq S(P(p-m)))$
   
   $\equiv$ < Como $m<n$, entonces $n-m$ no es $0$ y por lo tanto se puede aplicar el axioma 20 >
   
   $(n\leq p \Rightarrow n-m\leq p-m))$
   
   $\equiv$ < Por hipotesis >
   
   $(n\leq p \Rightarrow n \leq p))$
   
   $\equiv$ < Reflexividad de la igualdad >
   
   $True$
  
   Se ha demostrado el teorema por induccion
   
   <a name="teorema6.6"></a>
  - ## Teorema6.6 (para demostrar en la practica): Si $a\leq n$ y $a\leq m$, entonces $n\neq m\equiv n-a \neq m-a$ donde a es una constante.
   
   # Practica 3
   
   - [TeoremaP3.1:](#teoremaP3.1) Si $n\neq 0\Rightarrow S(P(n))=n$
   - [TeoremaP3.2 (para demostrar en la practica):](#teoremaP3.2)  Si $a\leq n$ y $a\leq m$ entonces  $n\neq m\equiv n-a\neq m-an$
   - [TeoremaP3.3:](#teorema3.3) $\neg(n<m) \equiv n\geq m$
   - TeoremaP3.4: $\neg(\exists n|:0< n<1)\equiv (\forall n|:n=0\vee n\geq 1)$
   - TeoremaP3.5: $(\forall n|:n=0\vee n\geq 1)$
                                                 
   <a name="teoremaP3.1"></a>
   - ## TeoremaP3.1: Si $n\neq 0\Rightarrow S(P(n))=n$
   
   **Caso base: n=0.**
   En este caso el antecedente de la implicacion da falso y por lo tanto la implicacion seria verdadera.
   
   **Paso inductivo: Sea n arbitrario.**
   
   Hipotesis inductiva: $n\neq 0\Rightarrow S(P(n))=n$
   Tesis inductiva: $S(n)\neq 0\Rightarrow S(P(n))=S(n)$
   
   $S(n)\neq 0\Rightarrow S(P(n))=S(n)$
   
   $\equiv$ < Axioma 20>
   
   $S(n)\neq 0\Rightarrow S(n)=S(n)$
   
   $\equiv$ < Reflexividad de la igualdad >
   
   $S(n)\neq 0\Rightarrow True$

   $\equiv$ < Axioma 1 >
   
   $ True \Rightarrow True$
   
   $\equiv$ 
   
   $True$
   
   <a name="teoremaP3.2"></a>
   - ## TeoremaP3.2 (para demostrar en la practica):  Si $a\leq n$ y $a\leq m$ entonces  $n\neq m\equiv n-a\neq m-an$
   
   Demostracion:  Por doble implicacion
   Primero se demuestra el sentido <=  por fortalecimiento

   $n\neq m$

   $\equiv$  < Axioma 31>
   
   $\neg(n= m)$ 
   
   $\Leftarrow$<Leibniz y paridad impar> 
   
   $\neg(n-a= m-a)$    E: como z op a

   $\equiv  < Axioma 31 >
   
   $n-a\neq m-a$

   Vamos a demostrar el sentido $\Rightarrow$ por fortalecimiento
   
   $ n−a \neq m-a$
   
   $\Rightarrow$ < Axioma 31 >
   
   $\neg(n-a= m-a)$

   $Rightarrow$ < Leibniz y paridad impar > 
   
   $\neg((n-a)+a= (m-a)+a)$    E: como z+a

   < Teorema restar y sumar con la hipotesis $a<n$ y $a<m$  >
   
   $\neg(n= m)$ 
   
   $\Rightarrow$ < Axioma 31 >
   
   $n\neq m$

   Se ha dmoemostrado por doble implicacion
   
   <a name="teoremaP3.3"></a>
   - ## TeoremaP3.3: $ \neg(n < m) \equiv n\geq m $
      
   $\neg(n < m)$
   
   
   
   
   
   
   
                                                    

                              
   
                              
                              
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   




