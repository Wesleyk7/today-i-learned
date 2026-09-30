# Estilização de Formulário

**Data:** 30/09/2026  
**Tags:** #css #formulario

## O que aprendi

Aprendi a organizar os campos de um formulário utilizando Flexbox.

```css
form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 600px;
    margin: 0 auto;
}
```

Nesse exemplo:

- `display: flex` → ativa o Flexbox
- `flex-direction: column` → organiza os campos um embaixo do outro
- `gap` → cria espaço entre os elementos
- `max-width` → limita a largura máxima
- `margin: 0 auto` → centraliza o formulário

Também estilizei os campos:

```css
input,
textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}
```

E permiti que o campo de mensagem seja redimensionado apenas verticalmente:

```css
textarea {
    resize: vertical;
}
```

`resize` significa redimensionar.

`vertical` significa que o tamanho pode ser alterado para cima ou para baixo.

## Resumo

Usei Flexbox para organizar o formulário e CSS para controlar largura, espaçamento, bordas e aparência dos campos.
