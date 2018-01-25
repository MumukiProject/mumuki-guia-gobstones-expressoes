Combinando as três funções de direções que vimos até agora, execute o procedimento `Seta(direcao)` que desenhe uma seta vermelha na direção correspondente. A garra começa e deve ficar sempre no centro, como se vê nas imagens.

Exemplos de uso:

|Flecha(Norte)|Flecha(Oeste)|
|:--------:|:-------:|
|<gs-board>
  GBB/1.0
    size 3 3
    cell 1 2 Rojo 1
    cell 0 1 Rojo 1
    cell 2 1 Rojo 1
    head 1 1
</gs-board>|
<gs-board>
  GBB/1.0
    size 3 3
    cell 1 2 Rojo 1
    cell 0 1 Rojo 1
    cell 1 0 Rojo 1
    head 1 1
</gs-board>|