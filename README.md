# analise_EDA

O código em Python realiza a análise de dados relacionados aos preços de combustíveis em 2021, utilizando bibliotecas como Pandas, Matplotlib, Seaborn e Plotly. Ele realiza as seguintes operações:

Carregamento de Dados:

Dois conjuntos de dados referentes aos meses de janeiro e fevereiro são carregados em DataFrames.
Concatenação de Dados:

Os DataFrames são concatenados para formar um único conjunto de dados representando o ano todo.
O DataFrame resultante é salvo em um novo arquivo CSV chamado 'gasolina_2021.csv'.
Visualização de Tendências Temporais:

Os preços de venda de combustíveis ao longo do tempo são visualizados através de um gráfico de linha e um gráfico de barras.
As médias mensais dos preços são apresentadas em ambos os gráficos.
Análise por Região, Tipo de Combustível e Bandeira:

Tabelas pivot são criadas para mostrar o preço médio de cada combustível por região.
A média dos preços de venda é calculada por região, tipo de combustível e bandeira de revendedora.
Identificação de Outliers:

Outliers nos preços de venda são identificados e visualizados através de um diagrama de caixa (boxplot).
Análise Descritiva:

Estatísticas descritivas, como média, mediana e desvio padrão, são calculadas para entender a distribuição dos preços de venda.
Visualização Gráfica:

Histograma e boxplot são criados para visualizar a distribuição dos preços de venda.
Um gráfico de barras mostra o preço médio de venda para cada tipo de combustível.
Visualização de Séries Temporais:

Um gráfico de linha é gerado para visualizar a tendência temporal dos preços de combustíveis ao longo do ano.
O código fornece uma análise abrangente dos dados de preços de combustíveis, explorando tendências temporais, variações regionais e características específicas de diferentes tipos de combustíveis e revendedoras.
