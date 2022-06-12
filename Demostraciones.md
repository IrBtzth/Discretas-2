# Demostraciones

# Clase 5
- ## **Teorema:  para todo n se tiene que \$n \leq n$** <a name="Teorema5.1"></a>

Demostracion: Sea n arbitrario.
Se demuestra por 

   $True$
   
$\equiv$ < Reflexividad de la igualdad >
  
  n=n
  
$\equiv$ < Elemento neutro >
   
  n+0=n 
  
$\Rightarrow$ < Introduccion del existe >
  ($\exists k|: n+k=n)$
  
$\equiv$  < Axioma 23 >

  $n\leq n$

- ## **Teorema (Sumar y restar):  Para todo $n$ y $m$ se tiene que $(n+m)-m=n$**

Dem: Por induccion sobre m.

Se demuestra por induccion sobre m. Se tomara $\varphi(m)$ como ($\forall$ n |: (n+m)-m=n)

**Caso base: m=0.**
Se demostrara por el metodo directo.

($\forall$ n |: (n+0)-0=n)

$\equiv$ <Elemento neutro de la suma>
  
  ($\forall$ n |: n-0=n)
  
$\equiv$ <Axioma 21>
  ($\forall$ n |: n=n)
  
$\equiv$ <Reflexivilidad de la igualdad>
  ($\forall$ n |: True)
  
 **Paso inductivo: sea m arbitrario.**
   
   Hipotesis inductiva: ($\forall$ n |: (n+m)-m=n)
   Tesis inductiva: ($\forall$ n |: (n+S(m))-S(m)=n)
   
   ($\forall$ n |: (n+S(m))-S(m)=n)

   $\equiv$ <Asociatividad de la suma>
   ($\forall$ n |: n+(S(m)-S(m))=n)
   
   $\equiv$ <Axioma 22>
   ($\forall$ n |: n+P(m-m)=n)
      1
   
   ## - **Teorema: si k'+k=0 entonces k'=0**
   
   Demostracion: Por induccion sobre k
   
   **Caso base: k=0**
   
Se debe demostrar que k'+0=0 $\Rightarrow$ k'=0 por metodo directo

   
   k'+0=0 $\Rightarrow$ k'=0
   
   $\equiv$ <Elemento neutro>
   
   k'=0 $\Rightarrow$ k'=0
   
   $\equiv$ < Reflexividad de la igualdad >
   
   $True$  
   
   **Paso inductivo: sea k arbitrario**
   
Hipotesis inductiva:  k'=0 $\Rightarrow$ k'=0
   
Tesis inductiva: k'+S(k)=0 $\Rightarrow$ k'=0 se demostrar por metodo directo 
   

k'+S(k)=0 $\Rightarrow$ k'=0
   
$\equiv$ <Axioma 14>   
   
   S(k'+k)=0 $\Rightarrow$ k'=0
   
$\equiv$  <Axioma 1>
   
   false $\Rightarrow$ k'=0 
   
$\equiv$ < Reflexividad de la igualdad >
   
   $True$ 
   
- ## **Teorema:  para todo $n$ y $m$ se tiene que si $n\leq m$  y $m \leq n$ entonces n=m** 

  Demostracion: Sean n y m arbitrarios

Se demostrara por debilitamiento
   
   $n\leq m  \land m \leq n$
   
$\equiv$ < Axioma 23 dos veces >
   
   $(\exists k|:n+k= m)\wedge (\exists k|:m+k= n)$

 $\equiv$  < Renombro variable dummy >
    
   $(\exists k|:n+k= m)\wedge (\exists k'|:m+k'= n)$
   
 $\equiv$ < Tomo testigos k y k' >
   
   $(n+k= m \wedge m+k'= n)$

$\equiv$ < Reemplaza n >
   
   $((m+k')+k= m \wedge m+k'= n)$
   
$\equiv$  < Asociatividad >
   
   $(m+(k'+k)= m \wedge m+k'= n)$
   
$\Rightarrow$ < Leibniz >
   
   $((m+(k'+k))-m= m-m \wedge m+k'= n)$

$\equiv$ <Conmutatividad y m-m=0>
   
   $((k'+k)+m)-m= 0 \wedge m+k'= n)$

$\equiv$ < Teorema de sumar y restar >
   
   $(k'+k= 0\wedge m+k'= n)$
   
$\Rightarrow$ < Teorema >
   
   $(k'= 0 \wedge m+k'= n)$
   
$\equiv$ < Reemplazo k'>
      
   $(k'= 0 \wedge m+0= n)$
                    
$\equiv$ < Elemento neutro >
   
   $(k'=0 \wedge m=n)$
   
$\Rightarrow$ < Debilitamiento >
     
   m=n
   
 $\equiv$ < Simetria de la igualdad  >
     
   n=m

Se ha demostrado por debilitamiendo que $n\leq m\wedge m\leq n\Rightarrow n$. Pero como $n$ y $m$ eran arbitrarios se puede generalizar obteniendo
$(\forall n|:(\forall m|:n\leq m\wedge m\leq n\Rightarrow n=m))$
   
- ## **Teorema (Transitividad del menor o igual): Para todo $n$, $m$ y $p$ se tiene que $n\leq m\wedge m\leq p\Rightarrow n\leq p$**

Dem: Sean n,m y p arbitrarios. Por debilitamiento.
   
   $(n \leq m \wedge m \leq p)$ 
   
$\equiv$ < Axioma 23 dos veces >
   
   $(\exists k|:n+k= m) \wedge (\exists k|:m+k= p)$
   
$\equiv$ < Tomo testigos k y k' >
    
  $( n+k= m) \wedge (m+k'= p)$

$\equiv$  < Reemplazo m >
   
  $(n+k= m) \wedge ((n+k)+k'= p)$
   
$\equiv$  < Asociatividad >
    
   $(n+k= m) \wedge (n+(k+k') = p)$
   
$\equiv$  < Debilito >
   
   $(n+(k+k') = p)$

 $\equiv$ < Introduccion del existe > 
    
   $(\exists k''|:n+k''=p)$
   
 $\Rightarrow$ $(\exists k''|:n+k''=p)$
   
   $\equiv$ < Axioma 23 >
   
   $n\leq p$
   
   Se ha demostrado por debilitamiento que $n\leq m\wedge m\leq p\Rightarrow n\leq$ . Como $n$, $m$ y $p$ eran arbitrarios entonces se puede generalizar obteniendo $(\forall n|:(\forall m|: \forall p|: n\leq m \wedge m\leq p\Rightarrow n\leq p))$
   


   
   
