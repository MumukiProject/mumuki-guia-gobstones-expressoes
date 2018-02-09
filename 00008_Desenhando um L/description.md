Nosso objetivo neste exercício será realizar um procedimento capaz de desenhar uma letra L com a cor Azul, mas com a possibilidade de escolher para onde será orientada. Em continuação, vemos alguns exemplos de como deveria se comportar:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Ele(Norte)</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Ele(Leste)</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 4 4
        cell 0 0 Azul 2
        cell 0 1 Azul 1
        cell 0 2 Azul 1
        cell 1 0 Azul 1
        cell 2 0 Azul 1
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 4 4
        cell 0 3 Azul 2
        cell 0 2 Azul 1
        cell 0 1 Azul 1
        cell 1 3 Azul 1
        cell 2 3 Azul 1
        head 0 3
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
 
Sem dúvida, um L consta de duas linhas e desenhar uma linha é a tarefa que você já resolveu no exercício anterior. Portanto, temos a metade do problema resolvido.

A primeira linha é fácil, porque coincide com a direção que recebemos por parâmetro… mas e a segunda? Bem, aí vem o interessante: além de `oposto`, Gobstones nos provê duas funções mais para operar sobre as direções, `seguinte` e `previo`.
<br>
`seguiente(direcao)` indica a direção seguinte à especificada, enquanto que `previo(direcao)` denota a anterior, sempre pensando no sentido das agulhas do relógio:
 
<img src="https://raw.githubusercontent.com/MumukiProject/mumuki-guia-gobstones-expressoes/master/images/rosa_vientos-01-pt_1518182346142.png" alt="rosa_vientos-01-pt_1518182346142.png" width=300>

> Descubra quais das novas funções você deve utilizar e implemente o procedimento `Ele(direcao)`. Não se preocupe com a posição inicial da garra, nós encontraremos o lugar correspondente para que a letra L possa ser desenhada.
