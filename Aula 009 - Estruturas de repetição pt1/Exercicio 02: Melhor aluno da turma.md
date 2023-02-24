~~~
Algoritmo "MelhorALuno"

Var
   Quantidade, Contador: Inteiro
   Nota, MelhorN: Real
   Aluno, MelhorA: Caractere


Inicio

   Escreva("Quantos alunos a turma tem? ")
   Leia(Quantidade)
   Contador <- 1

   Enquanto (Contador <= Quantidade) faca
      EscrevaL("---------------")

      Escreva(" NOME DO ALUNO",Contador,": ")
      Leia(Aluno)

      Escreva(" NOTA DE ", Aluno,": ")
      Leia(Nota)

      Contador <- Contador +1

      Se (Nota > MelhorN) entao

         MelhorA <- Aluno
         MelhorN <- Nota

      FimSe

   FimEnquanto

   EscrevaL ("------------------")

   Escreval (" O ALUNO COM MELHOR DESEMPENHO FOI: ")

   EscrevaL  (">>> ", MelhorA , " com nota  : " , MelhorN)

Fimalgoritmo
~~~