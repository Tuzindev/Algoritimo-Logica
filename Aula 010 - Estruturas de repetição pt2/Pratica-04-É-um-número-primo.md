~~~~
Algoritmo "semnome"

Var
   C, N, contDiv: Inteiro

Inicio

   C <- 1
   contDiv <- 0
   Escreva("Digite um número: ")
   Leia(N)
   Repita
      Escreva(C)
      Se (N % C = 0) entao
         contDiv <- contDiv + 1
      Fimse
      C <- C + 1
   Ate (C > N)

   Se (contDiv > 2) entao
      Escreval(" o valor ", N," nao é primo!")
   Senao
      EscrevaL(" o valor ", N," é primo")
   Fimse



Fimalgoritmo
~~~~