# 📩 SMS Text Classification

Este projeto foi desenvolvido com o objetivo de criar um classificador de mensagens SMS que distingue entre spam e mensagens legítimas (ham). O modelo foi construído utilizando Machine Learning e Redes Neurais, aproveitando técnicas de processamento de texto para a classificação automática das mensagens.

O modelo foi treinado para identificar padrões em mensagens de texto utilizando um conjunto de dados contendo exemplos de mensagens spam e ham. Para melhorar a qualidade da representação dos textos, utilizei **one-hot encoding** para transformar as palavras em valores numéricos e **padding** para garantir que todas as sequências tenham o mesmo tamanho.

A estrutura da rede neural inclui:
- **Camada de embedding** para mapear palavras em representações vetoriais densas.
- **Camada Flatten** para transformar os embeddings em um vetor unidimensional.
- **Camada densa final** com ativação **sigmoid** para classificação binária.

Além disso, utilizei a técnica de **Early Stopping**, que interrompe o treinamento quando o desempenho no conjunto de validação para de melhorar, evitando overfitting.

## 📊 Resultado
O modelo foi avaliado utilizando um conjunto de validação e alcançou uma boa precisão na detecção de mensagens spam e ham, demonstrando a eficácia do uso de redes neurais em classificação de texto.

## 📄 Referências
- [freeCodeCamp](https://github.com/freeCodeCamp)  
- [Mephistopheles-0](https://github.com/Mephistopheles-0)

