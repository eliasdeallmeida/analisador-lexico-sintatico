# Analisador Léxico e Sintático

Implementação de um analisador léxico e sintático em Python para uma linguagem C-like.

## Analisador Léxico

O Analisador Léxico é capaz de identificar e classificar os seguintes elementos:
- **Palavras-chave**: int, float, for, if, etc.
- **Identificadores**: Nomes de variáveis e funções.
- **Literais**: Inteiros, flutuantes, strings, caracteres.
- **Operadores**: Aritméticos, lógicos, de atribuição, etc.
- **Delimitadores**: Parênteses, chaves, ponto e vírgula.
- **Comentários**: Comentários de linha e de bloco.

## Analisador Sintático

O Analisador Sintático que valida a estrutura do código-fonte e constrói uma Árvore de Sintaxe Abstrata (AST) que descreve a estrutura hierárquica do programa.

1. Possui implementação das principais construções da linguagem C, como:
- Declarações de variáveis.
- Estruturas de controle: if, for, while.
- Expressões aritméticas e lógicas.
- Blocos de código e funções.

2. Detecta erros de sintaxe e exibe mensagens de erro adequadas.
