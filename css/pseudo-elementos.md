# Pseudo-elementos

**Data:** 30/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que pseudo-elementos permitem estilizar uma parte específica de um elemento ou criar conteúdo visual usando CSS.

Diferente das pseudo-classes, os pseudo-elementos normalmente utilizam dois pontos duplos:

```css
::
```

Alguns pseudo-elementos que aprendi foram:

```css
::placeholder
::selection
::before
::after
```

### Placeholder

Usei:

```css
::placeholder
```

para estilizar o texto de exemplo que aparece dentro dos campos de formulário.

```css
input::placeholder,
textarea::placeholder {
  color: #777777;
  font-style: italic;
}
```

Nesse exemplo:

- `color` → muda a cor do texto
- `font-style: italic` → deixa o texto em itálico

O `placeholder` continua desaparecendo quando começo a digitar no campo.

### Selection

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

Nesse exemplo:

- `background-color` → muda a cor de fundo da seleção
- `color` → muda a cor do texto selecionado

### Before

O:

```css
::before
```

permite criar conteúdo antes do conteúdo original de um elemento.

Exemplo:

```css
#projetos h2::before {
  content: "💻 ";
}
```

Nesse caso:

- `::before` → cria algo antes do conteúdo
- `content` → define o conteúdo que será exibido

O resultado fica parecido com:

```text
💻 Meus Projetos
```

O emoji não precisa estar escrito diretamente no HTML.

### After

O:

```css
::after
```

permite criar conteúdo depois do conteúdo original.

Exemplo:

```css
#projetos h2::after {
  content: "✓";
}
```

O resultado ficaria parecido com:

```text
Meus Projetos ✓
```

Também testei o `::after` para criar uma linha decorativa abaixo do título.

Nesse caso, utilizei:

```css
#projetos h2::after {
  content: "";
  display: block;
  width: 60px;
  height: 4px;
  background-color: rgb(37, 72, 168);
}
```

Mesmo com:

```css
content: "";
```

o pseudo-elemento pode existir e ser estilizado pelo CSS.

Usei esse exemplo para entender o funcionamento do `::after`, mas depois removi a linha porque não gostei dela visualmente no meu projeto.

## Pseudo-classe x Pseudo-elemento

Aprendi também a diferença entre os dois.

Pseudo-classes representam estados de um elemento:

```css
:hover
:focus
:valid
:invalid
```

Pseudo-elementos representam partes específicas ou conteúdo criado pelo CSS:

```css
::placeholder
::selection
::before
::after
```

De forma simples:

```text
:  → estado do elemento

:: → parte ou conteúdo do elemento
```

## Resumo

Pseudo-elementos permitem estilizar partes específicas ou criar conteúdo visual usando CSS.

Aprendi:

- `::placeholder` → estiliza o texto de exemplo dos campos
- `::selection` → estiliza o texto selecionado
- `::before` → cria conteúdo antes
- `::after` → cria conteúdo depois
- `content` → define o conteúdo criado por `::before` e `::after`

Também aprendi que pseudo-classes representam estados, enquanto pseudo-elementos trabalham com partes ou conteúdos específicos.
