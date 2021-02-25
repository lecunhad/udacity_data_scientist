<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- TABELA DE CONTEÚDOS -->
<details open="open">
  <summary>Sumário</summary>
  <ol>
    <li>
      <a href="#about-the-project">Sobre o Projeto</a>
      <ul>
        <li><a href="#built-with">Frameworks</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Iniciando</a>
      <ul>
        <li><a href="#prerequisites">Pré Requisitos</a></li>
        <li><a href="#installation">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#run">Executando</a></li>
    <li><a href="#usecases">Casos de uso</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contato</a></li>
    <li><a href="#acknowledgements">Referências</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

O objetivo desse projeto é criar um modelo para gerar atas de reuniões automáticas, a partir de transcrições de reuniões gravadas através da aplicação Microsoft Teams 

### Frameworks

Para conseguir rodar o notebook, faz-se necessário a instalação dos principais seguintes frameworks:

* [Transformers](https://github.com/huggingface/transformers)
* [Pytorch](https://pytorch.org/)
* [NLTK](https://www.nltk.org/)
* [Scikit Learn](https://scikit-learn.org/)


<!-- GETTING STARTED -->
## Iniciando

O notebook foi desenvolvido no ambiente [Google Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb)

### Pré-requisitos

Este notebook foi testado em Python 3.7+, PyTorch 1.3.1+ e TensorFlow 2.0.

A biblioteca transformers mais atualizada apresentou bugs, portanto recomenda-se a instalação da versão 3.5
* npm
  ```
  !pip install transformers==3.5
  ```

### Instalação

### Através do PIP


Você deverá instalar Transformers em um [ambiente virtual](https://docs.python.org/3/library/venv.html). 

Primeiramente, crie um ambiente virtual com a versão do Python que você irá utiliazar.

Instale o TensorFlow 2.0 e PyTorch

Assim que o TensorFlow 2.0 e ou PyTorch estiverem instalados, Transformers poderá ser instalado através do comando pip:


1. Clone the repo
   ```
   !git clone https://github.com/huggingface/transformers
   ```
2. Install Transformers
   ```
   %cd transformers
   !pip install
   ```
3. Utilizar a API in de tradução de textos para inglês
   ```
   !pip install googletrans==3.1.0a0
   ```


<!-- RUN -->
## Executando

Para testar a implementação, utilize o código Leandro_Dias_Projeto_Final_Curso_v2.ipynb que está armazenado neste repositório. Você deverá executar os códigos em sequência. Para carregar a base de dados, foi fornecido o arquivo reuniao1.txt


<!-- USECASES -->
## Casos de uso

O foco desse projeto é utilizar técnicas de sumarização para construção de atas de reuniões automáticas. No entanto, as técnicas de sumarização utilizadas podem ser direcionadas para outros casos de uso como sumarização de notícias, textos, etc.


<!-- ROADMAP -->
## Roadmap

Coletar extensa base de dados de reuniões e respectivas atas de reunião para fazer o tuning do modelo e ou treinar um novo.

Utilizar uma pré modelagem para extração apenas de tópicos via clusterização

Utilizar abordagem hibrida extrativa e abstrativa para compor melhor os resumos para cada tópico de entrada


<!-- CONTACT -->
## Contato

[Gmail](lecunhad@gmail.com)

[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/leandro-dias-6a446115a/)


<!-- ACKNOWLEDGEMENTS -->
## Referências

* [Transformers](https://huggingface.co/transformers/)
* [Pegasus](https://arxiv.org/pdf/1912.08777.pdf)
* [Sumarização](https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/)
* [Sumarização com Pegasus](https://chetanambi.medium.com/generate-summaries-using-googles-pegasus-library-772633a161c2)
* [Sumarização de vídeos longos](https://www.researchgate.net/publication/316948434_Semantic_Text_Summarization_of_Long_Videos)
* [Pegasus by Google](https://ai.googleblog.com/2020/06/pegasus-state-of-art-model-for.htm)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

