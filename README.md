# Estruturas e Tags Básicas do HTML5

O HTML5 é a nova versão padrão do HTML com novas Tags e APIs capazes de inserir facilmente um arquivo de audio ou vídeo em um site. Basicamente o HTML seria o esqueleto do seu site, que deverá ser formatado (ou vestido) utilizando a linguagem CSS (Cascading Style Sheet).

## Estrutura Básica

A estrutura básica do HTML5 é parecida as estrutra do XHTML e do HTML 4, contendo elementos HEAD e BODY.
```
<!DOCTYPE html>
<html lang="pt-br">
<head>

</head>
<body>

</body>
</html>
```

### Meta Tags

As metas ajudam o seu site a descrever seu conteúdo aos buscadores, como o Google. Aqui você poderá dizer qual a codificação (charset), descrição e até palavras-chaves referentes a sua página. 

Essas são importantes justamente por identificar o site aos buscadores, ajudando no SEO (Search Engine Optimization). O Google não utiliza somente as metas para realizar suas buscas, mas elas são uma parte importante.

Abaixo lista tas metas mais importantes:

- **description**: guarda a descrição do site, utilizado nos motores de busca. 
- **keywords**: palavras chaves relacionadas ao site, utilizada nos primórdios pelos motores de busca.
- **author**: idenfitica o autor do site
- **robots**: ajuda os robos dos motores de busca a indexar ou não um site. Com esta opção podemos dizer se uma determinada página do site não deve ser mostrada nos resultados de uma busca.

Exemplo de utilização:

```
<head>
  <title>Página do Burnes - Home</title>
  <meta charset="utf-8">
  <meta name="description" content="Página do Burnes sobre HTML e CSS">
  <meta name="keywords" content="html, css, js, site">
  <meta name="robots" content="index">
</head>
```

## Tags HTML e seus Significados

- **DOCTYPE:** define o tipo de documento
- **html:** define o início do documento html, todos as demais tags devem estar dentro desta tag
- **head:** cabeçalho onde ficar os metadados do documento, como metatgs, css e javascript
- **title:** define o título do documento, mostrado na barra de títulos do navegador e como link nos mecanismos de busca
- **base:** define a url base do documento
- **link:** utilizado para linkar um arquivo de imagem ou css a página html
- **script:** utilizado para escrever ou anexar um arquivo normalmente javascript a página
- **meta:** metatags, como charset, description, viewport ou keywords
- **style:** utilizada para adicionar um código css a página
- **body:** corpo ou área principal do documento, dentro deste deve ficar o conteúdo da sua página
- **header:** define um cabeçalho da página ou de uma seção, normalmente pode conter um menu (nav), um logo ou link
- **nav:**  define uma área de navegação contendo links, para a formação de menus com hiperlinks
- **footer:** define o rodapé de uma página ou seção
- **main:** define o conteúdo principal da página, deve ser utilizado apenas uma única vez em cada página
- **section:** define uma seção do documento
- **article:** pode ser um post ou notícia de um fórum ou blog, define um conteúdo independente
- **h1 a h6:** representam 6 níveis de títulos, sendo o h1 de maior importância
- **p:** define um parágrafo
- **br:** define uma quebra de linha
- **div:** define uma camada sem formatação, genérico
- **ul:** define uma lista não ordenada
- **li:** define um elemento ou item da lista não ordenada
- **a:** define um link que deve ser apontado com o atributo *href*
- **img:** define a utilização de uma imagem (JPG, GIF, PNG e outras). A imagem deve ser apontada com o uso do atributo *src*
- **strong:** apesar de deixar em negrito, representa a importância deste texto no meio da frase

### Exemplo de Utilização

```
<body>
  <header>
    <h1>Página do Tenório</h1>
  </header>
  <nav>
    <a href="index.html" title="Home">Home</a>
  </nav>
  <main>
    <h1>Olá! Bem vindo a minha Pagina!</h1>
  </main>
  <footer>
    <p>Desenvolvido por Tenório</p>
  </footer>
</body>

```

Para conhecer mais elementos HTML5, confira a lista no link [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5/HTML5_element_list "HTML Element List")