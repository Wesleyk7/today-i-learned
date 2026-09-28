# Z-index

**Data:** 28/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que `z-index` controla a ordem das camadas quando elementos ficam sobrepostos.

Exemplo:

```css
header {
    position: sticky;
    top: 0;
    z-index: 100;
}
```

O valor do `z-index` não representa pixels ou distância.

Ele representa a prioridade da camada.

Exemplo:

```text
z-index: 1
z-index: 10
z-index: 100
```

Quando os elementos podem se sobrepor, aquele com um `z-index` maior pode aparecer na frente.

Usei:

```css
z-index: 100;
```

no cabeçalho para evitar que o conteúdo da página passe visualmente por cima dele durante a rolagem.

## Resumo

`z-index` controla qual elemento aparece na frente ou atrás quando existe sobreposição.
