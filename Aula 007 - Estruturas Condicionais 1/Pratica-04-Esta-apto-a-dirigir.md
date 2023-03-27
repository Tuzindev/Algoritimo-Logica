~~~
Algoritmo "AptidaoCnh"


Var

      ano, nasc, idade: inteiro

Inicio
      EscrevaL("----------------------------")
      EscrevaL("DEPARTAMENTO DE TRÂNSITO")
      Escreva("----------------------------")
      
      Escreva("Ano Atual (yyyy):")
      Leia(ano)
      Escreva("Ano de Nasimento (yyyy):")
      Leia(nasc)
      
      Escreva("---------")
      Escreva("STATUS")
      Escreva("---------")
      
      idade <- (ano - nasc)
      Escreval("IDADE: ", idade)
      Se (idade >= 18) entao
      Escreva("APTO A TIRAR CARTEIRA")
      Senao
      Escreval("VOCE NÂO ESTA APTO A TIRAR CARTEIRA")
      
      FimSe
       Escreva("----------------------------")
      


Fimalgoritmo
~~~
