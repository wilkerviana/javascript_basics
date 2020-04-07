# Hands On

## Objetos

*Um objeto é uma coleção de dados e/ou funcionalidades relacionadas (que geralmente consistem em diversas variáveis e funções — que são chamadas de propriedades e métodos quando estão dentro de objetos). Vamos trabalhar com um exemplo para entender como eles são.*

```
var me = {
    name: 'Wilker',
    nickname: 'Will',
    age: 29
}

var you = new Object();
you.name = 'Ronaldo';
you.nickname = 'Fenomeno';
you.age = 38
```

> *MDN Objetos Javascript*: https://developer.mozilla.org/pt-BR/docs/Aprender/JavaScript/Objetos/B%C3%A1sico

Para acessar alguma propriedade de um objeto temos duas formas:
- Notação de colchetes
- Notação de ponto

Imagine que é necessário um elemento para acessar propriedades de um objeto.\

**Notação de colchete:**
```
me['name']
// retornará o valor 'Wilker'
```

**Notação de ponto:**
```
me.age
// retornará o valor 29
```

<small>_*Na maioria das vezes é utilizado a notação de ponto para acessar propriedades de um objeto_</small>

### Objetos complexos

```
var company = {
    name: 'Facebook Company',
    products: ['Facebook', 'Instagram', 'WhatsApp'],
    ceo: 'Mark Zuckeberg',
    units:
        [
            {
                country: 'Brazil',
                address: 'Rua Leopoldo Couto de Magalhães Júnior, 700',
                director: 'Dom Pedro II'
            },
            {
                country: 'México',
                address: 'Pedregal 24 - Cidade do México',
                director: 'Roberto Gómez Bolaños'
            }
        ]
}
```

## Exercícios

- Declare uma variável chamada empresa, sem valor.

- Após declarada, atribua o valor `Company` à variável empresa.

- Declare uma nova variável chamada `seresSp`, e atribua o valor 150.

- Declare uma nova variável chamada `seresPr`, e atribua o valor 20.

- Declare uma nova variável chamada `totalSeres`, e adicione uma instrução somando as váriaveis `seresSp` e `seresPr`.

- Declare uma variável chamada `seresIntegração`, com valor 4.

- Utilize a variável `totalSeres` somando a ele a variável `seresIntegração`, usando o operador de soma abreviado.

- Qual é o valor da variável `totalSeres` até aqui?

- Declare uma variável chamada `produtos` que recebe um array (uma lista) com os produtos: 'Bio', 'RH', 'Sign', 'Docs', 'Salário'

- Digite a instrução que imprime o valor de 'Sign', presente na variável `produtos`.

- Digite o código que verifica se a variável `seresPr` é igual ou menor a variável `seresSp` (testando também o tipo).

- Crie um objeto chamado `times`, que contém as propriedades: id, nome, integrantes, produtosAtendidos.\
Preencha o valor das propriedades como quiser, seguindo apenas as orientações:\
`id` -> deve ser um número\
`nome` -> deve ser uma string\
`integrantes` -> deve ser um array (lista) de strings\
`produtosAtendidos` -> deve ser um array (lista) de strings

- Digite a instrução que imprime o valor da propriedade 'nome' presente no objeto `times`.


