# How to Study Javascript
 *Um roteiro para aprender Javascript básico e melhorar suas habilidades*

> Os códigos apresentados podem ser executados diretamente no console do seu navegador.

## Conteúdo
1.  [Variáveis](#variaveis)

## Variáveis
+ As variáveis são objetos que é utilizado para representar um valor, uma variável pode ser iniciada utilizando a sintaxe `var`.
```javascript
var userName;
userName = "John Snow";

console.log(userName); //John Snow
```
+ Você pode criar frases utilizando variáveis.
```javascript
var userName = "John Snow";
var locale = "Winterfell";

console.log("Hello my name is " + userName + " and I'm from " + locale);
//Hello my name is John Snow and I'm from Winterfell
```
+ Algumas boas práticas para variáveis:
    -   Use apenas letras(a-z ou A-Z) e números(0-9)
    -   Não inicie o nome de uma variável com um número
    -   Utilize lowerCamelCase que é uma prática de escrever frases compostas, iniciando pela primeira palavra toda em minúsculo e as iniciais das frases seguintes em maiúsculo.
+ Exemplos
```javascript
//bad names
var 100topUser;
var _userAge;
var mycar;
var MYCAR;
var var;

//good names
var topUser100;
var userAge;
var myCar;
var bestPraticesIsGood;
var whatJhonKnows = "nothing";
```

*work in progress...*
