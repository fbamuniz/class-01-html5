# HTML5
![NPM](https://img.shields.io/npm/l/react)
# Introdução

O HTML (HyperText Markup Language) foi criado em 1991, por [Tim Berners-Lee](https://pt.wikipedia.org/wiki/Tim_Berners-Lee), no [CERN](https://pt.wikipedia.org/wiki/Organiza%C3%A7%C3%A3o_Europeia_para_a_Pesquisa_Nuclear) (European Council for Nuclear Research) na Suíça. Inicialmente o HTML foi projetado para interligar instituições de pesquisa próximas e compartilhar documentos com facilidade. Em 1992, foi liberada a biblioteca de desenvolvimento www (World Wide Web), uma rede de alcance mundial, que junto com o HTML proporcionou o uso em escala mundial da Web.

O HTML é uma linguagem de marcação. Esta linguagem é constituída por tags (ou elementos HTML), que são códigos que delimitam conteúdos específicos, segundo uma sintaxe própria. O HTML tem tags para criar páginas na Web. Estas tags definem o tipo de letra, qual o tamanho, cor, espaçamento, e vários outros aspectos da página. No início era muito complicado aprender HTML, pois eram muitos comandos para fazer algo simples. A cada nova versão, o HTML fica mais fácil de utilizar e adquire mais funções. Atualmente qualquer pessoa pode acessar a Internet e aprender a construir um site básico em questão de horas, seguindo os passos de tutoriais e aprendendo as funções de cada elemento.

O HTML foi a primeira linguagem de nível mundial, porém não é a única. Existem muitas outras linguagens destinadas a criação de paginas para Web, porém o HTML ainda prevalece. Atualmente já é possível integrar varias linguagens na mesma página da Web, sendo possível usar duas ou mais linguagens no mesmo projeto.

Hoje em dia é fundamental trabalharmos com o HTML em conjunto com outras tecnologias (que veremos mais tarde), como o Cascading Style Sheets (CSS3) e o JavaScript. Em uma analogia simples, o HTML é como se fosse a estrutura de uma casa, o CSS o acabamento e o JavaScript as funcionalidades como a porta automática da garagem ou o ventilador de teto.

<img src="https://miro.medium.com/max/640/1*q99J7XLYVWgOt69E8IuXqw.gif" width="300px">

Para criar e editar códigos em HTML é necessário qualquer editor de texto comum, como bloco de notas. Para testar os códigos, basta salvar o arquivo em formato .html e executar. Ainda é necessário ter um Web Browser (ou navegador) configurado como padrão. O interessante é que não é necessária a Internet para cirar páginas HTML, pois o arquivo com os códigos esta na máquina onde esta sendo executada.

Abaixo, um exemplo de uma estrutura básica de página em HTML:

```html
<!-- Isto é um comentário e pode ser usado em qualquer parte da página -->
<!DOCTYPE html>
<!-- Algumas tags possuem atributos e valores, como o caso do lang="pt-br" -->
<html lang="pt-br">
<!-- No cabeçalho são definidas configurações importantes sobre o funcionamento da página -->    
<head>
    <!-- As tags também são chamadas de elementos HTML -->
    <meta charset="UTF-8">
    <!-- Definimos um título para a página. Algumas tags possuem fechamento, como o caso de </title> -->
    <title>Programação Web</title>
</head>
<!-- No body construímos a estrutura da página -->
<body>
<!-- Abaixo um exemplo simples de estrutura, com título e parágrafo -->    
    <h1>Iniciando as aulas de Programação Web</h1>
    <p>Esta é somente uma página contendo a estrura básica do HTML.</p>
<!-- A indentação é um procedimento muito importante no âmbito do desenvolvimento de sistemas -->    
</body>
</html>
```

Existem programas profissionais para criação de páginas em HTML, como o [Visual Studio Code](https://code.visualstudio.com/) ou [Notepad++](https://notepad-plus-plus.org/downloads/). Apesar da enorme importância para o mundo da informação, o HTML havia estacionado na versão 4 desde 1999 e não acompanhou as dinâmicas mudanças que ocorreram nos anos seguintes e para atender as necessidades, careceu utilizar plugins externos como o já aposentado [Adobe Flash Player](https://pt.wikipedia.org/wiki/Adobe_Flash_Player) e outros. Mas felizmente, isso são coisas do passado, pois a [W3C](https://pt.wikipedia.org/wiki/W3C) (World Wide Web Consortium) e a [WHATWG](https://pt.wikipedia.org/wiki/WHATWG) (Web Hypertext Application Technology Working Group) disponibilizaram anos depois a versão HTML5.

## O que é o HTML5

O HTML5 é o último padrão lançado para a estruturação e apresentação de conteúdo na Word Wide Web, trazendo melhorias significativas com novas funcionalidades de semântica e acessibilidade, além de melhorar o suporte aos mais recentes conteúdo multimídias. As principais mudanças que a nova versão trouxe aos usuários foram: 

- Melhor tratamento de exceção
- Mais tags para substituir scripts
- Independência de plataforma 
- Redução da necessidade de plugins externos.

## Características do HTML5

As características da versão HTML5 estão ligadas diretamente as necessidades de suporte independente aos formatos de conteúdo multimídia da Web 2.0, as novas funcionalidades de semânticas e acessibilidade. Na sequência destacamos suas principais características:

**a) Inclusão do elemento Canvas para desenho.**

O elemento Canvas foi incluído para permitir desenhar gráficos em uma página Web, tarefa essa que só era possível com a utilização de plugins externos. Neste curso não trabalharemos com o elemento Canvas.

**b) Inclusão dos elementos vídeo e áudio para reprodução multimídia**

Outro motivo para integrar plugins externos é o uso de áudio e vídeo nas páginas Web. Com a inclusão de tags específicas para este fim, o HTML5 dá suporte nativo para a reprodução de áudio e vídeo, sem a necessidade de utilizar mecanismos externos. 

```html
<!-- Exemplo de faixa de áudio -->
	<audio controls>
		<source src="horse.mp3" type="audio/mpeg">
	</audio>
	<br><br>
	<!-- Exemplo de faixa de vídeo e legenda -->
	<video width="320" height="240" controls>
		<source src="forrest_gump.mp4" type="video/mp4">
		<track src="fgsubtitles_en.vtt" kind="subtitles" srclang="en" label="English">
	</video>
```

**c) Melhor suporte para armazenamento local**

Inclusão de novos objetos para armazenamento de dados locais. Estes procedimentos não serão abordados neste curso, uma vez que a manipulação de arquivos depende do uso de uma outra linguagem no [back-end](https://pt.wikipedia.org/wiki/Front-end_e_back-end).

**d) Inclusão de novos elementos de conteúdo específico.**

Muitos elementos do HTML4 foram excluídos da versão HTML5, uns por nunca terem sido usados, outros por estarem obsoletos e outros por serem usados indevidamente. O HTML5 traz novos elementos para proporcionar aos usuários uma melhor estrutura, desenho e conteúdo multimídia (denominados elementos semânticos). A relação completa desses elementos será abordada durante o curso, mas abaixo segue uma prévia:

```html
<!-- Exemplo de elementos semânticos -->
	<section class="section-1">
            <article class="div-3-left">
                <header>
                    <h1>Lorem ipsum dolor sit amet consectetur.</h1>
                </header>
                <section>
                    <img src="https://picsum.photos/id/816/350/200" class="img-highlight">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    <a href="#" class="a-link">Continuar</a>
                </section>
            </article>
    </section>
```

**e) Inclusão de novos controles para formulário.**

Uma carência do HTML4 era a escassa quantidade de controles para formulário, fazendo com que os desenvolvedores recorressem as famosas bibliotecas JavaScript, muitas vezes incompatíveis com determinados navegadores. No HTML5 novos controles de formulário foram incluídos para facilitar a vida dos desenvolvedores. Um dos remanescentes do HTML4, o elemento input, ganhou novos valores para o atributo type, fazendo com que o desenvolvedor ganhe maior controle sobre a entrada de dados pelo usuário. Abaixo, uma prévia desses itens:

```html
<!-- Entrada do tipo cor -->
    <label>Cores</label><br>
    <input type="color"><br><br>

<!-- Entrada do tipo data -->
    <label>Data</label><br>
    <input type="date"><br><br>

<!-- Entrada do tipo mês -->
    <label>Mês</label><br>
    <input type="month"><br><br>

<!-- Entrada do tipo semana -->
    <label>Semana</label><br>
    <input type="week">
```

**f) Total suporte ao CSS3**

Para dar ainda mais liberdade à criatividade dos usuários, o HTML5 dá total suporte ao CSS3. Com essa integração, as páginas Web podem receber os mais variados tipos de estilos como sombra nos textos e quadros, efeitos de transição, quadro com cantos arredondados e vários recursos que o CSS3 oferece.

No vídeo abaixo da Dotec, é apresentado um pequeno resumo do que é o HTML5 e sua aplicabilidade. 

[![Assista ao vídeo](https://img.youtube.com/vi/Tld2CrT5c2s/maxresdefault.jpg)](https://www.youtube.com/watch?v=Tld2CrT5c2s)

## Lista de exercícios
01) Neste exercício - com o título "Figuras Históricas" - você deverá inserir duas imagens de dois personagens históricos (por exemplo, Shakespeare e Machado de Assis). As imagens precisam ser necessariamente no formato WebP e PNG. Logo abaixo das imagens, insira um breve parágrafo com a biografia de ambos e, ao final do texto, um vídeo do Youtube. Tanto o vídeo quando as imagens devem possuir a mesma largura. As duas figuras históricas devem ser separadas por uma linha horizontal.  

01) Neste exercício - com o título "Figuras Históricas" - você deverá inserir duas imagens de dois personagens históricos (por exemplo, Shakespeare e Machado de Assis). As imagens precisam ser necessariamente no formato WebP e PNG. Logo abaixo das imagens, insira um breve parágrafo com a biografia de ambos e, ao final do texto, um vídeo do Youtube. Tanto o vídeo quando as imagens devem possuir a mesma largura. As duas figuras históricas devem ser separadas por uma linha horizontal.  


## Referências

- HTML. Infoescola, disponível em: [https://www.infoescola.com](https://www.infoescola.com/informatica/html/#:~:text=O%20HTML%20foi%20criado%20em,e%20compartilhar%20documentos%20com%20facilidade.). Acesso em: 28 de jan. de 2023.
- HTML5. Devmedia, disponível em: [https://www.devmedia.com.br](https://www.devmedia.com.br/as-novidades-do-html5/23992). Acesso em: 28 de jan. de 2023.

## Como executar

Pré-requisitos: 
- Visual Studio Code
- GIT

```bash
# clonar repositório
git clone https://github.com/fbamuniz/class-01-html5.git

```

## Bibliografia Básica 
- MEYER, E. S. CSS - técnicas profissionais para um layout moderno. Porto Alegre: Bookman, 2011.
- POWERS, S. Aprendendo JavaScript. São Paulo: Novatec, 2010.
- PETRUCELLI, E. E. HTML5, CSS e JavaScript. Brasília: NT Editora, 2019.
- DUCKETT, J. HTML e CSS: Projete e Construa Websites. Rio de Janeiro: Alta Books. 2016.
- SILVERMAN, R.E. Git: Guia prático. São Paulo: Novatec, 2019.
- GRINBERG, M. Desenvolvimento web com Flask: Desenvolvendo aplicações web com Python. São Paulo: Novatec, 2019.

## Bibliografia Complementar:
- GOMES, A. L. XHTML/CSS: criação de páginas web (Informática). São Paulo: Editora Senac, 2019.
- QUIERELLI, D. A. Criando sites com HTML-CSS-PHP: Construindo um projeto - Iniciante. Joinville: Clube dos Autores, 2012.
- TITTEL, E., NOBLE, J. HTML, XHTML e CSS Para Leigos. Rio de Janeiro: Alta Books, 2014

# Autor

Prof. Frederico Barbosa Muniz<br>
https://linktr.ee/fbamuniz