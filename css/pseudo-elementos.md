# Pseudo-elementos

**Data:** 30/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que pseudo-elementos permitem estilizar uma parte específica de um elemento.

Diferente das pseudo-classes, normalmente utilizam dois pontos duplos:

```css
::
```

Usei:

```css
::placeholder
```

para estilizar o texto de exemplo dos campos.

```css
input::placeholder,
textarea::placeholder {
    color: #777777;
    font-style: italic;
}
```

Nesse exemplo:

- `color` → muda a cor
- `font-style: italic` → deixa o texto em itálico

Também aprendi:

```css
::selection
```

Ele controla a aparência do texto quando seleciono uma parte da página com o mouse.

```css
::selection {
    background-color: rgb(37, 72, 168);
    color: white;
}
```

A diferença principal é:

```text
:hover
:focus
```

representam estados e são pseudo-classes.

Já:

```text
::placeholder
::selection
```

representam partes específicas e são pseudo-elementos.

## Resumo

Pseudo-elementos permitem estilizar partes específicas de um elemento, como o `::placeholder` e o texto selecionado com `::selection`.
