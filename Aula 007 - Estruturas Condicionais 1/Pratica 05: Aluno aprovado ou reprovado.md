~~~ 
 
 Algoritmo "AprovadoOuReprovado"


Var

    n1, n2, Media: real

Inicio
      EscrevaL("----------------------------")
      EscrevaL("ESCOLA DEV")
      Escreva("----------------------------")
      


      Escreva("Primeira nota: ")
      Leia(n1)
      Escreva("Segunda nota: ")
      Leia(n2)
      


      
      Escreva("---------")
      Escreva("STATUS")
      Escreval("---------")
      
      Media <- ((n1 + n2)/ 2)

      Escreval("MEDIA: ", Media:3:1)

      Se (Media >= 6) entao
      Escreval("ALUNO APROVADO")
      Senao
      Escreval("ALUNO REPROVADO")

      fimse
      

      

       Escreva("----------------------------")
      


Fimalgoritmo
~~~