~~~~
Algoritmo "semnome"

Var
   N, C, F: Inteiro
   R: Caractere

Inicio
Repita
   Escreva(" De qual numero voce quer saber o fatorial? ")
   Leia (N)
   C <- N
   F <- 1
   Repita
      Escreva(C, " x ")
      F <- F * C
      C <- C - 1

   Ate (C < 1)
   Escreval ("O valor do fatorial de ", N, " é:", F)
   Escreva ("Quer continuar? [S/N]")
   Leia(R)
   LimpaTela
Ate (R = "N")

Fimalgoritmo
~~~~
