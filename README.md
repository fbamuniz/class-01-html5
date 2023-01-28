# HTML5
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o HTML5

https://wmazoni-sds1.netlify.app

Desde 1999, o desenvolvimento da linguagem HTML (HyperText Markup Language) ficou estacionado na versão 4. De lá pra cá, a W3C esteve focada em linguagens como XML (Extensible Markup Language) e SVG (Scalable Vector Graphics - o uso de gráficos vetoriais em navegadores). Enquanto isso, desenvolvedores de navegadores estiveram preocupados em melhorar as funcionalidades destes, como exibir páginas em abas e oferecer integração com leitores de RSS. Recentemente, no entanto, organizações como Mozilla Foundation, Opera e Apple se uniram para atualizar o HTML e implementar novos e interessantes recursos.

Neste artigo, veremos algumas novidades que o HTML5 traz. Para quem está se familiarizando agora com o HTML, sem preocupações: os elementos tradicionais continuam os mesmos, já que o HTML5 foi planejado considerando também compatibilidade com estas funcionalidades.

Big Game Survey é uma aplicação full stack web e mobile construída durante a 1ª edição da **Semana DevSuperior** (#sds1), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em uma pesquisa de preferência de games, onde os dados são coletados no app mobile, e depois são listados no app web, que também apresenta um dashboard com gráficos baseados nestes dados.

## Layout mobile
![Mobile 1](https://github.com/acenelio/assets/raw/main/sds1/mobile1.png) ![Mobile 2](https://github.com/acenelio/assets/raw/main/sds1/mobile2.png)

## Layout web
![Web 1](https://github.com/acenelio/assets/raw/main/sds1/web1.png)

![Web 2](https://github.com/acenelio/assets/raw/main/sds1/web2.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/acenelio/assets/raw/main/sds1/modelo-conceitual.png)

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
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Wellington Mazoni de Andrade

https://www.linkedin.com/in/wmazoni

