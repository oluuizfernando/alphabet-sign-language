# Reconhecimento de Alfabeto em Linguagem de Sinais

Este é um projeto em Python que utiliza a biblioteca MediaPipe, OpenCV, NumPy e Keras para reconhecer letras do alfabeto da linguagem de sinais através da câmera.

## Funcionalidades

- **Detecção de Mão com MediaPipe:** Utiliza o MediaPipe para detectar a mão em tempo real na câmera.
- **Reconhecimento de Gestos:** Identifica gestos da mão para determinar qual letra do alfabeto em linguagem de sinais está sendo feita.
- **Classificação com Keras:** Utiliza um modelo de aprendizado profundo (deep learning) implementado com Keras para classificar os gestos das mãos em letras específicas.

## Pré-requisitos

- Python 3.x
- Bibliotecas necessárias: OpenCV, MediaPipe, NumPy, Keras

## Instalação

1. Clone este repositório:

   ```bash
   https://github.com/oluuizfernando/alphabet-sign-language.git

2.Instale as dependências:

  pip install -r requirements.txt

## Uso

Execute o script principal:

python main.py

Aponte a câmera para uma mão com a intenção de formar letras em linguagem de sinais.

O sistema irá identificar a letra correspondente com base nos gestos detectados.

## Contribuição
Contribuições são bem-vindas! Para mudanças importantes, abra primeiro uma issue para discutir o que você gostaria de mudar.
