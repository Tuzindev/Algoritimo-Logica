~~~
Algoritmo "CriacaEsperanca"

Var
   D: Inteiro
   
   Valor: Real
Inicio
      EscrevaL ("---------------------------")
      EscrevaL ("     CRIANÇA ESPERANÇA     ")
      EscrevaL ("---------------------------")
      EscrevaL (" Muito obrigado por ajudar!")
      EscrevaL (" [1] para doar R$10 ")
      EscrevaL (" [2] para doar R$25 ")
      EscrevaL (" [3] para doar R$50 ")
      EscrevaL (" [4] para doar outros valores ")
      EscrevaL (" [5] para cancelar ")
      Leia (D)
      Escolha(D)
                Caso 1
                     Valor <- 10
                
                Caso 2
                     Valor <- 25
                
                Caso 3
                     Valor <- 50
                
                Caso 4
                     Escreva ("Qual o valor da doação? R$")
                     Leia (Valor)
                
                Caso 5
                     Valor <- 0
                     
      FimEscolha
      EscrevaL ("---------------------------")
      EscrevaL ("   SUA DOAÇÃO FOI DE R$", Valor)
      EscrevaL ("   MUITO OBRIGADO!   ")
      EscrevaL ("---------------------------")


Fimalgoritmo
~~~

Outra forma: 
~~~
Algoritmo "UmaPartidaDeFutebol"

Var
   GolsC, GolsA, M: Inteiro
   Resultado: Caractere

Inicio
   Escreva ("Gols marcados pelo Cruzeiro: ")
   Leia (GolsC)
   Escreva ("Gols marcados pelo Atletico: ")
   Leia (GolsA)

   M <-Abs(GolsC - GolsA)

   Escolha(M)
   Caso 0
      Resultado <- ("Partida Empatada")
   Caso 1,2,3
      Resultado <- ("Partida Normal")
   OutroCaso
      Resultado <- ("Goleada")
   Fimescolha
   
   EscrevaL("Diferença de gols:", M)
   Escreva("Status:", Resultado)
      
fimalgoritmo
~~~