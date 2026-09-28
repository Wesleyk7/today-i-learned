# Position Fixed

**Data:** 28/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que `position: fixed` deixa um elemento preso em uma posição da tela.

Mesmo quando a página é rolada, o elemento continua no mesmo lugar.

```css
.botao-fixo {
    position: fixed;
    bottom: 20px;
    right: 50px;
}
```

Nesse exemplo:

- `position: fixed` → fixa o elemento na tela
- `bottom: 20px` → deixa 20px de distância da parte inferior
- `right: 50px` → deixa 50px de distância da direita

Usei isso para criar um botão que permanece no canto inferior direito da página.

Também posso usar:

```css
top: 20px;
left: 20px;
```

para controlar outras posições.

## Resumo

`fixed` mantém o elemento preso na tela, independentemente da rolagem da página.
