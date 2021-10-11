# Descrição do problema.
* Criação de um modelo de regressão para prever as notas de matemática para o desavio AceleraDev Data Science admistrado pela Codenation que atinja um R² de no mínimo de 0.9.

# Etapas do projeto.
* Conhecendo a estrutura dos datasets de treinamento e teste.
* Tratamento dos dados faltantes. 
* Descrição dos dados e seleção de variáveis.
* Treinamento dos modelos.
* Buscando os melhores parâmetros.
 
# Resultados.
 
- Pelas análises dos dados obtidos foram selecionadas as variáveis que contêm as notas das outras modalidades, já que foram elas que obteve as maiores correlações com o Target. Se fosse implementado o modelo de machine learning desenvolvido o uso das variáveis escolhidas causaria um problema claro de vazamento de dados.
 
- No trabalho foi avaliado um modelo baseado em regressão linear, knn, floresta aleatória e o XGB. Cada um deles foram treinados e avaliados pela validação cruzada, as métricas utilizadas para avaliar o desempenho de cada um foram o R² e o MSE. Aquele que apresentou o melhor resultado foi XGB com R² 0.921 e desvio padrão 0.003 e um MSE 4086 e desvio padrão de 118.

