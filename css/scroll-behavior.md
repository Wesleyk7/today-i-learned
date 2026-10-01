# Scroll Behavior

**Data:** 28/09/2026  
**Atualizado em:** 01/10/2026  
**Tags:** #css #responsividade

## O que aprendi

Aprendi a controlar melhor a rolagem da página usando propriedades do CSS.

### Scroll Behavior

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

Quando o link é clicado, a página vai até o elemento que possui o `id="topo"`.

Com:

```css
scroll-behavior: smooth;
```

essa movimentação acontece suavemente.

### Scroll Margin Top

Também aprendi:

```css
scroll-margin-top
```

Essa propriedade cria um espaço no topo quando a página rola até um elemento através de um link interno.

Usei:

```css
section {
  scroll-margin-top: 90px;
}
```

Isso foi útil porque meu `header` utiliza:

```css
position: sticky;
top: 0;
```

Sem o `scroll-margin-top`, o menu pode ficar por cima do título da seção quando clico em um link interno.

Com:

```css
scroll-margin-top: 90px;
```

a rolagem para um pouco antes, deixando espaço para o `header`.

A diferença entre as duas propriedades é:

- `scroll-behavior` → controla **como** a página rola
- `scroll-margin-top` → ajuda a controlar **onde** a rolagem para

Exemplo usando as duas:

```css
html {
  scroll-behavior: smooth;
}

section {
  scroll-margin-top: 90px;
}
```

Nesse caso, a página rola suavemente e deixa espaço para o menu no topo.

## Resumo

`scroll-behavior: smooth` deixa a navegação entre links internos mais suave.

`scroll-margin-top` cria um espaço no topo quando a página rola até um elemento, evitando que um `header` fixo ou sticky fique por cima do conteúdo.
