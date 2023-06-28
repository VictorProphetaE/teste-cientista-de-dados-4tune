# Programa de Preparação para a Aposentadoria

Este programa calcula métricas de preparação para a aposentadoria com base em dados fornecidos em um arquivo CSV. Ele ajusta a renda atual dos indivíduos considerando a inflação anual, filtra os indivíduos elegíveis com idade mínima, calcula economias adicionais para aposentadoria e gera gráficos para análise.

## Requisitos

- Python 3.x
- Bibliotecas Python: pandas, numpy, matplotlib

## Instalação

1. Certifique-se de ter o Python instalado. Caso contrário, você pode baixá-lo em [python.org](https://www.python.org/downloads/).

2. Instale as bibliotecas Python necessárias executando o seguinte comando:
    `pip install pandas numpy matplotlib`
            
            ou

3. Caso seja no notebook Jupyter
    `!pip install pandas numpy matplotlib`

## Uso no cmd

1. Coloque o arquivo de dados em formato CSV na mesma pasta do código e nomeie-o como `data.csv`.

2. Execute o programa executando o seguinte comando:
    `python teste2.py`

3. Os resultados da preparação para a aposentadoria serão exibidos no console e também serão salvos em um novo arquivo `new_scenario.csv`.

4. Além disso, os gráficos serão gerados e salvos nos arquivos `weighted_avg_savings_shortfall_plots.pdf` e `retirement_readiness_rating.pdf`.

## Uso no notebook Jupyter

1. Coloque o arquivo de dados em formato CSV na mesma pasta do notebook e nomeie-o como data.csv.

2. Execute as células do notebook para carregar e processar os dados, gerar gráficos e exibir os resultados.

3. Os resultados da preparação para a aposentadoria serão exibidos no notebook e também serão salvos em um novo arquivo new_scenario.csv.

4. Além disso, os gráficos serão exibidos nas células do notebook.

## Configuração

Você pode ajustar os seguintes parâmetros do programa no trecho de código principal (`main()`):

- `max_match_amount`: Valor máximo de contrapartida do Saver's Match.
- `income_threshold`: Limite de renda para ser elegível ao Saver's Match.
- `retirement_age`: Idade de aposentadoria.
- `inflation_rate`: Taxa de inflação anual.
- `start_year`: Ano inicial da simulação.