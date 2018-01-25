Agora que você já sabe usar a função `oposto`, podemos finalmente resolver o problema de construir um procedimento que desenhe uma linha **em qualquer direção** e **deixe a garra na posição inicial**.

A versão que sabíamos fazer até agora era esta:

``` gobstones
procedure Linha(direcao, cor, comprimento) {
  repeat(comprimento) {
    Colocar(cor)
    Mover(direcao)
  }
}

```

> Baseado nos seus novos conhecimentos sobre expressões, modifique o procedimento `Linha` para que a garra fique no lugar onde começou.