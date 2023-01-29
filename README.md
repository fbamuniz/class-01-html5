# jQuery3
![NPM](https://img.shields.io/npm/l/react)
# História

Em 2006, John Resig era um desenvolvedor Web que trabalhava em seus próprios projetos. Ele estava frustrado com a dificuldade de escrever JavaScript que funcionasse em vários navegadores, e decidiu escrever sua própria biblioteca JavaScript para resolver os seus problemas: o jQuery.
Em 16 de janeiro de 2006, John Resig deu uma palestra sobre sua nova biblioteca em uma BarCamp local, para um pequeno grupo de desenvolvedores Web, e publicou isso em seu blog.

jQuery é uma biblioteca de funções em JavaScript que interage com o HTML, desenvolvida para simplificar os scripts interpretados no navegador do usuário (client-side). Criada em dezembro de 2006 no BarCamp de Nova York por John Resig. Usada por cerca de 77% dos 10 mil sites mais visitados do mundo, jQuery é a mais popular das bibliotecas JavaScript.

jQuery é uma biblioteca de código aberto (open source) e possui licença dual, fazendo uso da Licença MIT ou da GNU General Public License versão 2. A sintaxe do jQuery foi desenvolvida para simplificar a navegação em documentos HTML, a seleção de elementos DOM, criar animações, manipular eventos, desenvolver aplicações AJAX e criação de plugins sobre ela. Permitindo aos desenvolvedores criarem camadas de abstração para interações de baixo nível de modo simplificado em aplicações web de grande complexidade.

A jQuery é leve, seu tamanho é em torno de 30kb, extensível, oferece suporte a plug-ins e conta ainda com uma grande equipe de desenvolvedores que vem diariamente adicionando novos recursos e funções a está biblioteca, nos disponibilizando uma grande quantidade de controles para interface.

**Utilidade do jQuery**
Podemos utilizar a jQuery para:

- Adicionarmos efeitos visuais e animações;
- Acessarmos e manipularmos o DOM;
- Carregarmos componentes Ajax;
- Provermos interatividade;
- Fazer alteração de conteúdo;
- Simplificarmos tarefas JavaScript.

**Suporte ao jQuery**

A jQuery foi desenvolvida para ser uma biblioteca com suporte a qualquer navegador Web. Ela facilita a nós desenvolvedores a muitas vezes difícil tarefa de desenvolvermos aplicações em JavaScript, tendo que atingir a enorme quantidade de navegadores em que nossa programação poderá ser executada. Como sabemos, cada navegador possui seu próprio conjunto de características de implementação que ainda pode dificultar mais ainda, de acordo com a variação de plataforma e sistema operacional onde esteja executando. Já com a jQuery, nossa programação é única e transparente.

Com a jQuery possuímos suporte também às CSS3, onde podemos utilizar seletores CSS3 mesmo que o navegador não tenha suporte a esta folhas de estilo. Isso é possível porque a própria jQuery implementa os seletores CSS3, o que faz com que ela seja independente do navegador em que estiver sendo executada.

**Construtor jQuery**
Com a jQuery temos que utilizar a função $() para encontrarmos um elemento HTML dentro da aplicação e utilizarmos as funções da biblioteca. Essa função [e tecnicamente conhecida como construtor ou função construtora e ela estará presente em todas as aplicações que utilizarmos a jQuery.

É denominada desse modo para ser fácil de decorar, e o fato de se chamar $ evita a possibilidade de ocorrer conflitos com outras funções da biblioteca do usuário. Ocasionalmente podemos vir a utilizar alguma outra biblioteca que também tenha como uso uma função chamada $. Caso isso acontece podemos usar como alternativa a função jQuery().

O construtor faz uso do seguinte parâmetro, onde alvo é um seletor CSS para TAG, ID ou classe.

$(alvo)
Vejamos alguns exemplo de sua utilização.
```javascript
$('h1')
$('p')
$('#conteudo')
$('.teste')
```
Muitos desenvolvedores Web amaram a simplicidade e o poder do jQuery, e a biblioteca de John logo ficou popular. Hoje, jQuery é a biblioteca JavaScript mais popular e é mantida pela Fundação jQuery, formada por uma grande equipe de voluntários. Quer saber mais sobre por que John inventou o jQuery e como essa biblioteca se transformou em um sucesso com centenas de contribuidores e milhares de desenvolvedores? 

Assista a esse vídeo no qual o professor da Escola de Informação da UMich, Charles Severance, entrevista John Resig no escritório da Khan Academy:

[![Assista ao vídeo](https://img.youtube.com/vi/AeCczbOctM8/maxresdefault.jpg)](https://www.youtube.com/watch?v=AeCczbOctM8)

## Referências

- Pausa para a história: como John criou o jQuery? Khan Academy, disponível em: [https://pt.khanacademy.org](https://pt.khanacademy.org/computing/computer-programming/html-js-jquery/jquery-dom-access/a/history-of-jquery). Acesso em: 28 de jan. de 2023.
- jQuery Tutorial. Devmedia, disponível em: [https://www.devmedia.com.br](https://www.devmedia.com.br/jquery-tutorial/27299). Acesso em: 28 de jan. de 2023.

# Descrição das aulas

- **lesson-01-basic** - Explicação sobre a estrutura do jQuery
- **lesson-02-arrow-function** - Aplicação da estrutura simplificada para funções
- **lesson-03-text** - Inserção de texto com jQuery
- **lesson-04-text-val-html** - Inserção de texto e elementos HTML com jQuery
- **lesson-05-index** - O método index() retorna o número da sequência de vezes que um determinado elemento foi utilizado
- **lesson-06-noconflict** - O método noConflict() altera o símbolo $ do seletor jQuery para qualquer outro desejado, impedindo possíveis conflitos
- **lesson-07-length** - O método length() retorna a quantidade de vezes que um determinado elemento HTML foi utilizado
- **lesson-08-units** - Os métodos innerWidth(), innerHeight(), outerWidth() e outerHeight() retornam o espaçamento total do tamanho, padding, border e margin em pixels do elemento
- **lesson-10-parent** - O método parent() aplica modificações somente no elemento acima. O método parent() aplicada somente no último elemento. O método parents() aplica em todos os elementos acima. O método parentsUntil() aplica de um determinado elemento até outro
- **lesson-11-children-find** - Ao contrário do método parent(), o children() trata os elementos filhos
- **lesson-12-siblings-next-prev** - O método siblings() aplica o efeito em um irmão específico. O método next() aplica o efeito no irmão direto (abaixo). O método prev() aplica o efeito no irmão direto (acima). O método prevAll() aplica o efeito em todos os irmãos direto (abaixo). O método prevAll() aplica o efeito em todos os irmãos direto (acima). O método prevUntil() aplica o efeito entre dois elementos irmãos (acima). O método nextUntil() aplica o efeito entre dois elementos irmãos (abaixo)
- **lesson-13-filter-first-eq-last** - O método first() formata o primeiro elemento. O método last() formata o último elemento. O método eq(x) formata um elemento específico da sequência
- **lesson-14-filter-not** - O método filter() permite uma nova formatação a partir da busca da classe (igual ao nome buscado). O método not() permite uma nova formatação a partir da busca da classe (diferente do nome buscado)
- **lesson-15-css** - O método click() tem a mesma funcionalidade do event click no HTML5. O método css() permite agrupar um conjunto de propriedades CSS
- **lesson-16-css-class-add-rem** - O método removeClass() remove uma classe CSS. O método addClass() adiciona uma classe CSS
- **lesson-17-css-class-toogle** - O método toggleClass() adiciona e remove a classes
- **lesson-18-atrr** - O método attr(), com um único parâmetro, retorna o valor do atributo. O método attr(), com dois parâmetros, altera o valor do atributo
- **lesson-19-hide-show** - O método show() exibe um elemento, por meio da id. O método hide() oculta um elemento, por meio da id
- **lesson-20-toogle** - O método toggle() substitui o hide/show
- **lesson-21-event** - O método click() é ativada quando clicado na área. O método mouseenter() é ativada quando entra na área. O método mouseleave() é ativada quando sai da área. O método keyup() é ativada quando digitado na input
- **lesson-22-event-on** - O método on() permite o agrupamento de eventos e um único construtor
- **lesson-23-event-trigger** - O método on() permite agrupar vários eventos em um único construtor. O método trigger() permite ativar eventos de formas diferentes. O método trigger() ativou o evento mouseleave a partir dO método click()
- **lesson-25-event-target** - O event.target.tagName resgata o elemento do objeto clicado
- **lesson-26-event-which** - O event.which na função keydown() mostra botão pressionado no teclado ou mouse
- **lesson-27-stop-propagation** - O método stopPropagation() evita que eventos sejam disparados todos de uma vez. Comente a linha 7 e 12 e descomente a 8 e 13 para testar
- **lesson-28-fade-in-out** - O método fadeIn() aplica opacidade gradativa mínima ao elemento. O método fadeOut() aplica opacidade gradativa máxima ao elemento
- **lesson-29-fade-to** - O método fadeTo() configura o tempo e a opacidade aplicada ao elemento
- **lesson-30-fade-toogle** - O método fadeToggle() aplica tanto fadeIn quanto fadeOut em um mesmo elemento, não sendo necessária a utilização de dois botões
- **lesson-31-finish** - O método finish() cancela a execução de outro método
- **lesson-32-fade-queue** - O método queue() possibilita visualizar numericamente a fila de funções que serão executadas
- **lesson-33-animate** - O método animate() possibilita movimentar elementos
- **lesson-34-animate-toogle** - O valor toggle modifica a propriedade até que ela desapareça ou reapareça 
- **lesson-35-animate-delay** - O método delay() atrasa a execução de um outro determinado método
- **lesson-36-slide-up-down** - Os métodos slideUp() e slideDown() deslizam o elemento na tela, até que ele fique oculto ou retorne ao seu estado inicial
- **lesson-37-slide-toogle** - O método slideToggle() desliza o elemento na tela, até que ele fique oculto ou retorne ao seu estado inicial no mesmo evento
- **lesson-38-animate-stop** - O método stop() cancela a execução do evento e pula para o próximo, exatamente do mesmo ponto
- **lesson-39-append-to** - O método append() solicita a adição de um elemento no final de outro elemento. O método appendTo() envia um elemento para ser adicionado no final de outro elemento
- **lesson-40-prepend** - O método append() solicita a adição de um elemento no início em outro elemento. O método prependTo() envia um elemento para ser adicionado no início de outro elemento
- **lesson-41-after-before** - O método before() solicita a adição de um elemento antes de outro elemento
- **lesson-42-remove-empty** - O método remove() remove um elemento específico. O método empty() remove todos os elementos especificados
- **lesson-43-clone** - O método clone() copia integralmente um determinado elemento e seus filhos
- **lesson-44-detach** - O método detach() remove os elementos selecionados, incluindo todos os nós de texto e filhos. No entanto, ele mantém dados e eventos. Este método também mantém uma cópia dos elementos removidos, o que permite que sejam reinseridos posteriormente
- **lesson-45-hasclass** - O método hasClass() verifica o nome de classes
- **lesson-46-position-change** - O método position() retorna a posição do elemento (top e left). O evento change() é acionado quando o valor de um elemento é alterado
- **lesson-47-position-offset** - O método offset() define ou retorna as coordenadas de deslocamento para os elementos selecionados
- **lesson-48-position-remove** - O método removeAttr() exclui o atributo do elemento. O método removeClass() exclui a classe do elemento. O método addClass() adiciona uma nova a classe ao elemento
- **lesson-49-replace** - O método replaceAll() substitui o elemento da esquerda pelo da direita. O método replaceWith() substitui o elemento da direita pelo da esquerda
- **lesson-50-scroll** - O método scrollLeft() define ou retorna a posição da barra de rolagem horizontal para os elementos selecionados. O método scrollTop() define ou retorna a posição vertical da barra de rolagem para os elementos selecionados
- **lesson-51-unwrap** - O método unwrap() remove o elemento pai dos elementos selecionados. O método wrap() agrupa os elementos HTML especificados em torno de cada elemento selecionado. O método wrapAll() envolve o(s) elemento(s) HTML especificado(s) em torno de todos os elementos selecionados. O método wrapInner() envolve o(s) elemento(s) HTML especificado(s) em torno do conteúdo (innerHTML) de cada elemento selecionado.
- **lesson-52-each** - O método each() especifica (percorre) uma função a ser executada para cada elemento correspondente.
- **lesson-53-append-get** - O método append() insere o conteúdo especificado no final dos elementos selecionados.
- **lesson-54-toarray** - O método toArray() retorna os elementos combinados pelo seletor jQuery como um array
- **lesson-55-get-xml** - Formas de manipular arquivos XML
- **lesson-56-get-xml-mvc** - Formas de manipular arquivos XML, organizando com o padrão de projeto MVC (Model, View e Controller)
- **lesson-57-get-json** - Formas de manipular arquivos JSON, organizando com o padrão de projeto MVC (Model, View e Controller)

# Como executar as aulas

## Front end Web
Pré-requisitos: 
- Visual Studio Code
- GIT

```bash
# clonar repositório
git clone https://github.com/fbamuniz/class-01-html5.git

```

## Bibliografia das aulas

- DUCKETT, J. HTML e CSS: Projete e Construa Websites. Rio de Janeiro: Alta Books. 2016.
- MEYER, E. S. CSS – técnicas profissionais para um layout moderno. Porto Alegre: Bookman, 2011.


# Autor

Prof. Frederico Barbosa Muniz 

https://linktr.ee/fbamuniz

