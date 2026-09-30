# Position Absolute

**Data:** 25/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que:

```css
position: absolute;
```

permite posicionar um elemento em um local específico.

É comum utilizar um elemento pai com:

```css
position: relative;
```

e o elemento filho com:

```css
position: absolute;
```

Exemplo:

```css
.caixa {
    position: relative;
}

.caixa span {
    position: absolute;
    top: 10px;
    right: 10px;
}
```

Nesse caso, `.caixa` funciona como referência para posicionar o `span`.

Essa combinação é muito utilizada em caixas, imagens e cards.

## Resumo

`absolute` permite posicionar um elemento de forma específica e pode usar um elemento pai com `position: relative` como referência.
