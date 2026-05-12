````md
# Exercício — Praticando `position` em CSS

## Objetivo

Criar uma página responsiva utilizando os principais tipos de `position` do CSS:

- `static`
- `relative`
- `absolute`
- `fixed`
- `sticky`

O exercício tem como foco compreender:

- fluxo normal da página;
- posicionamento de elementos;
- sobreposição;
- comportamento durante a rolagem;
- responsividade.

---

# Cenário

Você foi contratado para desenvolver a interface inicial de uma loja virtual.

A página deve possuir:

- um cabeçalho que acompanha a rolagem;
- um card de produto com badge promocional;
- um botão flutuante de ajuda;
- um menu lateral que permanece visível durante a rolagem;
- exemplos práticos de posicionamento usando todos os tipos de `position`.

---

# Parte 1 — Estrutura da Página

Crie a estrutura HTML da página contendo:

## Header

Um cabeçalho com o nome da loja.

---

## Main

Dentro do `<main>`, crie:

### Menu lateral (`aside`)

O menu deve conter links fictícios de categorias.

Exemplo:

- Eletrônicos
- Roupas
- Promoções
- Contato

---

### Área principal (`section`)

A área principal deve conter:

- um card de produto;
- imagem do produto;
- título;
- descrição;
- botão de compra;
- conteúdo suficiente para gerar rolagem da página.

---

## Botão flutuante

Crie um botão de ajuda/chat no canto da tela.

---

# Parte 2 — `position: static`

## Tarefa

Crie um parágrafo utilizando:

```css
position: static;
````

Depois tente aplicar:

```css
top: 20px;
left: 20px;
```

---

## Objetivo

Observar que:

* o elemento continua no fluxo normal;
* `top` e `left` não funcionam com `static`.

---

# Parte 3 — `position: relative`

## Tarefa

No card do produto:

1. aplique:

```css
position: relative;
```

2. mova o card utilizando:

```css
top: 10px;
left: 15px;
```

---

## Objetivo

Demonstrar que:

* o elemento continua ocupando espaço;
* apenas sua posição visual muda.

---

# Parte 4 — `position: absolute`

## Tarefa

Crie uma badge promocional escrito:

```text
Novo
```

A badge deve:

* ficar no canto superior direito do card;
* aparecer sobre a imagem do produto.

---

## Regras

Utilize:

```css
position: absolute;
```

e faça o card usar:

```css
position: relative;
```

---

## Objetivo

Praticar:

* remoção do fluxo normal;
* posicionamento relativo ao elemento pai;
* sobreposição de elementos.

---

# Parte 5 — `position: fixed`

## Tarefa

Transforme o botão de ajuda em um botão flutuante fixo.

---

## Resultado esperado

O botão deve:

* permanecer visível durante a rolagem;
* ficar no canto inferior direito da tela.

---

## Utilize

```css
position: fixed;
bottom: 20px;
right: 20px;
```

---

# Parte 6 — `position: sticky`

## Tarefa

Faça o menu lateral permanecer visível durante a rolagem da página.

---

## Regras

Utilize:

```css
position: sticky;
top: 0;
```

---

## Objetivo

Demonstrar o comportamento híbrido entre:

* `relative`
* `fixed`

---

# Parte 7 — Header Fixo ou Sticky

## Tarefa

Crie um cabeçalho que acompanhe a rolagem utilizando:

### Opção 1

```css
position: fixed;
```

### ou

### Opção 2

```css
position: sticky;
```

---

## Requisitos

O cabeçalho deve:

* ocupar toda largura da tela;
* permanecer acima do conteúdo;
* não esconder os elementos da página.



---

## Objetivo

Garantir que:

* o header fique acima do conteúdo;
* a badge não cubra o menu;
* o botão flutuante fique visível corretamente.

```
```
