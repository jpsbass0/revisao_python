# revisao_python

Notebooks Jupyter para introdução/revisão de Python. Usam apenas a biblioteca padrão.

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
| 3.5 | `import random`, `random.randint()` e loop com limite de repetições | Jogo da adivinhação | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_03/m3_05_adivinhacao.ipynb) |
| 4.1 | `range()` e resto da divisão (`%`) | Contar os divisores de um número | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_04/m4_01_divisores.ipynb) |
| 4.2 | Decisão depois do loop e casos-limite | Informar se um número é primo | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_04/m4_02_primo.ipynb) |
| 5.1 | Listas, posições, `len()` e maior até o momento | Maior valor de uma lista de números | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_05/m5_01_maior_valor.ipynb) |
| 5.2 | `len()` em strings, comparação por critério e empate | Maior string de uma lista | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_05/m5_02_maior_string.ipynb) |
| 5.3 | Lista vazia, `.append()` e `type()` | Separar strings e números em duas listas | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_05/m5_03_separar_strings_numeros.ipynb) |
| 6.1 | Posições em strings, `range(len())` e caractere anterior | Substituir repetições por `@` | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_06/m6_01_substituir_repetidos.ipynb) |
| 6.2 | Blocos de caracteres e último bloco | Imprimir as sequências de caracteres repetidos | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_06/m6_02_sequencias_repetidas.ipynb) |
| 6.3 | Letra atual, contador e `str()` | Compressão | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_06/m6_03_compressao.ipynb) |
| 6.4 | `.isdecimal()`, números de vários algarismos e `*` com texto | Descompressão | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_06/m6_04_descompressao.ipynb) |
| 7.1 | `def`, parâmetros, `return` x `print()` | Função do IMC | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_07/m7_01_funcao_imc.ipynb) |
| 7.2 | Vários `return` e combinação de funções | Função de classificação do IMC | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_07/m7_02_funcao_classificacao_imc.ipynb) |
| 7.3 | Encapsular código e loop dentro de loop | Jogo do Número Mágico repetido até o usuário parar | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_07/m7_03_numero_magico.ipynb) |
| 7.4 | Função com loop e acumulador | Soma dos divisores | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_07/m7_04_soma_divisores.ipynb) |
| 7.5 | Uma função usando outra | Número abundante, deficiente ou perfeito | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_07/m7_05_abundante_deficiente_perfeito.ipynb) |
| 8.1 | Dicionários e listas como valores | Dicionário de divisores | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_08/m8_01_dicionario_divisores.ipynb) |
| 8.2 | Dicionário em modo contínuo | Agenda telefônica | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_08/m8_02_agenda.ipynb) |
| 8.3 | Listas como valores e funções com dicionário | Agenda completa | [abrir](https://colab.research.google.com/github/jpsbass0/revisao_python/blob/main/aluno/modulo_08/m8_03_agenda_completa.ipynb) |

## Como usar

**Sem instalar nada:** clique em "abrir" na tabela acima para abrir o notebook no Google Colab.

**No computador:** qualquer Python 3.10 ou mais recente com Jupyter (ou VS Code com a extensão Jupyter). Os notebooks foram testados no Python 3.10 e no 3.14.

Nas células com `input()`, digite a resposta na caixa que aparece e pressione Enter. Use ponto como separador decimal (`1.75`, não `1,75`).

Nos Módulos 5.1 a 5.3, a entrada é a lista da primeira linha da célula da atividade: para testar, troque essa lista.
