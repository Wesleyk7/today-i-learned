# Atributos de Formulário

**Data:** 30/09/2026  
**Tags:** #html #formulario

## O que aprendi

Aprendi alguns atributos importantes usados nos campos de um formulário.

Exemplo:

```html
<input
    type="email"
    id="email"
    name="email"
    placeholder="Digite seu e-mail"
    autocomplete="email"
    required
>
```

Nesse exemplo:

- `type` → define o tipo do campo
- `id` → identifica o elemento
- `name` → identifica o dado quando o formulário é enviado
- `placeholder` → mostra um texto de exemplo dentro do campo
- `autocomplete` → permite preenchimento automático
- `required` → torna o campo obrigatório

Também utilizei:

```html
<textarea
    id="mensagem"
    name="mensagem"
    rows="5"
    maxlength="500"
    required
></textarea>
```

Nesse caso:

- `rows="5"` → define uma altura inicial de aproximadamente 5 linhas
- `maxlength="500"` → permite no máximo 500 caracteres

Também aprendi que:

```html
type="text"
```

é usado para texto comum.

Já:

```html
type="email"
```

faz o navegador verificar se o valor possui formato de e-mail.

## Resumo

Os atributos ajudam a definir como os campos funcionam, quais informações recebem e quais regras precisam seguir.
