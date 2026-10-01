# Aspect Ratio

**Data:** 01/10/2026  
**Tags:** #css #responsividade

## O que aprendi

Aprendi que `aspect-ratio` controla a proporção entre largura e altura de um elemento.

Usei na minha imagem de perfil:

```css
.foto-perfil {
  width: 300px;
  aspect-ratio: 1 / 1;
}
```

Nesse exemplo:

```css
aspect-ratio: 1 / 1;
```

mantém a largura e a altura na mesma proporção.

Isso cria um formato quadrado.

Como também uso:

```css
border-radius: 50%;
```

a imagem continua redonda.

Com `aspect-ratio`, não preciso definir manualmente:

```css
height: 300px;
```

Se eu mudar a largura, a altura é calculada automaticamente mantendo a proporção.

Outra proporção comum é:

```css
aspect-ratio: 16 / 9;
```

que é muito utilizada em vídeos.

## Resumo

`aspect-ratio` mantém a proporção entre largura e altura de um elemento.
