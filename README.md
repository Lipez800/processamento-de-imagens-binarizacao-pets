# Processamento de Imagens: Binarização de Fotos de Animais de Estimação

## 🎯 Descrição do Projeto
Este projeto implementa técnicas de processamento de imagens para converter fotos de gatos e cachorros em diferentes formatos: colorido, escala de cinza e binarizado (preto e branco). Parte do desafio de Processamento Digital de Imagens da Digital Innovation One (DIO).

## 🚀 Tecnologias Utilizadas
- Python 3.x
- NumPy para processamento numérico
- PIL (Pillow) para manipulação de imagens
- Matplotlib para visualização
- Dataset Cats vs Dogs (Microsoft)

## 📊 Funcionalidades Implementadas
- **Conversão RGB para Escala de Cinza**: Utilizando a fórmula de luminância (0.299×R + 0.587×G + 0.114×B)
- **Binarização com Threshold Fixo**: Conversão para preto e branco usando threshold de 127
- **Comparação de Diferentes Thresholds**: Visualização dos efeitos de diferentes valores de corte
- **Processamento Automático do Dataset**: Tratamento em lote das imagens de gatos e cachorros
- **Visualização em 3 Estágios**: Original → Escala de Cinza → Binarizada

# 🎓 Projeto Desenvolvido para Digital Innovation One (DIO)

## 📚 Conceitos Aplicados
- **Binarização**: Técnica de segmentação que converte imagens em preto e branco
- **Thresholding**: Processo de separar objetos do fundo baseado em intensidade
- **Processamento de Pixels**: Manipulação individual de valores de pixel
- **Visualização de Imagens**: Comparação lado a lado dos diferentes estágios

## 🎯 Resultados Esperados
- Conversão precisa de imagens coloridas para escala de cinza
- Binarização eficaz mantendo as características principais dos animais
- Interface visual clara mostrando os três estágios do processamento
