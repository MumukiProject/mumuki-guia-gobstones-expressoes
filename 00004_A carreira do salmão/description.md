Bom, chega de números (por um momento). Agora vamos aprender a fazer "contas" com as direções.

Para fazer isso, simularemos o movimento de um salmão contra a correnteza. Nosso objetivo será escrever um procedimento `MoverComoSalmao(direcao)` que receba uma direção e se mova exatamente uma vez na direção **oposta**. Vejamos em um quadro como deveria se comportar este procedimento:

* `MoverComoSalmao(Norte)` <i class="fa fa-arrow-right"></i> se move em direção ao **Sul**.
* `MoverComoSalmao(Leste)` <i class="fa fa-arrow-right"></i> se move em direção ao **Oeste**.
* `MoverComoSalmon(Sul)` <i class="fa fa-arrow-right"></i> se move em direção ao **Norte**.
* `MoverComoSalmon(Oeste)` <i class="fa fa-arrow-right"></i> se move em direção ao **Leste**.

Como a direção vai ser um parâmetro do nosso procedimento, necessitamos uma forma de dizer _"a direção oposta a X"_ para poder em seguida usar isso como argumento de `Mover`. Gobstones nos provê um mecanismo para fazer isso, a função `oposto(dir)`, que nos diz exatamente isso: a direção contrária à dir que nós te passamos.

Sabendo disso, poderíamos implementar facilmente o procedimento que queremos:

``` gobstones
procedure MoverComoSalmao(direcao) {
  Mover(oposto(direcao))
}

```

> Escreva a solução no editor e clique em Enviar. Você vai ver como a garra se move...
