Estrutura antiga:

~~~
ENQUANTO não arrumar o quarto faca
    castigo
FIMENQUANTO
liberado
~~~
Enquanto voce não arrumar o seu quarto você fica de castigo.
Esse enquanto vai se repetir e só vai sair quando o ARRUMAR O QUARTO for verdadeiro, ai ele vai pro comando LIBERADO que é o ultimo.

Usando essa mesma lógica usando o comando REPITA, o codigo ficaria dessa maneira:

~~~
REPITA 
    castigo
ATE arrumar o quarto
liberado
~~~
Ele repete CASTIGO, isso é, ele começa com castigo ate ARRUMAR O QUARTO. Quando chegar em arrumar o quarto o teste lógico é feito e caso ele não seja atendido ele volta para o REPITA. A partir do momento em que ele atingir a expressão ARRUMAR O QUARTO, ele vai sair e assim a execução continua para o LIBERADO.

![](/images/Captura%20de%20tela%20de%202023-01-05%2011-09-27.png)

Na primeira estrutura é preciso utilizar o operador lógico NÃO
Ja na segunda não é necessário

~~~
Algoritmo "SomadorNumerico"
var

  N, S: inteiro
  resp: Caractere
Inicio

   S <- 0
   Repita
      Escreva ("Digite o valor : ")
      Leia (N)
      S <- S + N
      Escreva("Voce quer continuar? [S/N] ")
      Leia(resp)

   Ate (resp = "N")
   Escreval("A soma de todos os valores foi ", S)
Fimalgoritmo
~~~