~~~
Algoritmo "contagem inteligente"

Var
   C, I, F: inteiro
Inicio
   Escreva("Inicio: ")
   Leia(I)
   Escreva("Fim: ")
   Leia(F)
   C <- I
   Se (I <= F) entao
      Enquanto (C <= F) faca
         EscrevaL(C,",,,")
         C <- C + 1
      FimEnquanto
   Senao
      Enquanto (C >= F) faca
         EscrevaL(C,"...")
         C <- C - 1
      Fimenquanto
   Fimse





Fimalgoritmo
~~~