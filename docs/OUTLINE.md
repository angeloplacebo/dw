# Roteiro das Aulas

[\# 01 - Apresentação da Disciplina (16/03/2018)](#-01---apresentação-da-disciplina-16032018)<br>
[\# 02 - Estrutura com HTML (23/03/2018)](#-02---estrutura-com-html-23032018)<br>
[\# 03 - Estilo com CSS (06/04/2018)](#-03---estilo-com-css-06042018)<br>
[\# 04 - Estilizando texto e box (13/04/2018)](#-04---estilizando-texto-e-box-13042018)<br>
[\# 05 - Criando Dashboard Admin (20/04/2018)](#-05---criando-dashboard-admin-20042018)<br>
[\# 06 - Avalição de HTML e CSS (27/04/2018)](#-06---avalição-de-html-e-css-27042018)<br>
[\# 07 - Introdução ao php (04/05/2018)](#-07---introdução-ao-javascript-04052018)<br>
[\# 08 - Introdução ao Javascript (11/05/2018)](#-08---introdução-ao-javascript-11052018)<br>
[\# 09 - Geração Dinâmica com JS (18/05/2018)](#-09---geração-dinâmica-com-js-18052018)<br>
[\# 10 - Consumindo JSON e Geração Dinâmica com JS (08/06/2018)](#-10---consumindo-json-e-geração-dinâmica-com-js-08062018)<br>
[\# 11 - Pacotes JS e Simulado de Javascript Avaliação de JS (15/06/2018)](#-11---pacotes-js-e-simulado-de-javascript-avaliação-de-js-15062018)<br>
[\# 12 - Avalição de Javascript e Servidor LAMP (29/06/2018)](#-12---avalição-de-javascript-e-servidor-lamp-29062018)<br>
[\# 13 - Fundamentos de PHP (06/07/2018)](#-13---fundamentos-de-php-06072018)<br>
[\# 14 - APIs em PHP (13/07/2018)](#-14---APIs-em-PHP-13072018)<br>

## \# 01 - Apresentação da Disciplina (16/03/2018)
---

**Conteúdo:**
- Apresentação da disciplina:
  - Objetivo, conteúdo, avaliação, comunicação, bibliografia e ferramentas
  - [O que você vai aprender em DW?](http://slides.com/luizcarlos/o-que-vou-aprender-em-dw#/)
  - Conteúdo
    - Fundamento e finalidade do frontend (HTML, CSS, JS) e backend (PHP, MySQL)
    - Exibindo a [arquitetura da Web](https://www.youtube.com/watch?v=guvsH5OFizE) (Tripé: URL, HTTP, HTML; [slide](https://ifpb.github.io/web-guide/slides/web.pdf))
    - Fundamentos de uma Linguagem de Marcação ([guide](https://ifpb.github.io/html-guide/markup/))

**Exercício:**
* Analisar o [site da discplina](https://ifpb.github.io/lm/) e se inscrever no channel `#dw20181` do [slack do ifpb](https://ifpb.slack.com).
* Configurar seu computador com essas [ferramentas](TOOLS.md).
* Descreva o que acontecer ao acessar uma página da Web, como a do [IFPB](http://www.ifpb.edu.br)
* Pesquisar sobre a evolução da Web.
* Descreva o que é uma Linguagem de Marcação.

## \# 02 - Estrutura com HTML (23/03/2018)
---

**Conteúdo:**
- [HTML](https://ifpb.github.io/html-guide/html/)
  - Tags
  - Atributos
  - Entidades
  - Comentários
- Editando HTML com [Visutal Studio Code (vscode)](http://code.visualstudio.com) e visualizando com o [Google Chrome](https://www.google.com/chrome/)
- [Referências dos Elementos no MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/)

**Exercício:**
* Reconstrua a [Primeira Página da Web](https://ifpb.github.io/html-exercises/html/first-web-page/)
* [Inspecione uma página na Web](https://ifpb.github.io/html-exercises/html/inspect-page/)
* Estruture o manual do [comando PING](https://ifpb.github.io/html-exercises/html/man-ping/) em HTML ([Fonte](https://linux.die.net/man/8/ping))
* Escolha algum manual do [GNU Manuals Online](https://www.gnu.org/manual/manual.html) ou do [Debian](https://www.debian.org/doc/) para tentar reproduzi-lo parcialmente.

## \# 03 - Estilo com CSS (06/04/2018)
---

**Conteúdo:**
- [CSS](https://ifpb.github.io/css-guide/css/)
  - Sintaxe
    - [Propriedades](https://ifpb.github.io/css-guide/css/property/)
    - [Seletores](https://ifpb.github.io/css-guide/css/selector/)
    - [Funções](https://ifpb.github.io/css-guide/css/function/)
    - [At-rules](https://ifpb.github.io/css-guide/css/at-rule/)
    - [Media query](https://ifpb.github.io/css-guide/css/media-query/)
  - Herança no CSS
- [Inspecionando estilos dos Elementos](https://developers.google.com/web/tools/chrome-devtools/inspect-styles/): Analisando e editando estilos

**Exercício:**
* [Criando seu primeiro estilo](https://ifpb.github.io/css-exercises/css/hello-world-css/)
* [Selecionando elementos no HTML](https://ifpb.github.io/css-exercises/css/selector-css/)
* [Curriculum Vitae com Estilo](https://ifpb.github.io/css-exercises/css/curriculum-style-text/)
* Estilize o mamual do comando Ping em CSS:
  * [Proposta](https://ifpb.github.io/css-exercises/css/man-ping/) de [Miguel Cabral](https://github.com/BelarminoM)

## \# 04 - Estilizando texto e box (13/04/2018)
---

**Conteúdo:**
- CSS
  - [Tipografia](https://ifpb.github.io/css-guide/css/typography/)
  - [Box Model](https://ifpb.github.io/css-guide/css/box-model/)
- Uso de bibliotecas no CSS
  - [Web Fontes](https://ifpb.github.io/css-guide/css/web-font/)
  - [Ícones](https://ifpb.github.io/css-guide/css/icon/)

**Reflexão:**

* Quais estilos podemos aplicar em um texto?
* O que é um elemento de bloco e de linha?
* Que configurações de tamanho podemos aplicar em um elemento de bloco?
* Como utilizamos fontes do Google Fonts?
* Como utilizamos ícones?
* Que estilos podemos aplicar em uma tabela?

**Exercício:**
* Analise o Box Model desses [títulos](https://ifpb.github.io/css-guide/css/box-model/)
* [Estilizando Tabelas](https://ifpb.github.io/css-exercises/css/table-css/)

## \# 05 - Criando Dashboard Admin (20/04/2018)
---

**Conteúdo:**
- [Bootstrap](https://ifpb.github.io/css-guide/packages/bootstrap/)

**Reflexão:**
* Como reutilizar estilos de terceiros?
* Quais são os prós e contras de utilizar o Bootstrap?
* Como habilitamos o Bootstrap no HTML e CSS?
* Com o Bootstrap é possível normalizar o estilo do seu HTML?
* É possível definir alguma layout usando Bootstrap?
* Qual é a diferença entre `Content` e `Components` no Bootstrap?

**Exercício:**
* [Criando Dashboard Admin](https://ifpb.github.io/css-exercises/packages/bootstrap/dashboard-admin/)
  * [Proposta do Ample Admin](https://ifpb.github.io/css-exercises/packages/bootstrap/dashboard-admin/response/ample-admin-walisson) de [Walisson Silva](https://github.com/walissonsilva)
* Simulado de HTML e CSS:
  * [Host Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/host-monitor/)
  * [eZ Server Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/ez-server-monitor/)
    * [Proposta](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/ez-server-monitor/code-response/walisson/) de [Walisson Silva](https://github.com/walissonsilva)
  * [Pingdom Monitor](https://ifpb.github.io/css-exercises/challenges/packages/bootstrap/pingdom-monitor/)

## \# 06 - Avalição de HTML e CSS (27/04/2018)
---

> [Avaliação de HTML e CSS](../exams/prova-html-css.md)<br>
> <br>
> Especificação do [Projeto Final](../exams/projeto.md)

## \# 07 - Introdução ao Javascript (04/05/2018)
---

**Conteúdo:**
- [Javascript EcmaScript](https://ifpb.github.io/javascript-guide/ecma/)
  - [Variável](https://ifpb.github.io/javascript-guide/ecma/variable/)
  - [Tipos](https://ifpb.github.io/javascript-guide/ecma/)
  - [Expressões e operadores](https://ifpb.github.io/javascript-guide/ecma/expression-and-operator/)
  - [Estrutura de Decisão](https://ifpb.github.io/javascript-guide/ecma/statements-and-declarations/)
  - [Funções](https://ifpb.github.io/javascript-guide/ecma/function/)
- Formulário
  - [Estrutura](https://ifpb.github.io/html-guide/html/form/)
- Bootstrap
  - [Form](https://getbootstrap.com/docs/4.1/components/forms/)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Running Javascript in Browser](https://ifpb.github.io/javascript-guide/w3c/running-javascript-browser/)
  - [Window](https://ifpb.github.io/javascript-guide/w3c/window/window.html)
  - [DOM](https://ifpb.github.io/javascript-guide/w3c/dom/) 
    - [Node (DOM tree)](https://ifpb.github.io/javascript-guide/w3c/dom/node.html)
    - [Document](https://ifpb.github.io/javascript-guide/w3c/dom/document.html): `querySelector()`
    - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `innerHTML`
    - [HTML Input Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-input-element.html): `checked`, `value`
  - [DOM Event](https://ifpb.github.io/javascript-guide/w3c/dom-event/): `onclick`

**Reflexão:**
* Para que serve os formulários e como estruturamos um?
* Por que o Javascript pode ser divido em recursos do EcmaScript e W3C?
* Como executamos código Javascript?
* Como declaramos variáveis no Javascript?
* Quais são os tipos primitivos e objetos do Javascript?
* Quais são os operadores do Javascript? Como podemos montamos expressões?
* O que acontece quando passamos uma quantidade de argumentos diferente do total de parâmetros?
* Para chamar uma função é necessário declará-lo antes de sua chamada?
* O que são parâmetros default dentro das funções no Javascript?
* Como integramos Javascript com HTML no Navegador?
* É possível acessar recusos do Navegador com o Javascript? Por exemplo, é possivel acessar os botões de navegação de histórico? Ou a URL da barra de endereço?
* Qual a importância da árvore DOM para o Javascript?
* Um Elemento no HTML pode ser analisado como sendo mais de um objeto no DOM? Mostre algum exemplo.
* Como acessamos um elemento do HTML via `document` no Javascript?
* Como acessamos ou alteramos o conteúdo dos elementos `<div>`, `<input type="text">` e `<input type="radio">`?(selecionado)?
* Como atribuímos um evento em um botão no Javascript?

**Exercício:**
* Crie um script para:
  * Através de `const x = 10` definir `x+2`
  * Através de `const x = 10` definir `x²`
  * Através de `const x = 10` definir `3x²+12x-4`
  * Através de `const x = 10` definir `x+3 > √x`
  * Calcular o [IMC](https://ifpb.github.io/javascript-exercises/ecma/basic/bmi/) usando `if` e `switch`
  * [Somar](https://ifpb.github.io/javascript-exercises/ecma/function/sum/)
  * [Calcular a área do círculo](https://ifpb.github.io/javascript-exercises/ecma/function/area-of-circle/)
  * [Calcular operações aritméticas básicas](https://ifpb.github.io/javascript-exercises/ecma/function/calc/)
* Crie uma interface Web para:
  * Este [formulário](https://ifpb.github.io/html-guide/html/form/#simple-form) usando a estilização do Bootstrap.
  * [IMC](https://ifpb.github.io/javascript-exercises/w3c/bmi-simple/)

## \# 08 - Introdução ao Javascript (11/05/2018)
---

**Conteúdo:**
- [Javascript EcmaScript](https://ifpb.github.io/javascript-guide/ecma/)
  - [Estrutura de Repetição](https://ifpb.github.io/javascript-guide/ecma/statements-and-declarations/#iterations-dowhile-for-forin-forof-while)
  - [Tipos](https://ifpb.github.io/javascript-guide/ecma/):
    - String ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/string/syntax.html), [objeto](https://ifpb.github.io/javascript-guide/ecma/string/object.html))
    - Array ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/array/syntax.html), [objeto](https://ifpb.github.io/javascript-guide/ecma/array/object.html))
    - JSON ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/json/syntax.html), [manipulação](https://ifpb.github.io/javascript-guide/ecma/object/syntax.html#changing-object), [iterando](https://ifpb.github.io/javascript-guide/ecma/object/syntax.html#object-interaction))
  
**Reflexão:**
* Quais são as estruturas de repetição do Javascript?
* No Javascript, como manipulamos (criar, alterar, iterar, ações) String, Array e JSON?
* Como estruturamos dados compostos em Javascript?

**Exercício:**
* Crie um script para:
  * Exibir a séria de [00 até 99](https://ifpb.github.io/javascript-exercises/ecma/basic/numbers/) de dez em dez usando `for`, `while` e `do-while`.
  * [Harmonic series](https://ifpb.github.io/javascript-exercises/ecma/basic/harmonic-series/)
  * [Array Operation](https://ifpb.github.io/javascript-exercises/ecma/array/array-operations/)
  * [Array Util](https://ifpb.github.io/javascript-exercises/ecma/array/array-util/)
  * [List Generator](https://ifpb.github.io/javascript-exercises/ecma/string/list-generator/)
  * [Table Generator](https://ifpb.github.io/javascript-exercises/ecma/string/table-generator/)
  * [String Util](https://ifpb.github.io/javascript-exercises/ecma/string/string-util/)
* Crie uma representação desse dado:

| Host | Address | Mask |
|-|-|-|
| PC 1	| 192.168.0.1 |	255.255.255.0 |
| Server	| 10.0.0.1 |	255.255.255.0 |

## \# 09 - Geração Dinâmica com JS (18/05/2018)
---

**Conteúdo:**
- [Javascript EcmaScript](https://ifpb.github.io/javascript-guide/ecma/)
  - [Funções Anônimas](https://ifpb.github.io/javascript-guide/ecma/function/#function-expression--anonymous-function)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `setAttribute()`, `innerHTML`, `insertAdjacentHTML()`
  - [HTML Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-element.html): `style`, `focus()`
  - [DOM Event](https://ifpb.github.io/javascript-guide/w3c/dom-event/)
    - [EventTarget](https://ifpb.github.io/javascript-guide/w3c/dom-event/event-target.html): `addEventListener()`
    - [GlobalEventHandlers](https://ifpb.github.io/javascript-guide/w3c/dom-event/global-event-handlers.html): `onclick`
  

**Reflexão:**
* O que são funções anônimas?
* Como adicionamos eventos a um elemento selecionado?
* No exercício do IMC gráfico, explique como adicionamos eventos de teclado para ao pressionar:
  * A tecla 'Enter' exiba o resultado do IMC;
  * A tecla 'Escape' limpe os valores digitados nos `<input>` e foque no primeiro input.
* Como alteramos o estilo de um elemento no Javascript?
* No exercício do IMC gráfico, explique como alteramos a cor do resultdo do IMC conforme o resultado, por exemplo, vermelho para obeso e assim por diante.
* Como acessamos ou alteramos o conteúdo dos elementos `<div>`, `<input type="text">` e `<input type="radio">` (selecionado)?
* Como inserimos um novo parágrafo no final da `<div>` a seguir sem recriar seus elementos internos?

```html
<div>
  <p>Lorem ipsum dolor</p>
  <p>Dolor ipsum lorem</p>
</div>
```

**Exercício:**
* Crie uma interface Web para:
  * [IMC com Evento](https://ifpb.github.io/javascript-exercises/w3c/bmi-event/)
  * [IMC com Estilo](https://ifpb.github.io/javascript-exercises/w3c/bmi-css/)
  * [IMC com Validação](https://ifpb.github.io/javascript-exercises/w3c/bmi-validator/)
  * [Calculadora](https://ifpb.github.io/javascript-exercises/w3c/calculator/)

## \# 10 - Consumindo JSON e Geração Dinâmica com JS (08/06/2018)
---

**Conteúdo:**
- [Web API](https://ifpb.github.io/javascript-guide/ecma/json/syntax.html#web-api)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Fetch API](https://ifpb.github.io/javascript-guide/w3c/fetch-api/) ([AJAX](https://ifpb.github.io/javascript-guide/w3c/xmlhttprequest/#asynchronous-javaScript-and-xml-ajax))
  - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `remove()`
  - [Node](https://ifpb.github.io/javascript-guide/w3c/dom/node.html): `parentNode`

**Reflexão:**
* Por que as Web API geralmente respondem com JSON?
* O que o Fetch API permite fazer?
* Como exibimos apenas a cidade do IP `8.8.8.8` usando a API do [ipinfo.io](https://ipinfo.io/developers)? Use essa rota `https://ipinfo.io/8.8.8.8/json` e o [Fetch API](https://ifpb.github.io/javascript-guide/w3c/fetch-api/).
* Como removemos um elemento no HTML via Javascript?

**Exercício:**
* [Gentelella App Versions](https://ifpb.github.io/javascript-exercises/w3c/gentelella-app-versions/)
* [Gentelella Top Tiles](https://ifpb.github.io/javascript-exercises/w3c/gentelella-top-tiles)
* [IP Info 1](https://ifpb.github.io/javascript-exercises/w3c/ipinfo-table-api/)
* [IP Info 2](https://ifpb.github.io/javascript-exercises/w3c/ipinfo-api/)
* [Iptable](https://ifpb.github.io/javascript-exercises/w3c/iptable/)

**Projeto:**

Apresentação das propostas de [projetos](https://padlet.com/lucachaves/projetodw20181).

## \# 11 - Pacotes JS e Simulado de Javascript Avaliação de JS (15/06/2018)
---

**Conteúdo:**
* [Javascript Ecma](https://ifpb.github.io/javascript-guide/ecma/)
* [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
* [Javascript Packages](https://ifpb.github.io/javascript-guide/packages/)

**Reflexão:**
* Como montamos gráficos usando Javascript?

**Exercício:**
* [Javascript Ecma](https://ifpb.github.io/javascript-exercises/ecma/)
* [Javascript W3C](https://ifpb.github.io/javascript-exercises/w3c/)
* [Javascript Packages](https://ifpb.github.io/javascript-exercises/packages/)
  * [Ample Admin Charts](https://ifpb.github.io/javascript-exercises/packages/charts/ample-admin-charts/)
* [Javascript Challenges](https://ifpb.github.io/javascript-exercises/challenges/)
  * [eZ Server Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/ez-server-monitor/)
  * [Host Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/host-monitor/)
  * [Pingdom Monitor](https://ifpb.github.io/javascript-exercises/challenges/w3c/pingdom-monitor/)

## \# 12 - Avalição de Javascript e Servidor LAMP (29/06/2018)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [Lamp Server](https://ifpb.github.io/php-guide/lamp/)

**Reflexão:**
* Como configurar um ambiente backend com PHP e MySQL?

**Avaliação:**

> Todos os detalhes da avaliação estão disponíveis nesta [página](../exams/prova-js.md)

## \# 13 - Fundamentos de PHP (06/07/2018)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Core](https://ifpb.github.io/php-guide/core/)
    - [Variable](https://ifpb.github.io/php-guide/core/variable/)
    - [Expression and Operator](https://ifpb.github.io/php-guide/core/expression-and-operator/)
    - [Statements](https://ifpb.github.io/php-guide/core/statements/)
    - [Function](https://ifpb.github.io/php-guide/core/function/)
  - [PHP Stdlib](https://ifpb.github.io/php-guide/stdlib/)
    - Process Control Extensions
      - [Program execution](https://ifpb.github.io/php-guide/stdlib/program-execution/)

**Reflexão:**
* Como executamos código PHP?
* Como declaramos variáveis no PHP?
* Quais são os tipos de dados do PHP?
* Quais são os operadores do PHP?
* Quais são as estruturas de controle e repetição do PHP?
* Como criamos uma função em PHP?
* O que acontece quando passamos uma quantidade de argumentos diferente do total de parâmetros?
* Como executamos comandos via PHP?
* Qual a finalidade do script [`ping.php`](https://ifpb.github.io/php-guide/stdlib/program-execution/#ping)?

**Exercício:**
* Crie um script para:
  * Através de `x = 10` definir `x+2`
  * Através de `x = 10` definir `x²`
  * Através de `x = 10` definir `3x²+12x-4`
  * Através de `x = 10` definir `x+3 > √x`
  * Calcular o [IMC](https://ifpb.github.io/php-exercises/core/basic/bmi/)
  * Gerar algumas [séries numéricas](https://ifpb.github.io/php-exercises/core/basic/numbers/)
  * Calcular a [soma de números](https://ifpb.github.io/php-exercises/core/function/sum/)
  * Calcular a [área do círculo](https://ifpb.github.io/php-exercises/core/function/area-of-circle/)
  * Calcular as [operações aritméticas básicas](https://ifpb.github.io/php-exercises/core/function/calc/)
* Como executar o comando `ls` por meio do PHP?
  
## \# 14 - APIs em PHP (13/07/2018)
---

**Conteúdo:**
- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Stdlib](https://ifpb.github.io/php-guide/stdlib/)
    - File System Related Extensions 
      - [Filesystem](https://ifpb.github.io/php-guide/stdlib/filesystem/)
    - Other Basic Extensions
      - [JSON](https://ifpb.github.io/php-guide/stdlib/json/)
    - Other Services
      - [SSH2 — Secure Shell2](https://ifpb.github.io/php-guide/stdlib/ssh2/)
    - Process Control Extensions 
      - [Program execution](https://ifpb.github.io/php-guide/stdlib/program-execution/)
    - Text Processing
      - [PCRE — Regular Expressions (Perl-Compatible)](https://ifpb.github.io/php-guide/stdlib/pcre/)
      - [Strings](https://ifpb.github.io/php-guide/stdlib/strings/)
  - [PHP Web](https://ifpb.github.io/php-guide/web/)
    - [HTTP Methods](https://ifpb.github.io/php-guide/web/http/)
    - [Web API](https://ifpb.github.io/php-guide/web/web-api/)

**Reflexão:**
* Como obter dados no PHP?
* Como executamos chamadas de sistema em PHP com e sem privilégio?
* Como editamos um arquivo de configuração por meio do PHP?
* Como formatar dados no PHP para retornar JSON?

**Exercício:**
* Crie uma API para listar arquivos de path no formato JSON.
* Crie uma API dos serviços de um SO no qual é possível realizar as seguintes as ações `start` e `stop`. Dica, use o comando `service`.
* Crie o esquema da API do seu projeto baseado nos templates existentes em [Web API](https://ifpb.github.io/php-guide/web/web-api/).

## \# 15 - PHP Web e Simulado de PHP (20/07/2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 16 - Avaliação de PHP e Acompanhamento do Projeto (27/07/2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 17 - MySQL (28/07/2018)
---

> [Projeto Final](../exams/projeto.md)

## \# 18 - PHP PDO (03/08/2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 19 - Acompanhamento do Projeto (04/08/2018)
---

> [Projeto Final](../exams/projeto.md)

## \# 20 - Prova e Projeto Final (10/08/2018)
---

> Entrega do [Projeto Final](../exams/projeto.md) e todos os detalhes da avaliação estão disponíveis nesta [página](../exams/prova-php.md).
