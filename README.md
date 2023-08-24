# Imoveis-

Regressão Linear com Dados de Imóveis
Este repositório contém um exemplo simples de como realizar uma análise de regressão linear utilizando a biblioteca scikit-learn e statsmodels em Python. O objetivo é entender como a área de um imóvel pode influenciar o seu preço.

Pré-requisitos
Certifique-se de ter as seguintes bibliotecas instaladas em seu ambiente:

pandas
numpy
seaborn
scikit-learn
statsmodels
Passos do Código
Carregar Dados: Os dados são carregados a partir do arquivo "Cópia de imoveis.xlsx" usando a biblioteca pandas.

Análise Descritiva dos Dados: Uma descrição estatística dos dados é exibida para entender melhor as características dos imóveis.

Visualização de Dados: Histogramas e gráficos de dispersão são utilizados para visualizar a distribuição e correlação entre as variáveis "área" e "preço".

Normalização dos Dados: Os dados são normalizados utilizando o MinMaxScaler da scikit-learn.

Regressão Linear com statsmodels: É realizado um ajuste de regressão linear usando a biblioteca statsmodels. A relação entre "área" e "preço" é modelada e os resultados estatísticos são exibidos.

Divisão dos Dados: Os dados normalizados são divididos em conjuntos de treino e teste.

Regressão Linear com scikit-learn: Uma regressão linear é ajustada aos dados de treino usando o LinearRegression da scikit-learn.

Avaliação do Modelo: O coeficiente de determinação (R-squared) é calculado para avaliar o desempenho do modelo nos dados de treino.

Previsões e Métricas: Previsões são feitas nos conjuntos de treino e teste, e métricas como MAE (Erro Médio Absoluto), MSE (Erro Quadrático Médio) e RMSE (Raiz Quadrada do Erro Quadrático Médio) são calculadas.

Como Usar
Certifique-se de ter instalado as bibliotecas listadas nos pré-requisitos.
Execute cada bloco de código sequencialmente em um ambiente Python.
Os resultados, gráficos e métricas serão exibidos conforme o código é executado.
