# Hands On

## Funções

Funções são blocos de construção fundamentais em JavaScript. Uma função é um procedimento de JavaScript - um conjunto de instruções que executa uma tarefa ou calcula um valor. Para usar uma função, você deve defini-la em algum lugar no escopo do qual você quiser chamá-la.

> *MDN Funções Javascript:* https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Fun%C3%A7%C3%B5es

### Sintaxe

```
function sum() {
    return 2 + 6;
}
```
Para executar:
```
sum(); // retorna 8
```

Funções também podem receber parâmetros para serem executados na sua chamada:
```
function sum(num) {
    return 2 + num;
}

sum(75); // retorna 77
```

## Function Expression & Function Declaration

**Function Expression**
```
var welcome = function(name) {
    return 'Welcome ' + name + '!';
}
```

**Function declaration**
```
function welcome(name) {
    return 'Welcome ' + name + '!';
}
```

Para executar a função:
```
welcome('Mickey'); // retorna Welcome Mickey!
```

## Métodos

Funções também podem ser atribuídas como valor de propriedade de um objeto, nesse caso chamamos de **Método**

### Sintaxe


```
const car = {
  name: 'Ka',
  model: 'sedan',
  speed: 10,
  speedUp: function() {
    this.speed *= 2; 
  }
}
```

No exemplo acima criamos um **método** `speedUp` do objeto `car`.
Nos deparamos também com uma nova **keyword** - `THIS`. Em resumo o `this` faz referência ao próprio _escopo_ definido.
No nosso exemplo o _escopo_ é o objeto `car`, e dentro da função executamos a multiplicação do valor `speed` do objeto e atribuímos o novo valor à `propriedade` em questão.
Para executar um método:
```
car.speedUp();
```
Se acessarmos a propriedade `speed` do objeto, teremos:
```
car.speed // 20
```