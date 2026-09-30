# Margin Top Auto 

**Data:** 29/09/2026  
**Tags:** #css #flexbox

## O que aprendi

Aprendi que `margin-top: auto` pode usar o espaço disponível acima de um elemento para empurrá-lo para baixo.

No meu projeto os cards foram organizados utilizando Flexbox em coluna.

```css
.projeto {
    display: flex;
    flex-direction: column;
}
```

Depois utilizei:

```css
.link-projeto {
    margin-top: auto;
}
```

Isso empurrou o link para a parte inferior do card.

Foi útil porque as descrições dos projetos possuem tamanhos diferentes.

Mesmo assim, os botões conseguem permanecer alinhados na parte inferior.

Também utilizei:

```css
.link-projeto {
    margin-top: auto;
    align-self: center;
}
```

Nesse exemplo:

- `margin-top: auto` → empurra o link para baixo
- `align-self: center` → centraliza o link

## Resumo

`margin-top: auto` pode usar o espaço disponível acima do elemento para empurrá-lo para a parte inferior de um Flexbox em coluna.
