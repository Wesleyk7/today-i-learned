# Semântica de Header e Nav

**Data:** 28/09/2026  
**Tags:** #html #semantica

## O que aprendi

Aprendi que `<header>` e `<nav>` possuem funções semânticas diferentes.

### Header

A tag:

```html
<header>
```

representa um cabeçalho ou uma área introdutória.

Ela pode conter elementos como:

```html
<h1>Título</h1>
<p>Apresentação</p>
```

Também pode conter uma área de navegação.

### Nav

A tag:

```html
<nav>
```

representa uma área de navegação com links importantes da página.

Exemplo:

```html
<nav>
    <a href="#sobre">Sobre mim</a>
    <a href="#tecnologias">Tecnologias</a>
    <a href="#objetivos">Objetivos</a>
</nav>
```

Aprendi que `<nav>` não precisa obrigatoriamente ficar dentro de `<header>`.

As duas estruturas podem ser utilizadas:

```html
<header>
    <nav>
        ...
    </nav>
</header>
```

ou:

```html
<header>
    ...
</header>

<nav>
    ...
</nav>
```

A escolha depende da organização e da função dos elementos na página.

## Resumo

```text
<header> → cabeçalho ou introdução
<nav>    → área de navegação
<a>      → cria o link
```
