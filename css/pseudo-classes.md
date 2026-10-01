# Pseudo-classes

**Data:** 30/09/2026  
**Atualizado em:** 01/10/2026  
**Tags:** #css

## O que aprendi

Aprendi que pseudo-classes representam estados específicos de um elemento.

Algumas que utilizei foram:

```css
:hover
:focus
:valid
:invalid
:user-valid
:user-invalid
:not()
```

### Hover

`:hover` acontece quando o mouse passa sobre um elemento.

```css
button:hover {
  background-color: #222222;
}
```

Nesse exemplo, a cor do botão muda quando passo o mouse sobre ele.

### Focus

`:focus` acontece quando um elemento está selecionado ou em foco.

```css
input:focus {
  border-color: rgb(37, 72, 168);
}
```

Usei isso nos campos do formulário para mostrar uma borda diferente enquanto estou preenchendo.

### Valid e Invalid

Também aprendi:

```css
:valid
:invalid
```

`:valid` representa um campo com uma informação válida.

`:invalid` representa um campo com uma informação inválida.

Exemplo:

```css
input:invalid {
  border-color: red;
}

input:valid {
  border-color: green;
}
```

Um problema que percebi é que um campo com:

```html
required
```

pode ser considerado inválido assim que a página abre, mesmo antes de eu interagir com ele.

Por isso, a borda vermelha já aparecia antes de eu clicar no campo.

### User Valid e User Invalid

Depois aprendi:

```css
:user-valid
:user-invalid
```

Essas pseudo-classes levam em consideração a interação do usuário com o campo.

Exemplo:

```css
input:not(:focus):user-invalid,
textarea:not(:focus):user-invalid {
  border-color: red;
}

input:not(:focus):user-valid,
textarea:not(:focus):user-valid {
  border-color: green;
}
```

Nesse caso:

- `:user-invalid` → o usuário interagiu com o campo e ele ficou inválido
- `:user-valid` → o usuário interagiu com o campo e ele ficou válido

Isso evita mostrar a borda vermelha assim que a página é carregada.

A lógica ficou:

```text
Página abriu
→ campo normal

Campo em foco
→ borda azul

Saiu do campo com informação errada
→ borda vermelha

Saiu do campo com informação correta
→ borda verde
```

### Not

Também aprendi:

```css
:not()
```

`not` significa "não".

Exemplo:

```css
input:not(:focus)
```

significa:

> input que não está em foco.

Então:

```css
input:not(:focus):user-invalid
```

pode ser entendido como:

> input que não está em foco e ficou inválido depois da interação do usuário.

Essa lógica lembra uma condição utilizada em linguagens de programação:

```text
não está em foco
E
está inválido
```

## Resumo

Pseudo-classes permitem aplicar estilos de acordo com o estado de um elemento.

Aprendi:

- `:hover` → mouse sobre o elemento
- `:focus` → elemento em foco
- `:valid` → valor válido
- `:invalid` → valor inválido
- `:user-valid` → valor válido depois da interação do usuário
- `:user-invalid` → valor inválido depois da interação do usuário
- `:not()` → seleciona elementos que não atendem a uma condição

Usei essas pseudo-classes principalmente para criar interações e validações visuais no formulário.
