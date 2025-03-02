## SMS Spam Classifier

Este projeto foi desenvolvido como parte do currículo "Machine Learning with Python" da freeCodeCamp, com o objetivo de criar um modelo de aprendizado de máquina para classificar mensagens SMS como **"ham"** (mensagens normais de amigos) ou **"spam"** (mensagens de publicidade ou empresas). O modelo foi construído utilizando técnicas de **Machine Learning** e a biblioteca **scikit-learn**.

O conjunto de dados utilizado é o **SMS Spam Collection**, que contém uma coleção de mensagens SMS rotuladas como **"ham"** ou **"spam"**. O desafio do projeto foi treinar um modelo de classificação para prever se uma mensagem SMS é "ham" ou "spam", com base no texto da mensagem.

### Funcionalidade Principal:

Foi criada uma função chamada **predict_message**, que recebe uma mensagem de texto como argumento e retorna uma lista contendo:

1. Um número entre 0 e 1, indicando a probabilidade de ser "ham" (0) ou "spam" (1).
2. A string "ham" ou "spam", dependendo da classificação mais provável para a mensagem.

### Exemplo de execução:

A função **predict_message("Congratulations, you’ve won a prize!")** pode retornar:

```python
[0.15, 'spam']
```

## Resultado

No meu projeto, consegui treinar um modelo de aprendizado de máquina que classifica com precisão as mensagens SMS como **ham** ou **spam**. A função **predict_message** retorna a classificação correta para uma mensagem de entrada.

## Referências

- [freeCodeCamp](https://github.com/freeCodeCamp)  
- [Mephistopheles-0](https://github.com/Mephistopheles-0)
