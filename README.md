# 7DaysOfCode_Day01
# Operadores de Comparação em JavaScript

Ao trabalhar com condições em JavaScript, precisamos utilizar operadores de comparação para avaliar valores e tomar decisões no código. 
Abaixo está uma tabela com os principais operadores de comparação:

| Operador | Operação          | Exemplo    |
|----------|------------------|------------|
| `>`      | Maior que         | `(a > b)`  |
| `<`      | Menor que         | `(a < b)`  |
| `>=`     | Maior ou igual a  | `(a >= b)` |
| `<=`     | Menor ou igual a  | `(a <= b)` |
| `==`     | Igual a           | `(a == b)` |
| `!=`     | Diferente de      | `(a != b)` |
| `===`    | Idêntico a        | `(a === b)` |
| `!==`    | Não idêntico a    | `(a !== b)` |
| `&&`     | E (and)           | `(a && b)` |
| `\|\|`   | Ou (or)           | `(a \|\| b)` |

## Diferença entre `==` e `===`

- O operador `==` (igual a) compara apenas os valores, sem levar em conta o tipo de dado.
- O operador `===` (idêntico a) compara tanto o valor quanto o tipo de dado.

### Exemplo em JavaScript:

```javascript
if (10 == "10") {
    console.log("Verdadeiro"); // Retorna verdadeiro, pois compara apenas o valor
}

if (10 === "10") {
    console.log("Verdadeiro"); 
} else {
    console.log("Falso"); // Retorna falso, pois os tipos são diferentes (número vs. string)
}
