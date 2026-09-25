# Transition e Transform

**Data:** 25/09/2026  
**Tags:** #css

## O que aprendi

Aprendi a usar `transition` para deixar mudanças de estilo mais suaves.

```css
nav a {
    color: white;
    transition: color 0.3s ease;
}

nav a:hover {
    color: yellow;
}
```

O `0.3s` controla quanto tempo a transição demora.

Também aprendi a usar `transform` para movimentar elementos.

```css
nav a:hover {
    color: yellow;
    transform: translateY(-2px);
}
```

O `translateY()` movimenta o elemento no eixo vertical.

- Valor negativo → sobe
- Valor positivo → desce

Também é possível aplicar transição ao movimento:

```css
nav a {
    transition:
        color 0.3s ease,
        transform 0.3s ease;
}
```

Assim, a mudança de cor e o movimento acontecem de forma suave.
