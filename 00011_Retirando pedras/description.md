Continuando com isso de contar as pedras, agora é a sua vez de fazer um procedimento que sirva para retirar **todas** as pedras **de uma cor**.

Pensemos nas subtarefas necessárias:

1. Poder retirar muitas pedras: já está resolvido com `RetirarN`.
2. Contar quantas pedras deve retirar: podemos fazer com `nroPedras`.
3. Retirar todas as pedras de uma cor: deve combinar as 2 subtarefas anteriores.

> Codifique `RetirarTodas(cor)`, que receba uma cor e retira todas as pedras que há dessa cor (não deve fazer nada com o resta das cores).