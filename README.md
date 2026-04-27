# Projeto Fase 6 – Visão Computacional com YOLOv5

## Descrição
Sistema de visão computacional desenvolvido para a Fase 6 do curso de IA da FIAP.
O modelo foi treinado para identificar dois objetos: **livro** e **bolsa de mão**.

## Autora
- **Nome:** Luana Brito
- **RM:** 566632

## Dataset
- 80 imagens no total (40 livros + 40 bolsas)
- Divisão: 32 treino / 4 validação / 4 teste por classe
- Imagens coletadas da internet e fotografadas pela autora

## Entrega 1 – YOLO Customizado
Treinamento do YOLOv5 com dataset próprio de livros e bolsas.
- Dois treinamentos realizados: 30 e 60 épocas
- 6 de 8 imagens de teste detectadas corretamente (75%)

## Entrega 2 – Comparação de Abordagens
Comparação entre três abordagens de visão computacional:
- **YOLO Customizado** – melhor precisão para os objetos escolhidos
- **YOLO Padrão** – confundiu bolsa com mala ("suitcase")
- **CNN do Zero** – 100% de acurácia na classificação, sem localização

## Tecnologias utilizadas
- YOLOv5
- TensorFlow / Keras
- Google Colab
- Python
- MakeSense.ai (rotulação)

## Notebook completo
👉 [Clique aqui para acessar o notebook](LuanaBrito_rm566632_pbl_fase6.ipynb)

## Vídeo demonstrativo
👉 *(link do YouTube será adicionado aqui)*
