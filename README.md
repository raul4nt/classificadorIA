# Classificador de Imagens

Este projeto foi desenvolvido como parte da disciplina de Inteligência Artificial do terceiro semestre. O objetivo é classificar imagens em duas classes: touros (classe 0) e búfalos (classe 1). Para isso, utilizamos a biblioteca TensorFlow com Keras para construir e treinar uma rede neural convolucional (CNN).

## Preparação dos Dados

Os dados de treinamento são organizados em duas subpastas dentro do diretório `data`:

- `data/classe0/`: Contém imagens de touros.
- `data/classe1/`: Contém imagens de búfalos.

Utilizamos a classe `ImageDataGenerator` do Keras para realizar aumentação dos dados e dividir os dados em conjuntos de treinamento e validação.

## Requisitos

- TensorFlow
- Keras
- NumPy
- SciPy

Para instalar os requisitos, execute:

```bash
pip install tensorflow numpy scipy
