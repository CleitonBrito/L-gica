# Puzzle 01

<img src="https://github.com/CleitonBrito/Logica/blob/master/Puzze_01/puzzle01.jfif" width="50%">

----

Para este exemplo, iremos utilizar icógnicas para representar os seguintes itens (na imagem) acima:

Icógnitas | Itens
----------|--------------
Z         | Par de Tênis
X         | Homem
Y         | Par de Gravatas

----

Quanto vale o par de tênis?

````
Z + Z + Z = 30
3Z = 30
Z = 30 / 3
Z = 10

Agora sabemos que o par de tênis equivale a 10.

Isso significa que: 
Z / 2 = ?
10 / 2 = 5

Um tênis equivale a 5.
````
----

E qual o valor do homem?

````
X + X + Z = 20
2X + 10 = 20
2X = 20 - 10
2X = 10
X = 10 / 2
X = 5

Encontramos o valor! O homem equivale a 5.
````

----

E as gravatas? Quanto custa o par?

````
Y + Y + X = 13
Y + Y + 5 = 13
2Y + 5 = 13
2Y = 13 - 5
2Y = 8
Y = 8 / 2
Y = 4

Opa! O par de gravatas equivale a 5.

Isso quer dizer que:
Y / 2 = ?
4 / 2 = 2

Uma gravata equivale a 2.
````

----
## Finalizando o cálculo ##

Para finalizar, temos:

Um tênis; ___mais___ um Homem com um par de gravatas nas mãos, e calçado um par de tênis;  ___multiplicando___ por uma gravata

Convertendo para nossas icógnitas, temos:

````
(par de tênis / 2) + (homem + par de gratavas + par de tênis) * (par de gravatas / 2)

ou seja

(Z / 2) + (X + Y + Z) * (Y / 2)
````

Alterando pelos valores ficaria:

````
(10 / 2) + (5 + 4 + 10) * (4 / 2)

  5      +      19      *    2
  
Respeitando a ordem de precedência da Matemática, resolve-se primeiro a multiplicação e depois a soma:

5 + 19 * 2
5 + 38
43

Resultado: 43
````
