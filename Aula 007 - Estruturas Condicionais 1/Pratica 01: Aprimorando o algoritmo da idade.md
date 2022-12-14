~~~
Algoritmo "CalculoIdade"
var
   AnoAtual, nasc, idade: inteiro

inicio
      Escreva("Em que ano estamos? ")
      Leia(AnoAtual)
      Escreva("Em que ano você nasceu? ")
      Leia(nasc)
      idade <- AnoAtual - nasc
      Escreva ("Em ", AnoAtual, " voce tera ", idade, " anos")
      Se (idade >= 21) entao
         Escreval (" e ja tera atingido a maioridade. ")
      FimSe


fimalgoritmo
~~~

Uma condição mais completa:

~~~
SE eu tiver dinheiro ENTÃO
vou fazer uma viagem pra Disney
SENÃO   
vou ficar em casa
~~~