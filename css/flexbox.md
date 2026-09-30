# Flexbox

**Data:** 30/09/2026  
**Tags:** #css #flexbox

## O que aprendi

Aprendi que o Flexbox é uma forma de organizar elementos dentro de um elemento pai.

Para ativar o Flexbox uso:

```css
.container {
    display: flex;
}
```

Depois disso, os elementos filhos passam a ser itens flexíveis.

Por padrão, eles ficam organizados em linha.

```css
.container {
    display: flex;
    flex-direction: row;
}
```

Também posso organizar os elementos em coluna:

```css
.container {
    display: flex;
    flex-direction: column;
}
```

Algumas propriedades importantes são:

- `display: flex` → ativa o Flexbox
- `flex-direction` → define a direção dos itens
- `justify-content` → organiza os itens no eixo principal
- `align-items` → organiza os itens no eixo cruzado
- `gap` → cria espaço entre os itens

Exemplo:

```css
nav {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 20px;
}
```

Quando uso:

```css
flex-direction: row;
```

o eixo principal normalmente é horizontal.

Quando uso:

```css
flex-direction: column;
```

o eixo principal passa a ser vertical.

Também estudei outros recursos do Flexbox em arquivos separados:

- `flex-wrap.md`
- `align-self.md`
- `margin-top-auto.md`

## Resumo

Flexbox serve para organizar e alinhar elementos dentro de um elemento pai usando propriedades como `flex-direction`, `justify-content`, `align-items` e `gap`.
