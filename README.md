Este projeto consiste em um simples alternador de modo claro/escuro em uma interface de usuário. Ele foi desenvolvido utilizando HTML, CSS e JavaScript.

O HTML:
O arquivo HTML é estruturado com as tags <head> e <body>. Na seção <head>, são definidas as metatags, o título da página e o link para o arquivo CSS. Dentro do <body>, temos uma seção que contém um input do tipo "button" e uma label para representar o botão de alternância. Também há uma <div> com a classe "divisao" que engloba um elemento <div> com a classe "trono" e um parágrafo com o texto "O inverno está chegando".

O CSS:
O arquivo CSS define as regras de estilo para os elementos da página. Ele utiliza variáveis CSS personalizadas, declaradas na pseudoclasse :root. As variáveis são utilizadas para definir cores, imagens de fundo e outros estilos. A classe "dark_mode" é adicionada ao elemento <body> quando o botão de alternância é clicado, alterando as variáveis CSS para o modo escuro.

O JavaScript:
O arquivo JavaScript seleciona os elementos do DOM (Documento Object Model) utilizando os métodos document.querySelector(). Em seguida, é adicionado um evento de clique ao elemento com a classe "lua_e_sol". Quando o evento é acionado, a classe "dark_mode" é alternada no elemento <body>, por meio do método classList.toggle(). Isso permite que a transição entre os modos claro e escuro seja realizada.

Para executar o projeto, basta abrir o arquivo HTML em um navegador da web. Ao clicar no botão de alternância representado pela label com a classe "lua_e_sol", a aplicação alternará entre os modos claro e escuro, alterando as cores de fundo, textos e imagens de acordo com as regras definidas no CSS.

Esse projeto é uma demonstração básica de como implementar um alternador de modos de exibição em uma interface de usuário, permitindo aos usuários escolherem sua preferência de tema. É possível estender e personalizar esse projeto adicionando mais recursos, como a persistência do modo selecionado ou a adição de animações mais complexas durante a transição de temas.
