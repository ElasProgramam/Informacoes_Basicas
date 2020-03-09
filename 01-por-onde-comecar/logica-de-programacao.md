# Lógica de programação: essencial

_por [@alegalliard](https://github.com/alegalliard)_

Se aprender uma linguagem de programação é o mesmo que conhecer as palavras soltas de uma outra língua, a lógica é o equivalente à gramática: somente ordenando as palavras em uma determinada sequência e usando as regras corretas é que você conseguirá escrever um programa.

Escrever um bom programa depende de como a comunicadora - você - "conversa" com o computador. 

Se você passar as instruções gramaticais erradas ou dúbias, o computador vai fazer o que você não esperava gerando assim um bug. Se a instrução não estiver com o formato que o computador espera aparecerá um erro como quem diz _"não entendi isso que você quis dizer, estou parando aqui até você corrigir seu comando"_.

Então pense em um computador como um gringo com um português muito básico e que ainda por cima interpreta as coisas muito literalmente. Se você disser a ele:

> Traga 12 ovos. Se tiver batatas, traga 6.

Sim, ele vai trazer **6 ovos e 0 batatas**. Porque ele interpretou que a condição para trazer 6 ovos é encontrar batatas, e não pegar as batatas junto com os ovos. Se quiser passar a instrução corretamente você deveria dizer algo como:

> Traga 6 batatas caso você as encontre, e também 12 ovos. 


Independente da linguagem que você escolher, estudar lógica de programação é fundamental, pois é a base de tudo.


## Mão na massa - começando do zero

Há vários cursos ótimos e baratos em plataformas pagas, como na Udemy, Alura, Devmedia e outras. No youtube tem programadores dando vídeo-aulas da graça. Também dá pra achar livros em PDF e artigos usando o Google. 

Uma playlist legal: [introdução à lógica de programação](https://www.youtube.com/watch?v=8mei6uVttho&list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) do Gustavo Guanabara no Youtube.

**Ferramentas para treinar sem se preocupar com a linguagem:**

  - [Portugol](http://lite.acad.univali.br/portugol/)
  - [Visualg3](http://visualg3.com.br/)

Esses programas te permitem fazer exercícios de lógica, só que em português. Pode ser um bom começo para quem tem dificuldades com inglês.


Se você prefere **treinar lógica direto com sua linguagem favorita** é bem fácil encontrar cursos e exercícios pagos ou gratuitos. Basta procurar assim:

> Lógica de programação com {linguagem}.


Para quem quer entrar no detalhe, tem livros também:

  - Algoritmos: Lógica para desenvolvimento de programação de computadores - Jayr Figueiredo de Oliveira e José Augusto N. G. Manzano
  - Algoritmos: Teoria e Prática - Thomas Cormen
  - Introdução à Programação: 500 Algoritmos Resolvidos - Carlos Assis
  

Solidifique esse conhecimento com bastante prática, pois isso vai permitir que você se desenvolva na linguagem que escolheu e que adapte a qualquer outra com muito mais facilidade.


## Extra: por que o computador é tão literal?

Por debaixo dos panos, computador - ou melhor, o hardware - só consegue lidar instruções binárias de sim e não (ou melhor, 0 e 1). Há diversas limitações num contexto assim.

Quando programamos estamos na verdade escrevendo uma série de instruções utilizando uma linguagem que foi escrita para que humanos consigam entender.

Entre a sua linguagem e o que o computador consegue interpretar, existe um terceiro personagem que age como tradutor e intérprete (que pode ser um compilador ou um interpretador) responsável por pegar seus comandos e repassar para o computador numa linguagem binária que ele consiga entender. 

Por isso nossas instruções precisam ser claras para que a "comunicação entre você e o hardware" funcione bem. Se o computador não estiver fazendo o que você está esperando é porque você escreveu um "comando com a gramática errada", digamos assim.


## Dúvidas?

Abra uma [issue nesse repositório](https://github.com/ElasProgramam/Informacoes_Basicas/issues) com a tag _Lógica de Programação_.