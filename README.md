# Car Price Prediction
Projeto envolvendo conceitos de Machine Learning para predição de preços de carros usados.

## Work Flow
<img src="graphs/Work Flow - Car Price Prediction (1).png" alt="Work Flow" width="1000"/>

## Sobre o projeto
<p>Este projeto foi feito para iniciar meus estudos na área de Machine Learning. Para realizá-lo, me baseei em um vídeo do YouTube e nos meus estudos de estatística e lógica de programação. Os dados importados provém de um site indiano, o que faz com que a moeda utilizada seja a Rupia Indiana.</p>

## Regressão Linear e de Lasso
<p>A regressão linear foi usada no projeto porque permite modelar a relação entre o preço (variável dependente) e fatores como idade do carro, quilometragem, marca, entre outros (variáveis independentes). A técnica ajuda a identificar padrões e estimar o valor do carro com base em características observáveis. Sendo uma abordagem simples e interpretável, é útil para entender como diferentes variáveis influenciam o preço e prever valores futuros com base em dados históricos.</p>
<p>A regressão Lasso foi usada no projeto para melhorar a precisão do modelo e lidar com conjuntos de dados com muitas variáveis. O Lasso (Least Absolute Shrinkage and Selection Operator) adiciona uma penalidade aos coeficientes das variáveis menos importantes, forçando alguns deles a zero, o que efetivamente realiza uma seleção de atributos. Isso é útil para simplificar o modelo, reduzir o risco de overfitting e aumentar a interpretabilidade, ao focar nas características mais relevantes que influenciam o preço do carro.</p>

## Gráficos e resultados obtidos
<h4>Gráficos - Regressão Linear</h4>
<p align="center">
  <img src="graphs/Lin1.png" alt="Gráfico Linear 1" width="300">
  <img src="graphs/Lin2.png" alt="Gráfico Linear 2" width="300">
</p>
<p>Nesses gráficos, já é notável que a distância entre os pontos é pequena, mas que tende a aumentar conforme os preços vão ficando mais altos.</p>
<h4>Gráficos - Regressão de Lasso</h4>
<p align="center">
  <img src="graphs/Lasso1.png" alt="Gráfico de Lasso 1" width="300">
  <img src="graphs/Lasso2.png" alt="Gráfico de Lasso 2" width= "300">
</p>
<p>Agora, utilizando a Regressão de Lasso, é nítida a mudança na distância entre os pontos. Os resultados de predição obtidos pelo modelo se assemelham mais ainda aos preços reais.</p>

## Tecnologias utilizadas
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
