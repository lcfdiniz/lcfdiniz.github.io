---
title: "Predição de Churn para Clientes de Banco"
excerpt: "Projeto de classificação para predição de churns<br/><img src='/images/bank-customer-churn.jpg'>"
collection: portfolio
---

A taxa de churn (churn rate) é uma métrica que aponta a rotatividade dos clientes de uma empresa, ou de forma mais direta, o número de clientes que deixaram de fazer negócios com a empresa em um determinado período de tempo. O investimento na predição de churn e consequente retenção de clientes é extremamente eficiente, dado que o custo para se adquirir um novo cliente pode ser de 5 a 7 vezes maior do que manter um atual [[1]](https://jrs.digital/conquistar-um-novo-cliente-custa-entre-5-a-7-vezes-mais-que-manter-um-atual/).

Sendo assim, este projeto propõe uma análise de dados nos âmbitos descritivo, diagnóstico e preditivo, buscando entender os fatores que determinam a evasão de clientes e construir um modelo de aprendizado de máquina capaz de prever aqueles com maiores probabilidades de se tornarem churn.

Como resultados, foi possível obter um modelo de alto desempenho, avaliado por sua métrica de F5-Score superior a 0.99. Ainda foi possível identificar a variável `Complain`, que indica a existência de uma reclamação anterior por parte do cliente, como determinante para o mesmo se tornar ou não churn.

![bank-customer-churn](/images/bank-customer-churn-picture-1.png)
*Importância dos atributos para o conjunto de dados avaliado*

[Link para o repositório no GitHub](https://github.com/lcfdiniz/puc-rio/tree/main/bank-customer-churn)
