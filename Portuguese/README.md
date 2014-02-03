
1. O que te excita ou te interessa em programação/codificação?
2. Fale sobre seu ambiente de desenvolvimento preferido. (SO, Editor, Browser, Ferramentas, etc)
3. Descreva seu trabalho quando cria uma página web.
4. Descreva a diferença entre _progressive enhancement_ and _graceful degradation_.
5. Explique o que significa "HTML Semântico".
6. Como você pode otimizar os recursos de um site?
7. Por que é melhor servir recursos de um site de múltiplos domínios?
8. Quantos recursos um navegador pode baixar, simultaneamente, a partir de um determinado domínio?
9. Fale 3 formas de diminuir o _page load_ (tempo de carregamento real e percebido)
10. Quais ferramentas você usa para testar a performance do seu código?
11. Se você pudesse dominar uma tecnologia deste ano, qual seria?
12. Explique a importância de normas e órgãos normativos.
13. O que é FOUC? Como você evita FOUC?
14. O que um `doctype` faz?
15. Qual a diferença entre _standards mode_ e _quirks mode_?
16. Quais as limitações quando utilizamos páginas XHTML?
17. Existe algum problema em utilizar páginas como `application/xhtml+xml`?
18. Quais são os benefícios em utilizar o atributo `data-`?
19. Considere o HTML5 como uma plataforma web aberta. Quais são os blocos de construção de HTML5?
20. Descreva a diferença entre cookies, sessionStorage e localStorage.
21. Explique o evento _delegation_.
22. Explique como `this` funciona em JavaScript.
23. Explique como funciona herança prototipada.
24. Como você testa seu JavaScript?
25. O que é um _hashtable_?
26. O que são as variáveis `undefined` e `undeclared`?
27. O que é uma _closure_, e como/por que você usaria uma?
28. Qual o caso de uso típico para funções anônimas?
29. Explique o padrão "JavaScript module pattern" e quando você o usaria.
30. Como você organiza seu código? (module pattern, herança clássica?)
31. Qual a diferença entre objetos herdados e objetos nativos?
32. Qual a diferença entre:

```javascript
function Person(){}
var person = Person()
var person = new Person()
```

33. Qual a diferença entre `.call` e `.apply`?
34. Explique `Function.prototype.bind`.
35. Quando você otimiza seu código?
36. Você pode explicar como funciona a herença no Javascript?
37. Quando você deve usar o `document.write()`?
38. Qual a diferença entre feature detection, feature inference, e o uso de UA string?
39. Explique o que é AJAX mais detalhadamente possível.
40. Explique como o JSONP funciona (e como ele realmente não é AJAX).
41. Você já utilizou templates com Javascript?
42. Se sim, quais bibliotecas foram utilizadas? 
43. Explique o que é "hoisting".
44. Descreva o que é event bubbling.
45. Qual a diferença entre atributo e propriedade?
46. Porque a extensão de objetos nativos não são uma boa ideia?
47. Porque a extensão de elementos nativos não são uma boa ideia?
48. Qual a diferença entre o evento document load e o evento document ready?
49. Qual a diferença entre `==` e `===`?
50. Explique como você pega um parâmetro na URL do browser.
51. Explique a política de _same-origin_ em relação a Javascript.
52. Descreva os padrões de herança em JavaScript.
53. Faça isso funcionar:

```javascript
[1,2,3,4,5].duplicate(); // [1,2,3,4,5,1,2,3,4,5]
```

54. Descreva a estratégia para memoization (evitar a repetição de cálculo) no JavaScript.
55. O que é um operador ternário, o que a palavra "ternário" indica/significa?
56. O que é o `"use strict";`? Quais a vantagens e desvantagens de sua utilização?

### Exemplos de códigos JavaScript:

```javascript
~~3.14
```

57. Questão: Qual é o valor a ser retornado?

```javascript
"sou uma lasanha".split("").reverse().join("");
```

58. Questão: Qual é o valor a ser retornado?


```javascript
( window.foo || ( window.foo = "bar" ) );
```
59. Questão: Qual é o valor de `window.foo`?


```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
60. Questão: Qual o retorno destes dois alerts?


```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

61. Questão: Qual o valor de `foo.length`?


```javascript
var foo = {};
foo.bar = 'hello';
```

62. Questão: Qual o valor de `foo.length`?

### Questões específicas de jQuery:

63. Explique o que é "chaining".
64. Explique o que é "deferreds".
65. Quais são algumas especificações de optimização do jQuery que você pode implementar?
66. O que o `.end()` faz?
67. Como, e porque, faria namespacing de vários agregadores de eventos?
68. Cite 4 valores diferentes que você pode passar pelo método jQuery
69. Quais são os efeitos do queue?
70. Qual a diferença entre `.get()`, `[]`, e `.eq()`?
71. Qual a diferença entre `.bind()`, `.live()`, e `.delegate()`?
72. Qual a diferença entre `$` e `$.fn`? 
73. Optimize esse seletor:
```javascript
$(".foo div#bar:eq(0)")
```
74. Qual a diferença entre 'delegate()' e 'live()'?
75. Descreva o que é o arquivo "reset" do css e o que ele faz e como ele é útil.
76. Descreva o que são floats e como eles funcionam.
77. Quais são as várias técnicas para "clearing" e quais delas são apropriadas para qual contexto?
78. Explique o que são CSS Sprites, e como você implementaria eles em um website.
79. Quais são suas técnicas favoritas para troca de imagens e quais dela você usa.
80. CSS Hacks, arquivo condicional .css, ou... alguma outra coisa?
81. Como você desenvolve sua página para browsers com recursos limitados?
  * Quais técnicas/processos você usa?
82. Quais são as diferentes formas de visualizar conteúdo escondido (e como fazer para deixar eles disponíveis apenas para leitores de tela?)
83. VoCê já utilizou algum sistema de grid, se sim, qual você prefere?
84. Você já utilizou ou implementou media queries ou css's específicos para mobile?
85. Como você optimiza suas páginas para impressão?
86. Quais são algumas técnicas para escrever um eficiente CSS?
87. Você já utilizou pré-processadores css? (SASS, Compass, Stylus, LESS)
88. Como você implementaria um website que não utilizaria fontes padrões nos computadores?
89. Explique como um browser determina quais os elementos que correspondem a um seletor CSS.
90. Qual a coisa mais legal que você desenvolveu, qual você ficou mais orgulhoso?
91. Quais suas partes favoritas sobre as ferramentas de desenvolvimento que você usa?
92. Qual sua "feature" favorita do Internet Explorer?
