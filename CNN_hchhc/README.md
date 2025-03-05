# Implementação de Rede Neural Convolucional (CNN) com PyTorch

Este projeto tem como objetivo implementar uma Rede Neural Convolucional (CNN) personalizada usando PyTorch, além de experimentar com modelos pré-treinados utilizando transfer learning. O modelo é treinado no dataset MNIST.

## Estrutura do Projeto

- `Notebook/`: Contém o notebook Jupyter para a implementação e análise da CNN.

## Dependências

As principais bibliotecas utilizadas neste projeto são:
- numpy
- matplotlib
- jupyter
- torch
- torchvision
- seaborn
- optuna
- cv2

## Como Executar

1. Clone o repositório.
2. Instale as dependências listadas no arquivo `requirements.txt`.
3. Navegue até o diretório `Notebook/` e abra o notebook `CNN(hchhc).ipynb` com Jupyter Notebook.
4. Execute as células do notebook para treinar e avaliar o modelo CNN.

## Datasets

O dataset MNIST é utilizado para treinar e avaliar o modelo. Ele é baixado automaticamente pelo código e armazenado em um diretório  que ele cria e que se chama `data/`.

## Observações

Esta atividade foi desenvolvida como parte do curso IF867 - Introdução à Aprendizagem Profunda 2024.2. O objetivo é desenvolver um modelo CNN de aprendizagem profunda e comparar seu desempenho com modelos pré-treinados.