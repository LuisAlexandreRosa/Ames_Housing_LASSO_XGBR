## Ames_Housing_LASSO_XGBR
Modelo preditivo com LASSO Regression e XGBRegressor utilizando o Ames Housing dataset
Public Score: 0.19607
Neste modelo utilizei LASSO e XGBRegressor juntos, mas com pesos diferentes para cada previsão:
No original (https://www.kaggle.com/code/apapiu/regularized-linear-models) o autor atribui peso 0.7*LASSO + 0.3*XGBRegressor
No meu dataset, com pré-processamento de dados diferente, os seguintes pesos funcionaram melhor: 0.3*LASSO + 0.7*XGBRegressor
O resultado final foi um Public Score melhor que meu modelo utilizando somente LASSO, mas pior que o modelo utilizando somente XGBRegressor.
