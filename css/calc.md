# Calc

**Data:** 01/10/2026  
**Tags:** #css

## O que aprendi

Aprendi que `calc()` permite fazer cálculos dentro do CSS.

Exemplo:

```css
main {
  width: calc(100% - 40px);
}
```

Nesse caso, o navegador utiliza 100% da largura disponível e retira 40px.

Posso misturar unidades diferentes dentro do cálculo.

```css
calc(100% - 40px)
```

Nesse exemplo:

- `100%` → valor relativo
- `40px` → valor fixo
- `calc()` → realiza o cálculo

Também é importante deixar espaços ao utilizar `+` ou `-`.

```css
calc(100% - 40px);
```

## Resumo

`calc()` permite que o navegador faça cálculos para determinar valores no CSS.
