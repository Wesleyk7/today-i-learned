# Clamp

**Data:** 01/10/2026  
**Tags:** #css #responsividade

## O que aprendi

Aprendi que `clamp()` permite criar um valor responsivo com limite mínimo e máximo.

A estrutura é:

```css
clamp(minimo, ideal, maximo)
```

Usei:

```css
font-size: clamp(28px, 5vw, 48px);
```

Nesse exemplo:

- `28px` → menor tamanho permitido
- `5vw` → tamanho que acompanha a largura da tela
- `48px` → maior tamanho permitido

Assim, o tamanho pode aumentar ou diminuir conforme a tela, mas nunca ultrapassa os limites definidos.

A diferença para `calc()` é:

- `calc()` → realiza um cálculo
- `clamp()` → controla um valor entre mínimo e máximo

## Resumo

`clamp()` cria valores responsivos respeitando um valor mínimo, um valor ideal e um valor máximo.
