#  SMS Text Classification

Este projeto implementa um classificador de mensagens SMS para distinguir entre mensagens legítimas ("ham") e mensagens de spam. Utiliza uma rede neural simples construída com TensorFlow e Keras, processando os dados através de técnicas de codificação e padding.

##  Tecnologias Utilizadas

- **Python** - Linguagem de programação principal
- **TensorFlow/Keras** - Framework para machine learning
- **Pandas** - Manipulação de dados
- **NumPy** - Operações matemáticas
- **Matplotlib** - Visualização de dados
- **TensorFlow Datasets** - Biblioteca para manipulação de conjuntos de dados

##  Estrutura do Projeto

1. **Coleta de Dados**: Os conjuntos de dados de treino e validação são baixados e carregados em `pandas.DataFrame`.
2. **Pré-processamento**:
   - Tokenização das mensagens
   - Criação de um dicionário de vocabulário
   - Codificação das mensagens com `one_hot`
   - Padding das sequências para garantir o mesmo comprimento
3. **Criação do Modelo**:
   - Camada de embedding para representação vetorial das palavras
   - Camada `Flatten` para transformar os embeddings em um vetor unidimensional
   - Camada `Dense` final com ativação `sigmoid` para classificação binária
4. **Treinamento do Modelo**:
   - Utiliza `EarlyStopping` para evitar overfitting
   - Otimização com `adam` e função de perda `binary_crossentropy`
5. **Predição**:
   - Implementação da função `predict_message()` para classificar novas mensagens
   - Teste automático de predições com mensagens conhecidas

##  Instalação e Execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências necessárias:
   ```sh
   pip install tensorflow-datasets pandas numpy matplotlib tensorflow
   ```
3. Execute o script principal:
   ```sh
   python fcc_sms_text_classification.py
   ```
4. Teste a predição de mensagens personalizadas modificando `pred_text`.

##  Roadmap

- [ ] Melhorar a eficiência do modelo com arquiteturas mais complexas
- [ ] Implementar técnicas de pré-processamento mais avançadas (remoção de stopwords, stemming, etc.)
- [ ] Criar uma interface gráfica para facilitar o uso do classificador

##  Licença

Este projeto segue a licença MIT.

## Referências

- [freeCodeCamp](https://github.com/freeCodeCamp)  
- [Mephistopheles-0](https://github.com/Mephistopheles-0)
