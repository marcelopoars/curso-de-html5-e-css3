# Curso Html5 e Css3

> Por Marcelo Pereira

<br>

## Aula 10 - Semântica, Tags Header, Footer, Nav, Section, Main, div

Nesta aula vamos trabalhar com aa tags...

<br>

### 1) body

Representa o conteúdo de um documento HTML.

- É permitido apenas um `<body>` por documento.

Exemplo:

```html
<body>
  <!-- Conteúdo do meu documento -->
</body>
```

<br>

### 2) header (cabeçalho)

Representa um grupo de suporte introdutório ou navegacional.

- Pode conter alguns elementos de cabeçalho como logo, título, navegação, campo de busca, etc.

Exemplo:

```html
<header>
  <h1>Curso Html5 e Css3</h1>
</header>
```

<br>

### 3) footer (rodapé)

Representa um rodapé para a sua seção de conteúdo.

- Normalmente um rodapé contém informações sobre o autor do documento;

Exemplo:

```html
<footer>
  <p>Copyright © 2020. Desenvolvido com ♥ por Marcelo Pereira.</p>
</footer>
```

<br>

### 4) nav

Representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.

- Nem todos os links de um documento devem estar dentro de um elemento `<nav>`, o qual é destinado apenas para `grupos importantes de links` de navegação;

- Um documento pode ter vários elementos `<nav>`, por exemplo, um para navegação no site e outro para navegação dentro da página;

- normalmente o elemento `<footer>` contém uma lista de links que não precisam estar em uma `<nav>`;

Exemplo:

```html
<nav>
  <ul>
    <li><a href="#">Sobre nós</a></li>
    <li><a href="#">Serviços</a></li>
    <li><a href="#">Contato</a></li>
  </ul>
</nav>
```

<br>

### 5) section

Representa uma seção genérica contida em um documento HTML.

- Cada `<section>` deve ser identificado, geralmente incluindo um elemento de cabeçalho `<h1>`, `h2`, ... `<h6>`;

Exemplo:

```html
<section>
    <h1>Curso Html5 e Css3</h2>
    <p>Neste curso vamos aprender muita coisa juntos e desenvolver projetos bem legais.</p>
</section>
```

<br>

### 6) main

O elemento `<main>` define o conteúdo principal dentro do `<body>` em seu documento ou aplicação.

- Deve ser único na página, ou seja, apenas um `<main>` por documento;

- Dentro do elemento `<main>` não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como `mecanismos de navegação`, `informações de copyright`, `logotipo` e `campos de busca` (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).

Exemplo:

```html
<main>
  <h1>Curso Html5 e Css3</h1>
  <p>
    Neste curso vamos aprender muita coisa juntos e desenvolver projetos bem
    legais.
  </p>

  <section>
    <h2>Sobre o Html5</h2>
    <p>Lunguagem utilizada para marcar os nossos documentos html.</p>
  </section>

  <section>
    <h2>Sobre o Css3</h2>
    <p>Linguagem utilizada para estilizar os nossos documentos html.</p>
  </section>
</main>
```

<br>

### 7) div

O elemento de divisão HTML `<div>` é um container genérico para conteúdo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando `class` ou `id`).

Exemplo:

```html
<div>
  <p>Um conteúdo qualquer.....</p>
</div>
```

<br><br>

## Assista esta aula no Youtube

Você pode clicar no ícone segurando a tecla `"Ctrl"` do teclado para abrir o site Youtube em uma nova aba do seu navegador.

[![Youtube Badge](https://img.shields.io/badge/-Youtube-FF0000?style=flat-square&labelColor=FF0000&logo=youtube&logoColor=white&link=https://youtu.be/NdAjp7X2CUI)](https://youtu.be/NdAjp7X2CUI)

<br><hr>

## Me segue lá!

[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/marcelopoars)](https://twitter.com/marcelopoars)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/marcelopoars)](https://www.linkedin.com/in/marcelopoars)
