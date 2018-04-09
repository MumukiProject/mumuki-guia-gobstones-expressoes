Suponhamos agora que queremos "copiar" as pedras verdes, fazendo com que haja a mesma quantidade de pedras vermelhas e pensemos em como poderia ser esse procedimento.

Uma tarefa que com certeza temos que fazer é colocar muitas pedras, e para isso já sabemos que existe o `ColocarN` que construímos em vários exercícios atrás. A cor das pedras que temos que colocar também já sabemos que é o vermelho.  Mas como sabemos quantas pedras colocar?

Observemos alguns exemplos:

* Se há 4 pedras verdes, deverá colocar 4 pedras vermelhas.
* Se há 2 pedras verdes, deverá colocar 2 pedras vermelhas.
* Se não há pedras verdes, não deverá colocar nenhuma vermelha.

O que está faltando para nós agora é uma forma de **contar quantas pedras verdes existem**, e para isso necessitamos outra função que nos dá Gobstones: `nroPedras(cor)`. O que faz é simples: nos informa quantas pedras de uma determinada cor existem **na posição atual**.

> Usando `nroPedras`, escreva o procedimento `CopiarVerdesEmVermelhas()`. 