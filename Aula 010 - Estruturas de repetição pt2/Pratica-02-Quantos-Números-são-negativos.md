~~~~
Algoritmo "semnome"

Var
   N, C, TotN: Inteiro

Inicio
   C <- 1
   TotN <- 0
   Repita
      Escreva("Digite um número: ")
      Leia(N)
      Se (N<0) entao
         TotN <- TotN + 1
      Fimse
      C <- C + 1
   Ate (C > 5)
   EscrevaL("Foram digitador ", TotN, " valores negativos.")


Fimalgoritmo
~~~~
