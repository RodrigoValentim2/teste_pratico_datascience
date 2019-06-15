# Introdução
  Este desafio consiste em classificar os trechos de textos opinativos sobre filmes. O objetivo específico é classificar um texto em 5 sentimentos: **negativo, um pouco negativo, neutro, um pouco positivo e positivo**. Neste projeto foram testados os classificadores: **LSTM, LinearSVC, MultinomialNB e LogisticRegression**. Os classificadores foram treinados utilizando validação cruzada K-fold com repetição de duas vezes. Por fim, foi feito um teste de Friedman para comparar os classificadores. 

# Metodologia
+ **pré processamento dos dados**
+ **Aplicação dos algoritmos**
+ **Avaliação e comparativo dos algoritmos**

# Resultados
+ **pré processamento**
  + **Limpeza dos dados**
  + **Geração de nuvens de palavras e gráficos com as palavras mais frequentes**. 
+ **Gerou-se dois datasets dos dados**:
  + **No primeiro não foi analisada a coluna IdSentenca**
  + **No segundo todos os dados com o mesmo IdSentenca foram concatenados**
# Aplicação dos Algoritmos
+ **Escolha dos algoritmos**
    + **LSTM, LinearSVC, MultinomialNB e   LogisticRegression**
+ **Métodos**
    + **Bag of words**
    + **Tokenization**

# Comparativo dos Modelos
+ **Avaliação**
  + **Acurácia obtidas pelos os modelos**
    + **LSTM: 0.859512**
    + **LinearSVC: 0.637242**
    + **MultinomialNB: 0.622199**
    + **LogisticRegression: .589248**
# Comparativo entre os modelos.
+ **Teste Friedman para  LinearSVC, MultinomialNB e  LogisticRegression. P-value = 0.0000000021**.


