# Por onde começar com Javascript?

_por [@alegalliard](https://github.com/alegalliard)_


Se você quer trabalhar com front-end, Javascript é fundamental. JS é a principal linguagem que roda no seu navegador (ou seja, do lado do cliente) e é responsável por promover a interação com o usuário.

Também existe o Javascript para servidor, conhecido como NodeJS, mas aqui neste artigo vamos focar no Javascript client-side.

**Depois que eu aprender o básico do básico de Javascript, vamos direto pro jQuery/React/Angular/Vue?**

Não vamos não. [Veja aqui o porquê](./pilota-de-framework.md).


## O que eu preciso ter ou saber antes de começar?

Seria legal se você já tivesse estudado pelo menos o básico de:

- HTML;
- CSS;
- Lógica de programação;

Pra começar melhor ainda, dê uma passadinha aqui também:

- O que é o DOM [em português](https://tableless.com.br/entendendo-o-dom-document-object-model/) ou [em inglês](https://www.guru99.com/understanding-dom-fool-guide.html);

E quando você começar a fazer o seu JS se conectar com recursos externos para trazer e enviar dados via AJAX, dá uma olhadinha em:

- [O que é HTTP](https://rockcontent.com/blog/http/)
- [Verbos HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)


## Executando o seu HTML + JS corretamente

Você até pode executar seu index.html no navegador dando 2 cliques no arquivo (que é quando na barra de endereço do seu navegador ele começa com `file://`), porém, há limitações. Se quiser fazer chamadas HTTP, por exemplo, elas não serão executadas.

Desenvolver requer que você rode um servidor na sua máquina para executar seu HTML corretamente (ou seja, lá na barra de endereço deve começar com `http://`).

### Alternativas para quem tem pressa:

- Use o [JSFiddle](https://jsfiddle.net/) ou outros [editores web](../editores-e-ides.md);

- Baixe o editor [Brackets da Adobe](http://brackets.io/) 
- -> Carregue a pasta do seu projeto;
- -> No menu superior, acesse `File (Arquivo) -> Live Preview`; 
- -> Brackets vai criar um servidor, abrir seu navegador padrão e conectar seu projeto a ele;
- -> Recurso de hot-reload: sempre que você atualizar qualquer arquivo HTML, CSS ou JS do seu projeto, o Brackets vai detectar a alteração a página será automaticamente atualizada.

Importante: o hot-reload pode ser desconectado se você acessar o Developer Tools do navegador e mexer nos elementos do DOM ou direto no console. Se isso acontecer, feche a aba e carregue live preview de novo.

### Para quem está com tempo e quer rodar um servidor local:

- Em [Python](https://developer.mozilla.org/pt-BR/docs/Learn/Common_questions/Como_configurar_um_servidor_de_testes_local#Executando_um_servidor_HTTP_local_simples)
- Em [Node](https://blog.caelum.com.br/como-criar-um-servidor-http-com-nodejs/);
- Em [PHP puro](https://codecommit.com.br/php-servidor-local-http-embutido-webserver) ou em [PHP com XAMPP](https://webdevacademy.com.br/tutoriais/instalar-configurar-servidor-local/);


## Cursos

Buscas no Youtube e no Goole usando o termo "curso básico de javascript" te levarão a resultados ótimos: muitos vídeos, artigos, e-books muito bons. Mas vou deixar aqui duas recomendações legais.

- 💵 [Javascript Ninja](https://www.udemy.com/course/curso-javascript-ninja/) por Fernando Daciuk, na Udemy;
- 🆓 [Javascript Essencial](https://www.youtube.com/watch?v=ipHuSfOYhwA&list=PLInBAd9OZCzxl38aAYdyoMHVg0xCgxrRx) por Ricardo Bernardi, no Youtube;

- 🆓 [Apostila da Caelum](https://www.caelum.com.br/apostila-html-css-javascript/#null)

## Dúvidas?

Abra uma [issue nesse repositório](https://github.com/ElasProgramam/Informacoes_Basicas/issues) com a tag _Javascript_.