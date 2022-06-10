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
   
   $\equiv$ <Reflexividad de la igualdad>
   
   $True$  
   
   **Paso inductivo: sea k arbitrario**
   
Hipotesis inductiva:  k'=0 $\Rightarrow$ k'=0
   
Tesis inductiva: k'+S(k)=0 $\Rightarrow$ k'=0 se demostrar por metodo directo 
   

k'+S(k)=0 $\Rightarrow$ k'=0
   
$\equiv$ <Axioma 14>   
   
   S(k'+k)=0 $\Rightarrow$ k'=0
   
$\equiv$  <Axioma 1>
   
   false $\Rightarrow$ k'=0 
   
$\equiv$ <Reflexividad de la igualdad>
   
   $True$ 
