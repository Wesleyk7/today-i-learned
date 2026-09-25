# Position

**Data:** 25/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que a propriedade `position` controla como um elemento é posicionado na página.

Alguns valores são:

```css
position: static;
position: relative;
position: absolute;
position: fixed;
position: sticky;
```

### Static

`static` é o posicionamento padrão dos elementos.

```css
.elemento {
    position: static;
}
```

O elemento continua seguindo normalmente a ordem do HTML.

### Relative

`relative` permite movimentar o elemento em relação à posição original dele.

```css
.elemento {
    position: relative;
    left: 50px;
}
```

Nesse exemplo, o elemento se move 50px para a direita.

Também posso usar:

```css
top: 20px;
left: 20px;
right: 20px;
bottom: 20px;
```

### Absolute

`absolute` permite posicionar um elemento em um local específico.

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

Nesse caso, `.caixa` funciona como referência para o elemento `span`.

A combinação:

```css
position: relative;
```

no elemento pai e:

```css
position: absolute;
```

no elemento filho é muito utilizada para posicionar elementos dentro de caixas, imagens e cards.

### Direções

- `top` → distância do topo
- `right` → distância da direita
- `bottom` → distância da parte inferior
- `left` → distância da esquerda
