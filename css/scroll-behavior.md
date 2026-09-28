# Scroll Behavior

**Data:** 28/09/2026  
**Tags:** #css

## O que aprendi

Aprendi a deixar a rolagem entre partes da página mais suave usando:

```css
html {
    scroll-behavior: smooth;
}
```

A propriedade:

```css
scroll-behavior
```

controla o comportamento da rolagem.

O valor:

```css
smooth
```

faz a página deslizar suavemente até o destino em vez de mudar de posição instantaneamente.

Por exemplo, posso ter um link:

```html
<a href="#topo" class="botao-fixo">Topo</a>
```

e um elemento com:

```html
<section id="topo">
```

Quando o link é clicado, a página volta para o elemento com `id="topo"`.

Com:

```css
scroll-behavior: smooth;
```

essa movimentação acontece suavemente.

## Resumo

`scroll-behavior: smooth` deixa a navegação por links internos mais suave.
