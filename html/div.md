# DIV no HTML

**Data:** 29/09/2026  
**Tags:** #html

## O que aprendi

Hoje aprendi sobre a tag `<div>`.

A `<div>` funciona como uma caixa ou um grupo genérico dentro do HTML.

Ela é utilizada quando quero agrupar vários elementos para depois organizar ou estilizar esse conjunto usando CSS.

Exemplo utilizado no meu portfólio:

```html
<div class="grid-projetos">

    <article class="projeto">
        <h3>BookShelf</h3>
        <p>Descrição do projeto.</p>
    </article>

    <article class="projeto">
        <h3>Today I Learned</h3>
        <p>Descrição do projeto.</p>
    </article>

</div>
```

Nesse caso, a `<div>` agrupa os dois projetos.

Mentalmente posso pensar assim:

```text
DIV
│
├── Projeto BookShelf
│
└── Projeto Today I Learned
```

## A DIV organiza os elementos sozinha?

Não.

A `<div>` apenas cria o grupo no HTML.

Quem controla como os elementos serão organizados visualmente é o CSS.

Por exemplo:

```css
.grid-projetos {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
}
```

Nesse caso:

```text
HTML
→ cria e agrupa os elementos

CSS
→ organiza os elementos visualmente
```

## DIV e semântica

A `<div>` é uma tag genérica.

Ela não informa ao navegador se aquele conteúdo é:

- um cabeçalho
- uma navegação
- uma seção
- um artigo
- um rodapé

Por isso, quando existe uma tag semântica adequada, é melhor utilizá-la.

Exemplos:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

Já a `<div>` é útil quando preciso apenas criar uma caixa ou grupo para organização e estilização.

## Exemplo do meu projeto

No meu portfólio utilizei:

```html
<div class="grid-projetos">
```

porque precisava de um elemento pai para organizar os cards de projetos utilizando CSS Grid.

## Resumo

```text
<div>
→ caixa genérica

Serve para:
→ agrupar elementos
→ facilitar a organização
→ aplicar estilos no conjunto

A DIV não organiza os elementos sozinha.
O CSS controla o layout.
```
