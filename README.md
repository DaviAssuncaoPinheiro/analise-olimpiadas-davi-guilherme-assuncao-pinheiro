# Análise de Medalhas Olímpicas

Trabalho de análise de dados sobre medalhas olímpicas, feito com Python e Pandas.

A ideia é consolidar o total de medalhas por país separando por jogos de verão, inverno e o total geral. Os dados históricos vão de 1896 até 2020 e os dados de Paris 2024 foram adicionados separadamente pra completar o quadro.

## Dados

- `dados-historicos/` — base com resultados de todos os atletas olímpicos (fonte: Olympedia)
- `dados-paris-2024/` — dados das olimpíadas de Paris 2024 (fonte: Kaggle)

## Como rodar

Abrir o notebook `analise_medalhas_olimpiadas.ipynb` no Jupyter e rodar todas as células. Ele gera as 3 tabelas de medalhas (verão, inverno e total) e os 3 gráficos com o top 50 de cada categoria.

## Requisitos

- Python 3
- pandas
- matplotlib