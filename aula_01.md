# Hands On

## Tipos de dados

```
var name = 'Will' -> string
var age = 29 -> number
var married = true // boolean
var diseases = null
var future = undefined
```

### Arrays

*Arrays são objetos semelhantes a listas que vêm com uma série de  métodos embutidos para realizar operações de travessia e mutação. Nem o tamanho de um array JavaScript nem os tipos de elementos são fixos. Já que  o tamanho de um array pode ser alterado a qualquer momento e os dados podem ser armazenados em posições não contíguas, arrays JavaScript não tem a garantia de serem densos; isso depende de como o programador escolhe usá-los.*

Um array pode ser criad das seguinte maneira:
- dados separados por vírgula ( **,** ) dentro de um `[ ]`
- dados separados por vírgula dentro método construtor de array do JS `new Array( )`\
*_segundo exemplo não é muito utilizado_ 

```
var mailbox = ['flyer', 'bill', 'letters', 'gift'];
ou 
var mailbox = new Array('flyer', 'bill', 'letters', 'gift');
```

O array segue uma estrutura de `chave:valor` (já que é um objeto em sua essência), porém a chave de cada valor armazenado é implícita;\
Trata-se do `índice` de cada item armazenado no array.

É através deste `índice` que vamos conseguir capturar um valor específico do nosso array:
Segue a sintaxe que utilizamos para acessar um `índice`:

*_vale lembrar que na programação qualquer "contagem" sempre é iniciada em `0`_

```
mailbox[3] // valor retornado 'gift'
```

Todo array tem um tamanho que é definido dinamicamente, a partir do momento em que é criado ou alterado.
O tamanho é uma `propriedade` desse tipo de dado.
Para acessarmos uma propriedade de um array, utilizamos a _palavra-chave_ `length` seguida da notação de ponto para acessarmos propriedades:

```
mailbox.length // valor retornado 4
```

## Loop

Vamos começar a brincar com laços de repetição :D

**Loop FOR**

Uma estrutura de loop convencional é formada de três etapas:
- inicialização: `var i=0`
- condição: `i < 6`
- incremento ou decremento: `i++`

### Sintaxe
```
for(var i=0; i < 6; i++) {
    // do something
}
```

**Exemplo:**
```
for(var i=0; i < 10; i++) {
    console.log(i + ' carneirinho');
}
```

***Outras declarações de laços de repetição***

**Loop DO WHILE**
```
do{
    // do something
}
while(i < 6) {}
```

**Loop WHILE**
```
while(i < 6) {
    // do something
}
```
