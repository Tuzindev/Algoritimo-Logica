1 forma de fazer:
~~~
Algoritmo "UmaPartidaDeFutebol"

Var
   GolsC, GolsA, M: Inteiro

Inicio
   Escreva ("Gols marcados pelo Cruzeiro: ")
   Leia (GolsC)
   Escreva ("Gols marcados pelo Atletico: ")
   Leia (GolsA)

   M <-Abs(GolsC - GolsA)

   Se (M = 0) entao
      Escreva("Placar empatado")
   Senao
      Se (M >= 1) e (M <= 3) entao
         Escreva ("Placar normal")
      Senao
         Se (M >= 4) entao
            Escreva ("Goleada")
         Fimse
      Fimse
      '   Fimse
   Fimse

fimalgoritmo
~~~
