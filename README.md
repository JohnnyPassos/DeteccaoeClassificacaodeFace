# Projeto de Reconhecimento Facial com TensorFlow

Este projeto faz parte do desafio final do Bootcamp de Machine Learning da plataforma DIO em parceria com a Baires Dev.

## Sobre o Projeto
[cite_start]O objetivo principal foi trabalhar com as bibliotecas e frameworks estudados nas aulas[cite: 2]. [cite_start]A proposta padrão envolvia a criação de um sistema de detecção e reconhecimento de faces/rostos, utilizando o framework TensorFlow[cite: 3]. [cite_start]O resultado esperado era um modelo capaz de detectar e reconhecer mais de uma face simultaneamente em uma imagem[cite: 4].

Para isso, o sistema foi construído utilizando duas redes principais:
* [cite_start]Uma rede de detecção treinada para localizar as faces[cite: 6].
* [cite_start]Uma rede de classificação para classificar cada face detectada[cite: 7].

## Tecnologias e Redes Neurais Utilizadas
* **Framework:** TensorFlow
* **Linguagem:** Python
* **Ambiente:** Kaggle Notebooks
* **Rede de Detecção:** MTCNN
* **Rede de Classificação (Extrator de Características):** EfficientNetV2, pré-treinado em ImageNet
* **Classificador:** Support Vector Machine (SVM) do Scikit-learn
* **Bibliotecas:** OpenCV, NumPy e Pillow

## Dataset e Resultados
Foi utilizado um dataset próprio com aproximadamente 99 imagens, divididas entre 3 pessoas: Cicero, Jessi e Johnny.

O sistema foi bem-sucedido em detectar e classificar as faces/rostos conhecidos. Para o desafio, alcançamos o objetivo de criar um sistema funcional para este conjunto de dados.

É importante notar que, para diferenciar com eficiência os rostos conhecidos de outros rostos desconhecidos, é fundamental treinar a base de dados com exemplos de faces desconhecidas.

## Exemplo de Resultado
*(Recomendado: Adicione a imagem do resultado aqui, seguindo as instruções que conversamos anteriormente.)*

![Resultado do Reconhecimento Facial] __results___5_1.png
