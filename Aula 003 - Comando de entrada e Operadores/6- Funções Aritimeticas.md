## Funções Aritimeticas

* Abs: Valor Absoluto
* Exp: Exponenciação
* Int: Valor inteiro
* RaizQ: Raíz Quadrada
* Pi: Retorna Pi
* Sen: Seno (rad)
* Con: Cosseno (rad)
* Tan: Tangente (rad)

![](../images/fun%C3%A7oes%20aritimeticas.png)

~~~
algoritmo "conversor"
var
   angulo, S: Real
inicio
      Escreva("Informe um ângulo: ")
      Leia(angulo)
      S <- Sen(GraupRad(angulo))
      Escreva("O seno de ", angulo, " e igual a ", S)   

fimalgoritmo
~~~