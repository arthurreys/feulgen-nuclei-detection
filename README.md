# Automação de Avaliação de Núcleos Celulares

Esse repositório se dedica aos arquivos relacionados ao projeto final da disciplina de Visão Computacional, do Programa de Mestrado em Ciência da Computação da Universidade Federal de Santa Catarina.

O objetivo do projeto é detectar núcleos celulares em imagens de microscopia, pigmentados com coloração de Feulgen, e classificá-los em 8 categorias distintas. Para tal, duas diferentes abordagens foram utilizadas: uma com ferramentas clássicas de visão computacional, e outra via fine-tuning de YOLO v8, uma rede neural consolidada na tarefa de detecção de objetos.

## Instruções
Os notebooks podem ser executados individualmente, sem qualquer instalação adicional, no Google Colab. Para tal, abra o arquivo e clique no link "Open in Colab".

- Ferramentas clássicas de visão computacional: Disponível em `notebooks/Abordagem_Clássica.ipynb`.
- Redes Neurais - YOLOv8: Disponível em `notebooks/YOLO_Detecção_Objetos.ipynb`.

No diretório `models` encontra-se o modelo treinado YOLO serializado, além de outros arquivos gerados durante o treinamento.

## Apresentação

O vídeo de apresentação do trabalho está disponível em https://youtu.be/6FSSrGn45xQ.

## Dataset

O Dataset utilizado pode ser baixado em https://arquivos.ufsc.br/d/7e7ac2f498df4cf9aa7d/. Não é necessário fazer download do dataset para executar os notebooks.

## Exemplo predições modelo YOLOv8

O exemplo abaixo mostra duas imagens do conjunto de teste e as respectivas predições do modelo YOLOv8. Mais exemplos (incluindo perdições da abordagem clássica) estão disponíveis nos notebooks.

![plot](./assets/yolo_result.png)