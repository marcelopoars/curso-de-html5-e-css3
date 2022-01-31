# Curso Html5 e Css3

> Por Marcelo Pereira

<br><br>

## Aula 11 - Introdução ao CSS

A partir desta aula iremos avançar nos estudos de HTML e CSS ao memos tempo. Isso por que HTML é muito mais interessante com CSS e você não pode aprender realmente CSS sem conhecer HTML.

<br><br>

### 1) O que é CSS?

CSS (Cascading Style Sheets) é um mecanismo para adicionar estilo (cores, fontes, espaçamento, etc.) a um documento web.

O CSS desenvolvido por um grupo dentro do **`W3C`** chamado **`CSS Working Group`**.

- representantes de fornecedores de navegadores web;
- outras empresas que tem interesse em CSS;
- outras pessoas, conhecidas como peritos convidados (invited experts).

<br><br>

### 2) Sintaxe CSS

CSS é uma linguagem baseada em regras. — Você define regras especificando grupos de estilo que devem ser aplicados para elementos particulares ou grupos de elementos na sua página web;

Exemplo:

```css
h1 {
  /* propriedade: valor */
  color: red;
  font-size: 36px;
}
```

<br><br>

### 3) Adicionando CSS para o nosso documento

Temos tr~es formas de adicionar CSS ao nosso documento html.

<br>

3.1) Adicionando rega inline:

```html
<h1 style="color: red;">Estudando CSS</h1>
```

<br>

3.2) Adicionando regra CSS entre as tags `<head>...</head>` e `<style>...</style>`:

```html
<head>
  <style>
    h1 {
      color: red;
    }
  </style>
</head>
```

<br>

3.3) Para ligar o style.css ao index.html adicione a seguinte linha em algum lugar dentro do `<head>` do documento HTML:

<br>

```html
<link rel="stylesheet" href="styles.css" />
```

Este elemento `<link>` diz ao navegador que temos uma **folha de estilo**, usando o atributo **rel**, e a localização desse arquivo como o valor do atributo href.

<br><br>

A regra é aberta com um selector . Isso seleciona o elemento HTML que vamos estilizar. Neste caso, estamos estilizando títulos de nível um (`<h1>`).

<br><br>

### 4) Múltiplos seletores

Você pode especificar múltiplos seletores, separando-os com virgula.

```css
h1,
p {
  color: red;
}
```

<br><br>

## Assista esta aula no Youtube

Você pode clicar no ícone segurando a tecla `"Ctrl"` do teclado para abrir o site Youtube em uma nova aba do seu navegador.

[![Youtube Badge](https://img.shields.io/badge/-Youtube-FF0000?style=flat-square&labelColor=FF0000&logo=youtube&logoColor=white&link=https://youtu.be/XwkhDt3YxqE)](https://youtu.be/XwkhDt3YxqE)

<br><hr>

## Me segue lá!

[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/marcelopoars)](https://twitter.com/marcelopoars)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/marcelopoars)](https://www.linkedin.com/in/marcelopoars)
