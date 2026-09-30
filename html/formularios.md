# Formulários

**Data:** 30/09/2026  
**Tags:** #html #formulario

## O que aprendi

Aprendi a criar um formulário utilizando a tag:

```html
<form>
```

Dentro dela posso adicionar campos para o usuário preencher.

Exemplo:

```html
<form>
    <label for="nome">Nome</label>
    <input type="text" id="nome">

    <label for="email">E-mail</label>
    <input type="email" id="email">

    <label for="mensagem">Mensagem</label>
    <textarea id="mensagem"></textarea>

    <button type="submit">Enviar</button>
</form>
```

Nesse exemplo:

- `<form>` → agrupa o formulário
- `<label>` → identifica o campo
- `<input>` → recebe uma informação
- `<textarea>` → recebe textos maiores
- `<button>` → cria o botão
- `type="submit"` → indica que o botão envia o formulário

Também aprendi que o `for` do `<label>` deve estar relacionado ao `id` do campo.

```html
<label for="nome">Nome</label>
<input id="nome">
```

Isso associa o texto "Nome" ao campo correspondente.

## Resumo

`<form>` agrupa os campos de um formulário e pode conter elementos como `label`, `input`, `textarea` e `button`.
