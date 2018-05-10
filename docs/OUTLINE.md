# Roteiro das Aulas

[\# 01 - Apresentação da Disciplina (16/03/2018)](#-01---apresentação-da-disciplina-16032018)<br>
[\# 02 - Estrutura com HTML (23/03/2018)](#-02---estrutura-com-html-23032018)<br>
[\# 03 - Estilo com CSS (06/04/2018)](#-03---estilo-com-css-06042018)<br>
[\# 04 - Estilizando texto e box (13/04/2018)](#-04---estilizando-texto-e-box-13042018)<br>
[\# 05 - Criando Dashboard Admin (20/04/2018)](#-05---criando-dashboard-admin-20042018)<br>
[\# 06 - Avalição de HTML e CSS (27/04/2018)](#-06---avalição-de-html-e-css-27042018)<br>
[\# 07 - Introdução ao Javascript (04/05/2018)](#-07---introdução-ao-javascript-04052018)<br>
[\# 08 - Geração Dinâmica com JS (11/05/2018)](#-08---geração-dinâmica-com-js-11052018)<br>
[\# 09 - Consumindo JSON e Pacotes JS (18/05/2018)](#-09---consumindo-json-e-pacotes-js-18052018)<br>

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
    - [Document](https://ifpb.github.io/javascript-guide/w3c/dom/document.html): `querySelector()`
    - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `innerHTML`
    - [HTML Input Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-input-element.html): `checked`, `value`
    - [Node (DOM tree)](https://ifpb.github.io/javascript-guide/w3c/dom/node.html)

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
* É possível acessar recusos do Navegador com o Javascript? Por exemplo, é possivel acessar os botões de navegaçõa de histórico?
* Como atibuímos um evento em um botão no Javascript?
* Por que a árvore DOM é tão importante para o Javascript?
* Um Elemento no HTML pode ser analisado como sendo mais de um objeto no DOM?

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

## \# 08 - Geração Dinâmica com JS (11/05/2018)
---

**Conteúdo:**
- [EcmaScript](https://ifpb.github.io/javascript-guide/ecma/)
  - [Estrutura de Repetição](https://ifpb.github.io/javascript-guide/ecma/statements-and-declarations/#iterations-dowhile-for-forin-forof-while)
  - [Tipos](https://ifpb.github.io/javascript-guide/ecma/):
    - String ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/string/syntax.html), [objeto](https://ifpb.github.io/javascript-guide/ecma/string/object.html))
    - Array ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/array/syntax.html), [objeto](https://ifpb.github.io/javascript-guide/ecma/array/object.html))
    - JSON ([sintaxe](https://ifpb.github.io/javascript-guide/ecma/json/syntax.html), [manipulação](https://ifpb.github.io/javascript-guide/ecma/object/syntax.html#changing-object), [iterando](https://ifpb.github.io/javascript-guide/ecma/object/syntax.html#object-interaction))
  - [Funções Anônimas](https://ifpb.github.io/javascript-guide/ecma/function/#function-expression--anonymous-function)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [HTML Element](https://ifpb.github.io/javascript-guide/w3c/dom/html-element.html): `style`, `focus()`
  - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `innerHTML`, `insertAdjacentHTML()`
  - [DOM Event](https://ifpb.github.io/javascript-guide/w3c/dom-event/)
    - [EventTarget](https://ifpb.github.io/javascript-guide/w3c/dom-event/event-target.html): `addEventListener()`
    - [GlobalEventHandlers](https://ifpb.github.io/javascript-guide/w3c/dom-event/global-event-handlers.html): `onclick`

**Reflexão:**
* Quais são as estruturas de repetição do Javascript?
* No Javascript, como manipulamos (criar, alterar, iterar, ações) String, Array e JSON?
* Como estruturamos dados compostos em Javascript?
* O que são funções anônimas?
* Como inserimos dados no HTML? Por exemplos, em um:
  * `<input type="text">`
  * `<div></div>`
* Como inserimos um novo parágrafo no final da `<div>` a seguir sem recriar seus elementos internos?

```html
<div>
  <p>Lorem ipsum dolor</p>
  <p>Dolor ipsum lorem</p>
</div>
```

* Como alteramos o estilo de um elemento no Javascript?
* Como adicionamos eventos a um elemento selecionado?

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

* Crie uma interface Web para:
  * [IMC com validação](https://ifpb.github.io/javascript-exercises/w3c/bmi-validator/)
  * [Calculadora](https://ifpb.github.io/javascript-exercises/w3c/calculator/)
  * [Gentelella App Versions](https://ifpb.github.io/javascript-exercises/w3c/gentelella-app-versions/)
  * [Gentelella Top Tiles](https://ifpb.github.io/javascript-exercises/w3c/gentelella-top-tiles)

## \# 09 - Consumindo JSON e Pacotes JS (18/05/2018)
---

**Conteúdo:**
- [Web API](https://ifpb.github.io/javascript-guide/ecma/json/syntax.html#web-api)
- [Javascript W3C](https://ifpb.github.io/javascript-guide/w3c/)
  - [Node](https://ifpb.github.io/javascript-guide/w3c/dom/node.html): `parentNode`
  - [Element](https://ifpb.github.io/javascript-guide/w3c/dom/element.html): `innerHTML`, `insertAdjacentHTML()`, `remove()`
  - [Fetch API]()

**Reflexão:**

**Exercício:**
  * [Iptable](https://ifpb.github.io/javascript-exercises/w3c/iptable/)
  * [IP Info 1](https://ifpb.github.io/javascript-exercises/w3c/ipinfo-table-api/)
  * [IP Info 2](https://ifpb.github.io/javascript-exercises/w3c/ipinfo-api/)

<!-- 
## \# 10 - Simulado de Javascript (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 11 - Avaliação de JS (//2018)
---

> Todos os detalhes da avaliação estão disponíveis nesta [página](../exams/prova-js/)

> Além da avaliação será divulgado o critério de avaliação do [Projeto Final](../exams/projeto.md)

## \# 12 - Fundamentos do PHP (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 13 - APIs em PHP (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 14 - Acompanhamento de Projetos (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 15 - API dos Projetos (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 16 - MySQL & PHP PDO (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 17 -  (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 18 -  (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 19 -  (//2018)
---

**Conteúdo:**

**Reflexão:**

**Exercício:**

## \# 20 - Prova e Projeto Final (//2018)
---

 -->