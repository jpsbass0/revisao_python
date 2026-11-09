# Introdução à Programação em Python

Notebooks Jupyter para aulas introdutórias de Python. Usam apenas a biblioteca padrão.

Autor: João Pedro Susin Basso.

## Estrutura

```
aluno/       notebooks para os alunos: sem saídas e com a célula da atividade vazia
professor/   mesmos notebooks, com a solução de referência e as saídas de uma execução completa
```

Cada notebook segue a mesma sequência: título e objetivos, **Conceitos**, **Exemplos**, **Erros comuns**, **Atividade** e **Testes** (entradas e saídas esperadas para conferir a solução).

## Módulos

| Módulo | Conteúdo | Atividade | Colab (aluno) |
|---|---|---|---|
| 1.1 | Variáveis, tipos, operadores, `input()` e f-string | Cálculo do IMC | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_01/m1_01_imc.ipynb) |
| 2.1 | Comparações e `if`/`elif`/`else` | Classificação do IMC | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_02/m2_01_classificacao_imc.ipynb) |
| 3.1 | Laço `for`, contador, acumulador de texto, `in` e `.lower()` | Imprimir as consoantes de uma frase | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_03/m3_01_consoantes.ipynb) |
| 3.2 | `break`, variável de controle e `not` | Encontrar a quinta vogal de uma frase | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_03/m3_02_quinta_vogal.ipynb) |
| 3.3 | `while`, texto vazio (`""`) como sentinela, acumulador | Soma e média dos números digitados | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_03/m3_03_soma_media.ipynb) |
| 3.4 | Validação de entrada com `while True`, `and`/`or` e `.isdecimal()` | Validar número inteiro de 0 a 10 | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_03/m3_04_validacao.ipynb) |

## Como usar

**Sem instalar nada:** clique em "abrir" na tabela acima para abrir o notebook no Google Colab.

**No computador:** qualquer Python 3.10 ou mais recente com Jupyter (ou VS Code com a extensão Jupyter). Os notebooks foram testados no Python 3.10 e no 3.14.

Nas células com `input()`, digite a resposta na caixa que aparece e pressione Enter. Use ponto como separador decimal (`1.75`, não `1,75`).
