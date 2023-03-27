~~~
Algoritmo "NotaMelhorado"

Var
   N1, N2, M: Real


Inicio
   Escreva("Primeira nota: ")
   Leia(N1)
   Escreva("Segunda nota: ")
   Leia(N2)
   M <- (N1 + N2) / 2
   EscrevaL(" Media do aluno: ",M)

   Se(M >= 7) entao
      EscrevaL("Aluno aprovado")
   Senao
      Se(M >= 5) e (M < 7) entao
         EscrevaL("Aluno em recuperação")
      Senao
         EscrevaL("O Aluno foi reprovado")
      Fimse
   Fimse


Fimalgoritmo
~~~
