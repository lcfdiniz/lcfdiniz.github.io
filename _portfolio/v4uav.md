---
title: "V4UAV"
excerpt: "Projeto para controle de VANT com visão computacional<br/><img src='/images/v4uav.jpg'>"
collection: portfolio
---

Este projeto foi desenvolvido como parte de minha dissertação de mestrado. Seu objetivo é o desenvolvimento de um sistema de controle, orientação e navegação para um Veículo Aéreo Não-Tripulado (VANT), utilizando técnicas de visão computacional. Este sistema deve permitir que o veículo realize a inspeção das linhas de transmissão de maneira autônoma, além de auxiliar o operador humano no pouso sobre os condutores e/ou cabos para-raio dessas linhas.

A aplicação foi desenvolvida como um pacote ROS (Robot Operating System), sendo composta por diversos nós, tópicos e serviços. Com o auxílio da biblioteca *Tkinter* em linguagem Python, uma interface gráfica do usuário (GUI) simples e amigável foi construída. Um modelo de detecção de objetos baseado na arquitetura **YOLO** e **técnicas clássicas de visão computacional** foram utilizados para identificar cada cabo condutor e para-raio das linhas de transmissão.

Como resultados do projeto, foi visto que o sistema é capaz de realizar a tarefa de rastreamento das linhas de transmissão de forma robusta, mesmo quando exposto a mudanças abruptas na orientação das linhas. Também foi verificado que o sistema reduz boa parte do esforço manual necessário para que um operador realize o pouso sobre as linhas de transmissão. Para mais detalhes, você pode acessar minha dissertação de mestrado [aqui](https://drive.google.com/file/d/12A0chRwYH55cX5iv-3A38wMTLE6BZa7J/view).

![v4uav](/images/v4uav-picture-1.png)

*Resultados dos ensaios de rastreamento realizados*

[Link para o repositório no GitHub](https://github.com/lcfdiniz/v4uav)
