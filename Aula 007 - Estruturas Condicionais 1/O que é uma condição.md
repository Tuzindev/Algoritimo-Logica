## O que é uma condição?

Usando uma frase de exemplo:

**Se** eu tiver dinheiro **então** <br>
vou fazer uma viagem pra disney
<br>
<br>
Existe 3 delimitações: O comando, a expressão e a ação.
<br>

### Condicional simples


~~~
Se **(expressão)** entao 
    Bloco 
Fimse
~~~

**Se** uma expressão for verdadeira então executo um bloco.

~~~
Se (dinheiro >= 10000) entao
    Escreva ("Partiu Disney")
FimSe
~~~

O nome dessa estrutura, onde existe um bloco sendo executado caso uma expressão seja verdadeira, se chama **Condicional Simples.** 
<br>

### Condicional composta

Condicional com **Senão:**

~~~ 
Se (expressão) entao
    Bloco A
senao
    Bloco B
FimSe
~~~

**SE** uma expressão ocorrer **ENTAO** executa o bloco A, **SENAO** executa o bloco B.

~~~
Se (dinheiro >= 10000) entao
    Escreva ("Partiu Disney")
Senao
    Escreva ("#chateado")
FimSe
~~~