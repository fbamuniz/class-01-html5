# HTML5
![NPM](https://img.shields.io/npm/l/react)
# Introdução

O HTML foi criado em 1991, por [Tim Berners-Lee](https://pt.wikipedia.org/wiki/Tim_Berners-Lee), no [CERN](https://pt.wikipedia.org/wiki/Organiza%C3%A7%C3%A3o_Europeia_para_a_Pesquisa_Nuclear) (European Council for Nuclear Research) na suíça. Inicialmente o HTML foi projetado para interligar instituições de pesquisa próximas, e compartilhar documentos com facilidade. Em 1992, foi liberada a biblioteca de desenvolvimento www (World Wide Web), uma rede de alcance mundial, que junto com o HTML proporcionou o uso em escala mundial da Web.

O HTML é uma linguagem de marcação. Estas linguagens são constituídas de códigos que delimitam conteúdos específicos, segundo uma sintaxe própria. O HTML tem códigos para criar paginas na web. Estes códigos que definem o tipo de letra, qual o tamanho, cor, espaçamento, e vários outros aspectos do site. No início era muito complicado aprender HTML, pois eram muitos comandos para fazer algo simples. A cada nova versão, o HTML fica mais fácil de utilizar, e adquire mais funções. Atualmente qualquer pessoa pode acessar a internet a aprender a construir um site básico em questão de horas, seguindo os passos de tutoriais e aprendendo as funções de cada código.

O HTML foi a primeira linguagem de nível mundial, porem não é a única. Existem muitas outras linguagens destinadas á criação de paginas da web, porém o HTML ainda prevalece. Atualmente já é possível integrar varias linguagens na mesma pagina da Web, sendo possível usar duas ou mais linguagens no mesmo site.

Para criar e editar códigos em HTML é necessário qualquer editor de texto comum, como bloco de notas. Para testar os códigos, basta salvar o arquivo em formato .HTML e executar. Para o teste é necessário ter um navegador configurado como padrão. Não é necessária internet, pois o arquivo com os códigos esta na maquina onde esta sendo executado.

Alguns códigos em HTML e suas funções:

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

Existem programas profissionais para criação de páginas em html automaticamente, como o Visual Studio Code ou Notepad++, entretanto, com o tempo o desenvolvedor precisará criar páginas complexas demais, sendo necessário ele mesmo digitar alguns códigos HTML.

Apesar da enorme importância para o mundo da informação o HTML estancou na versão 4.0.1 desde 1999 e não acompanhou as dinâmicas mudanças que ocorreram nos últimos anos e para atender as necessidades careceu utilizar plugins externos como o flash player e outros. Mas felizmente, isso são coisas do passado, pois a W3C (World Wide Web Consortium) e a WHATWG (Web Hypertext Application Technology Working Group) disponibilizaram uma versão de teste que provavelmente será a nova cara do HTML. Esse artigo mostra as novas características dessa versão que, inclusive, já tem suporte para algumas funcionalidades nos mais conceituados navegadores e brevemente será oficializado por definitivo como o HTML 5.

## O que é HTML5

Surgido a partir de um consórcio entre a W3C (World Wide Web Consortium) e a WHATWG (Web Hypertext Application Technology Working Group), o HTML5 será o novo padrão para a estruturação e apresentação de conteúdo na Word Wide Web trazendo melhorias significativas com novas funcionalidades de semântica e acessibilidade, além de melhorar o suporte aos mais recentes conteúdo multimídias.

As principais mudanças que a nova versão proporcionará aos usuários são: Melhor tratamento de exceção, mais tags para substituir scripts, independência de plataforma e redução da necessidade de plugins externos.

## As novas características do HTML5

As novas características da versão 5 estão ligadas diretamente as necessidades de suporte independente aos novos formatos de conteúdo multimídia, as novas funcionalidades de semânticas e acessibilidade. Apresentaremos elas a seguir.

**a) Inclusão do elemento canvas para desenho.**

O elemento canvas foi incluído para permitir desenhar gráficos em uma página Web, tarefa essa que atualmente só é possível com a utilização de plugins externos. Neste curso não trabalharemos com o elemento canvas, pois futuramente será disponibilizado um outro curso somente sobre este assunto.

**b) Inclusão dos elementos vídeo e áudio para reprodução multimídia**

Outro motivo para integrar plugins externos é o uso de áudio e vídeo nas páginas Web. Com a inclusão de tags específicas para este fim, a HTML5 dá suporte nativo para a reprodução de áudio e vídeo sem a necessidade de utilizar mecanismos externos. 

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

Inclusão de novos objetos para armazenamento de dados locais (com auxilia de JavaScript).

**d) Inclusão de novos elementos de conteúdo específico.**

Muitos elementos da versão 4.0.1 foram excluídos da nova versão, uns por nunca terem sido usados, outros por estarem obsoletos e outros por serem usados indevidamente. A nova versão traz novos elementos para proporcionar aos usuários uma melhor estrutura, desenho e conteúdo multimídia (denominados elementos semânticos). A relação desses elementos será abordada na aula 18. Abaixo segue uma prévia:

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

Uma carência da versão 4.0.1 e a escassa quantidade de controles para formulário fazendo com que os desenvolvedores recorram as famosas bibliotecas JavaScript, muitas vezes incompatíveis com determinados navegadores. Na versão 5 novos controles de formulário foram incluídos para facilitar a vida dos desenvolvedores. Um dos remanescentes da versão 4.0.1, o elemento input, ganhou novos valores para o atributo type, fazendo com que o desenvolvedor ganhe maior controle sobre a entrada de dados pelo usuário. Abaixo, uma prévia:

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

Para dar ainda mais liberdade à criatividade dos usuários o HTML5 dá total suporte a mais nova versão das famosas Cascading Style Sheets, ou simplesmente CSS. Com essa integração as páginas webs podem receber os mais variados tipos de estilos como sombra nos textos e quadros, efeitos de transição, quadro com cantos arredondados e vários recursos novos que o CSS3 oferece.

## Suporte

Apesar da versão 5 não ter sido oficializada, vários navegadores continuam adicionando os novos recursos do HTML5 nas suas recentes versões. Dentre os navegadores podemos citar: Safari, Chrome, Firefox, Opera e Internet Explorer. Com a chegada da nova versão da linguagem de marcação HTML só temos a ganhar, pois além de contarmos com novos recursos que permitem uma maior estruturação dos documentos, mais funcionalidades, independência de plataforma, tratamento de exceção e suporte nativo aos recentes conteúdos multimídias, ainda podemos ficar livres dos incômodos estresses que temos ao utilizar bibliotecas e plugins externos que nem sempre funcionam como deveriam nos navegadores distintos.

No vídeo abaixo da Dotec, é apresentado um pequeno resumo do que é o HTML e sua aplicabilidade. 

[![Assista ao vídeo](https://img.youtube.com/vi/Tld2CrT5c2s/maxresdefault.jpg)](https://www.youtube.com/watch?v=Tld2CrT5c2s)

## Referências

- HTML. Infoescola, disponível em: [https://www.infoescola.com](https://www.infoescola.com/informatica/html/#:~:text=O%20HTML%20foi%20criado%20em,e%20compartilhar%20documentos%20com%20facilidade.). Acesso em: 28 de jan. de 2023.
- HTML5. Devmedia, disponível em: [https://www.devmedia.com.br](https://www.devmedia.com.br/as-novidades-do-html5/23992). Acesso em: 28 de jan. de 2023.

# Como executar

## Front end Web
Pré-requisitos: 
- Visual Studio Code
- GIT

```bash
# clonar repositório
git clone https://github.com/fbamuniz/class-04-jquery3.git

```

## Bibliografia das aulas

- DUCKETT, J. HTML e CSS: Projete e Construa Websites. Rio de Janeiro: Alta Books. 2016.
- MEYER, E. S. CSS – técnicas profissionais para um layout moderno. Porto Alegre: Bookman, 2011.


# Autor

Prof. Frederico Barbosa Muniz<br>
https://linktr.ee/fbamuniz
