Aula 10 - Semântica, Tags Header, Footer, Nav, Section, Main, div
Nesta aula vamos trabalhar com aa tags...


1) body
Representa o conteúdo de um documento HTML.

É permitido apenas um <body> por documento.
Exemplo:

<body>
  <!-- Conteúdo do meu documento -->
</body>

2) header (cabeçalho)
Representa um grupo de suporte introdutório ou navegacional.

Pode conter alguns elementos de cabeçalho como logo, título, navegação, campo de busca, etc.
Exemplo:

<header>
  <h1>Curso Html5 e Css3</h1>
</header>

3) footer (rodapé)
Representa um rodapé para a sua seção de conteúdo.

Normalmente um rodapé contém informações sobre o autor do documento;
Exemplo:

<footer>
  <p>Copyright © 2020. Desenvolvido com ♥ por Marcelo Pereira.</p>
</footer>

4) nav
Representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.

Nem todos os links de um documento devem estar dentro de um elemento <nav>, o qual é destinado apenas para grupos importantes de links de navegação;

Um documento pode ter vários elementos <nav>, por exemplo, um para navegação no site e outro para navegação dentro da página;

normalmente o elemento <footer> contém uma lista de links que não precisam estar em uma <nav>;

Exemplo:

<nav>
  <ul>
    <li><a href="#">Sobre nós</a></li>
    <li><a href="#">Serviços</a></li>
    <li><a href="#">Contato</a></li>
  </ul>
</nav>

5) section
Representa uma seção genérica contida em um documento HTML.

Cada <section> deve ser identificado, geralmente incluindo um elemento de cabeçalho <h1>, h2, ... <h6>;
Exemplo:

<section>
    <h1>Curso Html5 e Css3</h2>
    <p>Neste curso vamos aprender muita coisa juntos e desenvolver projetos bem legais.</p>
</section>

6) main
O elemento <main> define o conteúdo principal dentro do <body> em seu documento ou aplicação.

Deve ser único na página, ou seja, apenas um <main> por documento;

Dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).

Exemplo:

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

7) div
O elemento de divisão HTML <div> é um container genérico para conteúdo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id).

Exemplo:

<div>
  <p>Um conteúdo qualquer.....</p>
</div>