# Projeto de Reconhecimento Facial com TensorFlow

Este projeto faz parte do desafio final do Bootcamp de Machine Learning da plataforma DIO em parceria com a Baires Dev.

## Sobre o Projeto
O objetivo principal foi trabalhar com as bibliotecas e frameworks estudados nas aulas. A proposta padrão envolvia a criação de um sistema de detecção e reconhecimento de faces/rostos, utilizando o framework TensorFlow. O resultado esperado era um modelo capaz de detectar e reconhecer mais de uma face simultaneamente em uma imagem.

Para isso, o sistema foi construído utilizando duas redes principais:
* Uma rede de detecção treinada para localizar as faces.
* Uma rede de classificação para classificar cada face detectada.

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

<img width="841" height="658" alt="__results___5_1" src="https://github.com/user-attachments/assets/6431258d-bb69-40a8-9ba9-e8ca432c7682" />

