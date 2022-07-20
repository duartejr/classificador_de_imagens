# Classificador de Imagens

Este projeto contém dois classificadores de imagens. O primeiro utilizando extração de características e o segundo utilizando fine-tunning.

Em ambos os classificadores foi utilizado o datase de folhas de videira disponível no ![Kaggle](https://www.kaggle.com/datasets/muratkokludataset/grapevine-leaves-image-dataset)

No `classificador_extracao_caracteristicas.ipynb` foi utilizada a CNN VGG-19 para realizar a extração de características e o KNN foi utilizado para realizar a classificação das imagens.
A acurácia deste método ficou 0,54.

No `classificador_fine_tunning.ipynb` também foi utilizada a CNN VGG-19 porém desta vez foi realizado o fine-tuning e adição de camadas para realizar a
classificação das imagens. Com este classificador obteve-se uma acurácia de 0,88. Também foi testado o processo de augmentation para aumentar o número de samples
para teste.
