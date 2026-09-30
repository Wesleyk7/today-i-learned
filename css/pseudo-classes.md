# Pseudo-classes

**Data:** 30/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que pseudo-classes representam estados específicos de um elemento.

Algumas que utilizei foram:

```css
:hover
:focus
:valid
:invalid
```

`:hover` acontece quando o mouse passa sobre um elemento.

```css
button:hover {
    background-color: #222222;
}
```

`:focus` acontece quando um elemento está selecionado ou em foco.

```css
input:focus {
    border-color: rgb(37, 72, 168);
}
```

Também utilizei:

```css
:valid
```

para campos com informações válidas e:

```css
:invalid
```

para campos com informações inválidas.

Exemplo:

```css
input:not(:focus):invalid {
    border-color: red;
}

input:not(:focus):valid {
    border-color: green;
}
```

Também aprendi:

```css
:not(:focus)
```

que significa que o elemento NÃO está em foco.

A lógica lembra uma condição:

```text
:not(:focus):invalid
```

significa que o elemento não está em foco e está inválido.

## Resumo

Pseudo-classes permitem aplicar estilos de acordo com o estado de um elemento, como `:hover`, `:focus`, `:valid` e `:invalid`.
