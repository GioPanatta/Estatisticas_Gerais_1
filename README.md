# Análise Estatística com Python

Este repositório contém um notebook Jupyter ('Estatisticas_Gerais_1.ipynb') que realiza uma série de operações de análise de dados em Python usando o conjunto de dados 'credit_data.csv'. O foco principal do notebook é a exploração, limpeza e amostragem de dados.

## Operações Realizadas

O notebook executa as seguintes operações principais:

1. **Importação de Bibliotecas**: Uso da biblioteca pandas para manipulação de dados.
2. **Leitura e Exploração de Dados**: Carregamento e visualização inicial dos dados a partir do arquivo CSV.
3. **Limpeza de Dados**: Remoção de entradas com valores nulos.
4. **Amostragem de Dados**: Aplicação de diversas técnicas de amostragem para análise de subconjuntos de dados. As técnicas incluem:
   - Amostragem Aleatória Simples
   - Amostragem Sistemática
   - Amostragem por Agrupamento
   - Amostragem por Reservatório
   - Amostragem Estratificada
5. **Análise Comparativa**: Comparação das médias das colunas 'age', 'income' e 'loan' entre o conjunto de dados completo e os conjuntos resultantes das diferentes técnicas de amostragem.

## Ferramentas e Bibliotecas Utilizadas

- Python
- Pandas
- Sklearn (para amostragem estratificada)

## Como Usar

Para executar o notebook, é necessário ter um ambiente Python com as bibliotecas mencionadas instaladas. O arquivo CSV 'credit_data.csv' deve estar no mesmo diretório do notebook.

