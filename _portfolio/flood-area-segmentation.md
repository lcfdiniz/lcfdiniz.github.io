---
title: "Segmentação de Área de Inundações"
excerpt: "Projeto de segmentação semântica de áreas de inundações<br/><img src='/images/flood-area-segmentation.jpg'>"
collection: portfolio
---

Este projeto foi escolhido para o **Prêmio MVP Destaque** [[1]](https://www.linkedin.com/posts/lcfdiniz_ontem-tive-o-prazer-de-participar-do-pr%C3%AAmio-activity-7128865273465483264-GBL-?utm_source=share&utm_medium=member_desktop) do curso de especialização em Ciência de Dados e Analytics da PUC-Rio.

As enchentes e inundações representam um grande desafio para o Brasil, um país com vasta extensão territorial, grandes bacias hidrográficas e condições climáticas diversas. Diferentes fatores contribuem para o aumento do risco de inundações no Brasil, incluindo a urbanização desordenada, mudanças no uso do solo, desmatamento, assoreamento dos rios, falta de infraestrutura adequada e eventos climáticos extremos.

Nesse cenário, o uso de técnicas de inteligência computacional se mostra uma medida promissora, auxiliando comunidades e regiões no enfrentamento e recuperação desses desastres. Sendo assim, esse trabalho propõe o desenvolvimento de um modelo de segmentação semântica de imagens para detecção de áreas de inundação.

Com o uso de técnicas de *data augmentation* e uma arquitetura U-Net, foi possível desenvolver um modelo de alto desempenho, com elevados valores para métricas como a Acurácia de pixel (0.91) e Coeficiente de Dice (0.83). Pela análise visual dos resultados, foi possível constatar que as máscaras de segmentação geradas como saída do modelo em muito se aproximaram dos resultados esperados, levando em conta o conjunto de teste.

![flood-area-segmentation](/images/flood-area-segmentation-picture-1.png)
*Resultados do modelo para uma amostra do conjunto de teste*

[Link para o repositório no GitHub](https://github.com/lcfdiniz/puc-rio/tree/main/flood-area-segmentation)
