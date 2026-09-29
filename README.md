# Resolução exercício15.1

## Descrição do problema
O programa solicita ao usuário um número inteiro de 0 a 9 e exibe a escrita por extenso desse algarismo em letras minúsculas. Caso o usuário insira qualquer valor fora desse intervalo, o sistema deve exibir uma mensagem indicando erro de validação.

## Como Funciona
1. O usuário insere um valor numérico inteiro, que é armazenado na variável `numero`.
2. O código avalia o valor utilizando uma estrutura condicional encadeada (`if / else if / else`):
   - Cada bloco valida individualmente se o número corresponde a um algarismo de `0` a `9` e imprime seu respectivo nome (ex: `"zero"`, `"um"`, `"dois"`, etc.).
   - O bloco final `else` captura qualquer valor fora da faixa permitida e exibe a mensagem `"numero invalido"`.
