# CSS Grid

**Data:** 28/09/2026  
**Tags:** #css

## O que aprendi

Aprendi que CSS Grid permite organizar elementos utilizando linhas e colunas.

Para ativar o Grid:

```css
#tecnologias ul {
    display: grid;
}
```

## Criando colunas

Usei:

```css
grid-template-columns: repeat(3, 1fr);
```

Isso cria três colunas do mesmo tamanho.

```text
[ coluna 1 ] [ coluna 2 ] [ coluna 3 ]
```

### repeat()

O `repeat()` evita repetir a mesma configuração várias vezes.

```css
repeat(3, 1fr)
```

significa:

```text
3   → quantidade de colunas
1fr → tamanho de cada coluna
```

Seria semelhante a escrever:

```css
grid-template-columns: 1fr 1fr 1fr;
```

## FR

`fr` significa uma fração do espaço disponível.

```css
grid-template-columns: 1fr 2fr 1fr;
```

Nesse exemplo:

```text
coluna 1 → 1 parte
coluna 2 → 2 partes
coluna 3 → 1 parte
```

Por isso a segunda coluna fica maior.

Também posso utilizar outras medidas:

```css
grid-template-columns: 200px 1fr 1fr;
```

ou:

```css
grid-template-columns: 25% 50% 25%;
```

## Gap

O `gap` cria espaço entre os itens do Grid.

```css
gap: 10px;
```

Também posso usar `gap` com Flexbox.

## Removendo marcadores

Como usei uma lista `<ul>`, removi os marcadores padrão com:

```css
list-style: none;
padding: 0;
```

## Fazendo um item ocupar mais colunas

Aprendi:

```css
grid-column: span 2;
```

O `span 2` faz um item ocupar o espaço de duas colunas.

Exemplo:

```css
#tecnologias li:last-child {
    grid-column: span 2;
}
```

Nesse caso:

```css
:last-child
```

seleciona o último item.

## Resumo

```text
display: grid         → ativa o Grid
grid-template-columns → define as colunas
repeat()              → repete uma configuração
fr                    → fração do espaço disponível
gap                   → espaço entre os itens
grid-column           → controla o espaço ocupado pelo item
span 2                → ocupa duas colunas
```
