# Aplicação de CNNs em imagens de "Pedra, Papel e Tesoura"

## Introdução

Este projeto consiste em uma aplicação de Redes Neurais Convolucionais (CNNs) em imagens de mãos representando pedra, papel e tesoura. A aplicação divide-se em três partes principais:

* Parte 1: treinamento de uma CNN **sem** o processo de _Data Augmentation_ (Aumento de Dados) com o dataset [rock_paper_scissors](https://www.tensorflow.org/datasets/catalog/rock_paper_scissors), do catálogo de datasets do TensorFlow;
* Parte 2: treinamento de uma CNN **com** o processo de Data Augmentation usando o dataset rock_paper_scissors;
* Parte 3: testes com a melhor CNN treinada para classificar fotos de mãos fazendo os três gestos (pedra, papel e tesoura).

## Explorando o dataset

O dataset rock_paper_scissors possui, ao todo, 2892 imagens, sendo 964 de cada uma das três classes possíveis. Dentre essas, 2520 são de treinamento e 372 são de teste. Seguem alguns exemplos dessas imagens:

![mao1](imgs/mao1.png "Mão fazendo o gesto de pedra") ![mao2](imgs/mao2.png "Mão fazendo o gesto de papel") ![mao3](imgs/mao3.png "Mão fazendo o gesto de tesoura")

Neste projeto, essas imagens de teste serão usadas como dados de validação. Ou seja, em cada época da etapa de treinamento, o otimizador usado calculará a função de perda (comumente chamada de "loss") usando esses dados de validação e usará isso para atualizar os pesos das CNNs por meio do processo de "backpropagation" (retropropagação).

Com isso, levando em conta que todos os dados serão usados na etapa de treinamento dos modelos, precisaremos de imagens novas para fazer os testes. Essas imagens serão fotos reais de mãos, que eu e meus familiares providenciamos.

## Trabalhando sem data augmentation

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
## Trabalhando com data augmentation

## 

## Links úteis

[GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)

[repository settings](https://github.com/gustavor10silva/CNN-Pedra-Papel-Tesoura/settings/pages)

[documentation](https://docs.github.com/categories/github-pages-basics/)

[contact support](https://support.github.com/contact)
