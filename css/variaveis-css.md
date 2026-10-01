# Variáveis CSS

**Data:** 01/10/2026  
**Tags:** #css

## O que aprendi

Aprendi que posso guardar valores em variáveis no CSS e reutilizá-los em vários lugares.

As variáveis podem ser definidas dentro de:

```css
:root {
  --cor-principal: rgb(37, 72, 168);
  --cor-escura: #222222;
  --cor-texto: #333333;
}
```

Nesse exemplo:

- `:root` → representa a raiz da página
- `--cor-principal` → nome da variável
- `rgb(37, 72, 168)` → valor guardado

Para utilizar uma variável uso:

```css
var(--cor-principal)
```

Exemplo:

```css
h1 {
  color: var(--cor-principal);
}
```

A vantagem é que posso mudar o valor da variável uma única vez e todos os lugares que utilizam essa variável serão atualizados.

## Resumo

Variáveis CSS permitem guardar valores com nomes e reutilizá-los usando `var()`.
