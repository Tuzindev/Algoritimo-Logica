1 das formas
~~~
Algoritmo "AproveitamentoAluno"

Var
   N1, N2, Media: Real


Inicio
   Escreva ("Nota da primeira prova: ")
   Leia(N1)
   Escreva ("Nota da segunda prova: ")
   Leia(N2)
   Media <- (N1 + N2) / 2

   EscrevaL("Sua media é de: ", Media)

   Se (Media <= 10) e (Media >= 9) entao
      EscrevaL ("Sua nota é A")
   Senao
      Se (Media <= 8)  e (Media >= 7) entao
         Escreva ("Sua nota é B")
      Senao
         Se (Media <= 6) e (Media >= 5) entao
            Escreva ("Sua nota é C")
         Senao
            Se (Media <= 4) e (Media >= 5) entao
               Escreva ("Sua nota é D)
            Senao
               Escreva ("Reprovado")

            Fimse
         Fimse
      Fimse
   fimse




Fimalgoritmo
~~~
