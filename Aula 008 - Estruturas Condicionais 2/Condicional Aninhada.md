## Condicional Aninhada

Uma estrutura condicional um pouco mais complexa:

~~~
SE eu tiver muito dinheiro ENTAO
    vou fazer uma viagem pra Disney
SENAO SE tiver uma graninha ENTAO
    vou visitar minha cidade natal 
SENAO
    vou ficar em casa
~~~
~~~
SE (situação 1) ENTAO
    Bloco A
SENAO
    SE (situação 2) ENTAO
        Bloco B
    SENAO
        Bloco C
    FIMSE
~~~

SE uma situação 1 ocorrer então ele executa o bloco A, SENAO, SE uma situação 2 ocorrer ENTAO executa o bloco B, SENAO, executa o bloco C.

Temos então duas estruturar condicionais, uma maior que esta externa e um outra situação condicional que esta dentro

![](../images/condicional%202.png)

Exemplo com codigo real:

~~~
Se (dinheiro >= 10000) entao
    Escreva ("Partiu Disney")
Senao
    Se (dinheiro >=5000) e (dinheiro < 1000) entao
        Escreva ("Visitar famímlia")
    Senao
    Escreva ("#chateado")
    FimSe
FimSe
~~~