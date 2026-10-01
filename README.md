# Árvore AVL — inserção, balanceamento e remoção

Exercício da disciplina de Resolução de Problemas Estruturados em
Computação — PUCPR. Profa. Lisiane Reips.

**Inserir:** 55, 26, 29, 13, 12, 11, 16, 1, 5, 29, -15, 4, 16, 8, 4, 5, 3, 1312, 100, 88
**Remover:** 4, 29, 100, 5, -15, 16, 55

## Convenções adotadas

- Valores repetidos são ignorados
- Remoção com 2 filhos: substituto = maior mais próximo (direita 1x, depois sempre à esquerda)
- Altura: folha = 1, vazio = 0

## Resolução

### Inserções (1.1 a 1.11)
![Inserções, primeira parte](img/01-insercoes-55-a-15.jpg)

### Inserções (1.12 a 1.19)
![Inserções, segunda parte](img/02-insercoes-4-a-88.jpg)

### Remoções
![Remoções](img/03-remocoes.jpg)

## Rotações realizadas

| Inserção | Caso | Rotações |
|---|---|---|
| 29 | LR | esquerda em 26, direita em 55 |
| 12 | LL | direita em 26 |
| 11 | LL | direita em 29 |
| 1 | LL | direita em 12 |
| 4 | LR | esquerda em 1, direita em 11 |
| 100 | RL | direita em 1312, esquerda em 55 |

Nenhuma remoção exigiu rotação.
