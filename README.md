# Projeto de Estatística Descritiva — Base de Supermercado

Projeto prático desenvolvido para aplicação de conceitos de estatística descritiva (média, mediana, desvio padrão, identificação de outliers) e visualizações de dados com Python (Pandas, Seaborn, Matplotlib e Plotly).

##  Principais Resultados

- **Média e Mediana por Categoria**: A maioria das categorias apresentou distribuição assimétrica à direita (média superior à mediana), impulsionada por produtos de maior valor.
- **Maior Desvio Padrão**: A categoria **`lacteos`** apresentou a maior variabilidade de preços ($\text{std} \approx 3925.82$), com diferença acentuada entre média ($\text{CLP } 2385.22$) e mediana ($\text{CLP } 989.00$).
- **Outliers**: Foram identificados 43 outliers na categoria `lacteos`, correspondendo principalmente a *packs* com 12 unidades de leite e leites em pó especiais de maior peso.
- **Descontos**: A categoria **`congelados`** obteve a maior média de desconto concedida aos clientes.

##  Tecnologias Utilizadas

- **Python 3**
- **Pandas** (manipulação de dados)
- **Matplotlib & Seaborn** (visualizações estáticas: Boxplot e Barras)
- **Plotly Express** (mapa interativo Treemap salvo em HTML)

##  Estrutura do Repositório

- `Profissao Cientista de Dados M13 Projeto.ipynb`: Notebook com o código-fonte completo.
- `boxplot_outliers.png`: Boxplot da distribuição de preço da categoria lácteos.
- `barras_desconto_medio.png`: Gráfico de barras com a média de descontos por categoria.
- `mapa_interativo_desconto.html`: Gráfico interativo em HTML agrupando Categoria, Marca e Desconto Médio.
