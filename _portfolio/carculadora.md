---
title: "CARculadora"
excerpt: "Projeto de regressão para predição de preços de veículos<br/><img src='/images/carculadora.jpg'>"
collection: portfolio
---

Este projeto foi entregue como trabalho de conclusão de curso do bootcamp em Data Science & Machine Learning da [Tera](https://somostera.com/). Como objetivo, estava o desenvolvimento de uma ferramenta para predição de preço de veículos usados e seminovos, utilizando um modelo de regressão.

Para a aquisição dos dados, foi realizado um web scraping em um famoso portal de compra e venda de veículos. Os dados foram analisados em detalhes, buscando extrair as relações mais significativas entre as variáveis. Em seguida, os mesmos dados passaram por um criterioso processo de limpeza e pré-processamento, permitindo seu treinamento por um modelo de aprendizado de máquina. 

O método *Random Forest Quantile* foi utilizado, permitindo prever os preços com intervalos máximos e mínimos. Os seguintes resultados foram verificados para o conjunto de teste:

* Um erro **341 reais** menor que o da tabela Fipe, por automóvel;
* Um erro **187 mil reais** menor que o da tabela Fipe, para os 549 veículos da base de teste;
* **91%** dos valores previstos dentro dos intervalos determinados pelo modelo.

![carculadora](https://miro.medium.com/max/700/1*_8fdBbZfpwTGIUq_Wl7a4Q.gif)
*Deploy da aplicação utilizando o Streamlit*

[Link para o repositório no GitHub](https://github.com/lcfdiniz/carculadora)
