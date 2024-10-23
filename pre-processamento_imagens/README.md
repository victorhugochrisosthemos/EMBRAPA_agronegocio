# Pré-Processamento de Imagens

- A fim de melhorar a precisão e a confiabilidade das imagens, é necessário melhorar a qualidade das imagens antes de manipulá-las com algoritmos de IA
- Passos do pré-processamento são: redimensionamento, normalização, remoção de ruído, segmentação, extração de características, augmentation e codificação
- Aplicações do pré-processamento são: reconhecimento de objetos, detecção de rosto, diagnóstico médico

### Redimensionamento
- Adequar as imagens a um tamanho padronizado no dataset

### Normalização
- Ajuste dos pixels de uma imagem para valores entre 0 e 1, é necessário para facilitar o treinamento na medida em que todas as imagens estão na mesma escala

### Remoção de ruído
- São imagens que não fazem parte de nenhum grupo a ser definido, suas existência no dataset pode gerar inconsistências
- É utilizado técnicas para remover essas imagens:
    - Filtragem mediana
    - Filtragem gaussiana
    - Filtragem bilateral

### Segmentação
- Divide a imagem em partes que facilitem a extração de um objeto
- Técnicas utilizadas:
    - Segmentação por detecção de bordas
    - Segmentação por crescimento de região
    - Segmentação baseada em limiar

### Extração de características
- Identificar e selecionar quais objetos da imagens serão relevantes

### Augmentation
- Criação de novas imagens a partir das originais para aumentar a quantidade de dados para treinamento
- Utiliza certas técncias: zoom, rotação, espelhamento

### Codificação
- Adequar as imagens a um tamanho requisitado pelo modelo de aprendizagem de máquina

## Dúvidas sobre o assunto
- Como aumentar o realce de contraste para diferenciar plantas com morfologias parecidas em imagens?
  - Ler um pouco sobre esses tópicos:
    - Equalização de histogramas
    - Aplicação do método CLAHE
    - Utilizar curvas de nível para diferenciar tonalidades semelhantes mas não iguais
    - Segmentação de cores
    - Transformações de cores
    - Filtros de detecção de bordas
    - Algoritmo de Watershed
    - Filtro de Gabor
    - Análise de textura com Haralick
    - Sharpness/Unsharp Masking
    - High-pass filter
    - Análise Multiespectral
    - Machine Learning/Deep Learning

- Qual é o valor mínimo de imagens para gerar um aprendizado e máquina eficiente?

## Sites de leitura inicial sobre o assunto
- [O que é Image Preprocessing?](https://glossario.maiconramos.com/glossario/o-que-e-image-preprocessing-pre-processamento-de-imagens-em-ia/)

- [Pré-Processamento de Imagens para Visão Computacional](https://medium.com/@denise_marti/pr%C3%A9-processamento-de-imagens-abb25cc48eb4)

- [As 3 etapas do processamento de imagens](https://adenilsongiovanini.com.br/blog/processamento-de-imagem-as-3-etapas/)

- [Etapas do Processamento de Imagens](https://1library.org/article/pr%C3%A9-processamento-etapas-do-processamento-de-imagens.y83pw9wq#google_vignette)
