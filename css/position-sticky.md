# Position Sticky

**Data:** 28/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que `position: sticky` faz um elemento começar na posição normal da página e depois ficar preso quando atingir uma posição definida.

Exemplo:

```css
header {
    position: sticky;
    top: 0;
}
```

Nesse caso:

- `position: sticky` → permite que o elemento fique grudado durante a rolagem
- `top: 0` → faz ele grudar no topo da tela

Diferente do `fixed`, o elemento com `sticky` começa normalmente na página.

### Diferença

```text
fixed  → já fica preso na tela

sticky → começa normalmente e depois gruda
```

Também aprendi que o `sticky` respeita os limites do elemento pai.

Por isso, dependendo da estrutura do HTML, o efeito pode não funcionar como esperado.

## Resumo

`sticky` é útil para menus e cabeçalhos que devem continuar visíveis durante a rolagem.
