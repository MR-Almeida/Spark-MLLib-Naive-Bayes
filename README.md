# Spark-MLLib-Naive-Bayes

O intuito deste codigo é mostrar como se aplicar o algoritmo de Naive Bayes através do PySpark, mostrar as bibliotecas, fazer análise exploratória, alguns jeitos de programar para poder fazer a limpeza e o pré-processamento dos dados.

Vai ser utilizado o dataset que diz se aquele email foi um spam ou nao, está disponivel no link https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection. O objetivo será aplicar esse codigo junto com algumas técnicas de PNL para poder identificar/classificar se foi ou nao um SPAM.

### Naive Bayes

#### Descrição

- Baseado no Teorema de Bayes.
- Probabilidade de um Evento A = P(A) é entre 0 e 1.
- A probabilidade P(A/B) = P(A intersect B ) * P (A) /P(B).
- A variável target se torna o evento A.
- O modelo armazena a probabilidade condicional da variável target para cada possível valor das variáveis preditoras.

#### Vantagens
- Rápido e simples
- Funciona bem mesmo com valores missing
- Provê probabilidades de um resultado
- Excelente com variáveis categóricas

#### Desvantagens
- Não funciona bem com muitas variáveis numéricas
- Espera que as variáveis preditoras sejam independentes

#### Aplicação
- Filtro de Spam
- Diagnóstico médico
- Classificação de documentos
