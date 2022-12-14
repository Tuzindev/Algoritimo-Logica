  ~~~
  Algoritmo "Calculo IMC"
var
   M, A,IMC: real

inicio
   Escreva("Massa (Kg): ")
   Leia(M)
   Escreva("Altura (m): ")
   Leia(A)
   IMC <- M /(A * A)
   Escreval("IMC: ",IMC:5:2)
   Se (IMC >= 18.5) e (IMC < 25) entao
      Escreva("Parabens, voce esta no peso ideal")
   Senao
      Escreva("Voce nao esta no peso ideal")
   Fimse



fimalgoritmo
~~~