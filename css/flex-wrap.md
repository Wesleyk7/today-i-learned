# Flex Wrap

**Data:** 29/09/2026  
**Tags:** #css #flexbox

## O que aprendi

Aprendi que `flex-wrap` permite que os itens de um Flexbox quebrem para outra linha quando não existe espaço suficiente.

No meu projeto eu tinha vários aprendizados dentro de um mesmo card.

```css
.aprendizados {
    display: flex;
    justify-content: center;
    gap: 10px;
    flex-wrap: wrap;
}
```

Sem:

```css
flex-wrap: wrap;
```

o Flexbox tenta manter todos os itens na mesma linha.

Isso fez o card aumentar demais de largura.

Com:

```css
flex-wrap: wrap;
```

os itens passam para a linha de baixo quando não existe espaço suficiente.

Por exemplo:

```text
HTML  CSS  JavaScript
Lógica de Programação  Python
MySQL  Git e GitHub
```

`wrap` pode ser entendido como "quebrar" ou "envolver".

## Resumo

`flex-wrap: wrap` permite que os itens de um Flexbox quebrem para novas linhas.
