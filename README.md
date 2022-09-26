# nlw-sports-explorer

PREVIEW
Projeto construído no evento Next Level Week da Rocketseat.

## OBJETIVO

Criar uma página onde se possa ver os seus jogos e streamers favoritos, além de poder compartilhar suas redes sociais.

## TECNOLOGIAS

- HTML
- CSS
- Git e GitHub

## CRONOGRAMA

- Dia 01 - Base Building (Configuração de Ambiente);

- Dia 02 High Speed [(Tags)](##HTML);

  - Tags Mencionadas na aula;
  - Outras Tags

- Dia 03 - To be continued (CSS);
  - Princípios
  - Reset;
  - Display;

## HTML (HyperText Markup Language)

Estrutra básica de construção WEB. É uma forma de marcação de texto utilizada para a interpretação do texto pelo navegador

### TAGS

São elementos HTML que servem para a marcação de texto, são utilziados pelos os leitores de tela, além de facilitar na organização do código.

#### Tags mencionadas na aula

- <**html\> →** Representa a raiz de um documento HTML, todas as demais tags são derivadas desse elemento, ou seja, estão contidas dentro dele;
- **<head\> →** Esta tag irá conter os elementos que serão lidos pela máquina através das meta tags, tais elementos ajudam a página a performar melhor no SEO;
  - **<meta\> →** Define qualquer informação de metadados que não possam ser definidos por outros elementos HTML;
  - **<link\> →** Especificam as relações entre o atual documento com outros documentos, seja no mesmo projeto, como em locais externos**;**
  - **<title\> →** Define o título do documento, aquele que é mostrado na barra de título de um navegador;
- **<header\> →** Representa o conteúdo de introdução
- **<body\> →** Representa o conteúdo do documento HTML;
  - **<main\> →** Esta _tag_ indica o conteúdo principal do site, é aqui onde estará contido a maior parte das _tags_ de uma aplicação;
  - **<section\> →** Elemento genérico para representar uma secção em um documento HTML;
  - **<h\_\> →** Representa o título e seu nível de hierarquia, onde o mais alto é o <h1\> e o mais baixo <h6\>;
  - **<p\> →** Conhecido como a _tag_ de parágrafo, é utilizada para agrupar conteúdos de texto;
  - **<a\> →** Tag de âncora, cria conexões tanta internas.

## CSS (Cascading Style Sheets)

Utilizado para a apresentação visual da página, onde se irá estilziar os elementos HTML

```CSS
body{
  background: red;
  /* Isso é um comentário*/
}
```

### **Princípios**

- **Declaração →** Pedaço do código que irá ditar as propriedades e valores a serem aplicados em um elemento HTML;
- **Seletores →** São valores de seleção, ou seja, qual elemento HTML será selecionado para estilização. Geralmente é utilizado o atributo _class_ do elemento para a seleção, mas nada impte que se utilize _tags_, _IDs_, ou outras propriedades:
  - **Epecificidade dos Seletores →** ID > Atributos > Class > Tags;
- **Propriedade →** Qual a propriedade que será modificada no seletor;
- **Valores →** Qual valor a propriedade irá receber;
- **Comentários →** Se encontra em "/_ /_", e são utilizados para ignorar certa parte do código e fazer anotações;
- **Cascata →** Característica do CSS para a sua aplicação de estilos, onde a ordem e a espeficicade importam.

### **Reset**

Por default, as _tags_ do HTML já possuem alguns estilos de CSS pré-estabelecidos, o que pode vir a fazer o desenvolvedor perder o controle dos estilos. Por isso é comum realizar o reset das definições, onde se cria um file 'zerando' os estilos desejados.

```CSS
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### **CSS Display**

É uma propriedade que especifica a disposição da renderização do elemento em tela. Os principais _displays_ utilizaodos para o desenvolvimento são o Flexbox e Grid, mas existem diversos outros, que são utilizados muitas vezes de forma default por algumas _tags_, como o block, inline, e inline-block.

**Flexbox**
Imagem

**Grid**
Imagem

## **Power Up**

## **Referênicias**

[Tags HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element)

[CSS Especificidade](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)

[CSS Display](https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
