~~~
Algoritmo "SomadorNumerico"
var

   cont, N, S: inteiro
Inicio

   cont <- 1
   S <- 0
   Enquanto (cont <= 5) faca
      Escreva ("Digite o ",cont, "o. valor : ")
      Leia (N)
      S <- S + N
      cont <- cont + 1
   FimEnquanto
   Escreval("A soma de todos os valores foi ", S)
Fimalgoritmo
~~~

Mostrar qual foi o maior numero:
~~~
Algoritmo "SomadorNumerico"
var

   cont, N, S, maior, menor: inteiro
Inicio

   cont <- 1
   S <- 0
   Enquanto (cont <= 5) faca
      Escreva ("Digite o ",cont, "o. valor : ")
      Leia (N)
      Se (N > maior) entao
         maior <- N
      Fimse
      Se (N < menor) entao
         menor <- N
      Fimse
      S <- S + N
      cont <- cont + 1
   FimEnquanto
   Escreval("A soma de todos os valores foi ", S)
   EscrevaL("O maior valor digitado foi ", maior)
   EscrevaL("O menor valor digitado foi ", menor)
Fimalgoritmo
~~~
