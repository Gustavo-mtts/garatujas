# ia26-webdesing

Essa disciplina ensina os fundamentos do desenvolvimento web, focando principalmente em HTML, CSS e um pouco de JavaScript. A ideia é que o aluno aprenda a criar e estilizar páginas na internet, começando do básico e evoluindo para coisas mais complexas no futuro. Mesmo sendo um conteúdo introdutório, ele é essencial porque serve como base para qualquer tipo de site ou aplicação web. O curso também é pensado para iniciantes, então não é necessário ter conhecimento prévio.

## antes do início

Antes de começar, é recomendado ter um ambiente de desenvolvimento preparado, com um editor de código e um navegador atualizado. No caso, são indicados o Visual Studio Code, por ser gratuito e muito usado, e o Google Chrome, pelo mesmo motivo.

## HTML - HyperText Markup Language (Linguagem de Marcação de Hipertexto)

-O HTML (Linguagem de Marcação de Hipertexto) é a base de qualquer página web. Ele não é uma linguagem de programação, mas sim uma linguagem de marcação, ou seja, serve para organizar e estruturar o conteúdo da página. Isso inclui textos, títulos, links, imagens e outros elementos. Além da parte visual, o HTML também é importante para acessibilidade, pois organiza o conteúdo de forma que diferentes tipos de usuários, incluindo pessoas com deficiência, consigam entender e navegar na página.

O funcionamento do HTML é feito por meio de tags, que são como etiquetas que indicam o tipo de conteúdo. Essas tags geralmente têm uma abertura e um fechamento, e o conteúdo fica entre elas, como no caso de um parágrafo: `<p>texto</p>`. Existem várias tags diferentes, como `<h1>` para títulos e `<a>` para links. Também existem atributos, que são informações extras dentro das tags, como o `href` em links, que define para onde o usuário será levado, ou o `src`, que indica a origem de uma imagem.

Uma forma simples de entender o HTML é compará-lo com editores de texto como Word ou Google Docs. Quando você aplica formatações como negrito ou itálico nesses programas, no HTML isso é feito com tags específicas, como `<strong>` para dar importância ao texto (geralmente exibido em negrito) e `<em>` para dar ênfase (geralmente em itálico). Essas tags são chamadas de semânticas porque, além da aparência, também indicam o significado do conteúdo, o que é importante para acessibilidade.

Outro ponto importante é a estrutura básica de um documento HTML. Todo arquivo começa com `<!DOCTYPE html>`, que indica que é um documento HTML5. Depois vem a tag `<html>`, que envolve todo o conteúdo. Dentro dela existem duas partes principais: o `<head>`, que contém informações sobre a página (como título e configurações, mas não aparece na tela), e o `<body>`, que contém tudo que será exibido para o usuário. Também são definidos elementos importantes, como o idioma da página e a codificação de caracteres, para garantir que tudo funcione corretamente.

Além disso, os atributos HTML são usados para complementar as tags, adicionando funcionalidades e informações extras. Por exemplo, ao criar um link com a tag `<a>`, o atributo `href` define o endereço para onde o link leva. Esses detalhes são essenciais para tornar a página interativa.

## CSS - Cascading Style Sheets (Folhas de Estilo em Cascata)

Já o CSS (Folhas de Estilo em Cascata) é a linguagem responsável pela aparência da página. Enquanto o HTML organiza o conteúdo, o CSS define como ele será exibido, controlando cores, fontes, tamanhos, espaçamento e layout. Uma vantagem importante é que o CSS fica separado do HTML, o que ajuda a manter o código mais organizado e facilita mudanças no visual.

O CSS funciona com regras formadas por seletores e declarações. Os seletores indicam quais elementos do HTML serão estilizados, e as declarações definem quais estilos serão aplicados. Por exemplo, é possível mudar a cor de todos os parágrafos ou centralizar um título. Sem CSS, a página aparece com o estilo padrão do navegador, que geralmente é simples e pouco atrativo. Com CSS, é possível deixar o site mais bonito e profissional.

Existem vários tipos de seletores no CSS, como seletores por tipo de elemento, por classe, por ID, por atributos e também baseados no estado dos elementos. Um conceito importante é que o CSS segue a estrutura do HTML, funcionando em forma de “cascata”, ou seja, os estilos são aplicados de acordo com a hierarquia dos elementos. Isso permite aplicar estilos de forma mais específica, atingindo apenas os elementos desejados.

No geral, HTML e CSS trabalham juntos: o HTML cria a estrutura da página e o CSS define sua aparência. Aprender os dois é essencial para o desenvolvimento web, e a prática é fundamental para entender bem como eles funcionam.
