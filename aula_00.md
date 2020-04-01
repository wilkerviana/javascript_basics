# Hands On

## Variáveis

Estrutura composta por: 

- **var** *palavra-chave reservada*
- **nome** *nome da variável*
- **=** atribuição de valor
- **'Will'** valor armazenado

```
var nome = 'Maria';
```

**Atualizar valor da variável:**
```
nome = 'Mari';
// valor armazenado -> 'Mari'
```

**Concatenar valores (string):**
```
var nomeCompleto = nome + 'ana';
// valor armazenado -> 'Mariana'
```

**Somar valores numéricos:**
```
var idade = 1 + 29;
// valor armazenado -> 30
```

**Conversão de valores automática (STRING)**:\
*A conversão é realizada automaticamente quando o operador `+` é utilizada em uma expressão que contém uma string*

Exemplo:
```
var ano = 20 + '20';
// valor armazenado -> '2020'
```

**Conversão de valores automática (NUMBER)**:\
*A conversão é realizada automaticamente quando qualquer operador matemático, **exceto**: `+`; é utilizado em uma expressão que contém um número*

Exemplo:
```
var ano = 2 * '1010';
// valor armazenado -> '2020'
```

## Estruturas condicionais

*Uma expressão (premissa) que pode ser avaliada como verdadeira (true) ou falsa (false).<br>
A condicional **if**  é uma estrutura condicional que executa a afirmação, dentro do bloco, se determinada condição for verdadeira. Se for falsa, executa as afirmações dentro de **else**.*

```
var idade = 20;

if (idade > 60) {
    console.log('Você está no grupo de risco! Fique em casa!')
} else {
    console.log('Seja responsável, fique em casa')
}
```