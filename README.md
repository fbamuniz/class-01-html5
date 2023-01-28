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

# Descrição das aulas
## Introdução
- **class-01-basic** - _Explicação sobre a estrutura do jQuery_
- **class-02-arrow-function** - _Aplicação da estrutura simplificada para funções_
- **class-03-text** - _Inserção de texto com jQuery_
- **class-04-text-val-html** - _Inserção de texto e elementos HTML com jQuery_
- **class-05-index** - _O método index() retorna o número da sequência de vezes que um determinado elemento foi utilizado_
- **class-06-noconflict** - _O método noConflict() altera o símbolo $ do seletor jQuery para qualquer outro desejado, impedindo possíveis conflitos_
- **class-07-length** - _O método length() retorna a quantidade de vezes que um determinado elemento HTML foi utilizado_
- **class-08-units** - _Os métodos innerWidth(), innerHeight(), outerWidth() e outerHeight() retornam o espaçamento total do tamanho, padding, border e margin em pixels do elemento_
- **class-10-parent** - _O método parent() aplica modificações somente no elemento acima. O método parent() aplicada somente no último elemento. O método parents() aplica em todos os elementos acima. O método parentsUntil() aplica de um determinado elemento até outro_
- **class-11-children-find** - _Ao contrário do método parent(), o children() trata os elementos filhos_
- **class-12-siblings-next-prev** - _O método siblings() aplica o efeito em um irmão específico. O método next() aplica o efeito no irmão direto (abaixo). O método prev() aplica o efeito no irmão direto (acima). O método prevAll() aplica o efeito em todos os irmãos direto (abaixo). O método prevAll() aplica o efeito em todos os irmãos direto (acima). O método prevUntil() aplica o efeito entre dois elementos irmãos (acima). O método nextUntil() aplica o efeito entre dois elementos irmãos (abaixo)_
- **class-13-filter-first-eq-last** - _O método first() formata o primeiro elemento. O método last() formata o último elemento. O método eq(x) formata um elemento específico da sequência_
- **class-14-filter-not** - _O método filter() permite uma nova formatação a partir da busca da classe (igual ao nome buscado). O método not() permite uma nova formatação a partir da busca da classe (diferente do nome buscado)_


# Como executar o projeto

## Front end Web
Pré-requisitos: Visual Studio Code

```bash
# clonar repositório
git clone https://github.com/fbamuniz/class-01-html5.git

```

# Autor

Prof. Frederico Barbosa Muniz 

https://linktr.ee/fbamuniz

