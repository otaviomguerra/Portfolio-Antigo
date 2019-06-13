# Classification Projects:

### [Cancer de Mama](https://github.com/otaviomguerra/Portifolio/tree/master/End-to-End%20ML%20Projects%20in%20Jupyter%20Notebooks/Classification/Cancer%20de%20Mama):
- **Dataset**: O dataset consiste em diversas informações sobre células advindas de tumores malignos e benignos.
- **Objetivo**: O objetivo é analisar as variaveis contidas no dataset e treinar um classificador para prever a que grupo de tumor(Maligno ou Benigno) aquela determinada célula pertence.
- **Resultados**: O Modelo(uma Support Vector Machine com kernel rbf) avaliado com K-Fold cross-validation utilizando 10 folds obteve uma acurácia média de 97,15%.

### [Emprestimos](https://github.com/otaviomguerra/Portifolio/tree/master/End-to-End%20ML%20Projects%20in%20Jupyter%20Notebooks/Classification/Emprestimos%20):
- **Dataset**: O conjunto de dados consiste em diversas informações(gênero, nível de educação etc) sobre clientes de uma compania de empréstimos bem como se suas solicitações de empréstimo foram aprovadas ou não.
- **Objetivo**: O objetivo é analisar as características dos clientes e seus determinados pedidos de empréstimo para prever se os pedidos serão aprovados ou não pela compania.
- **Resultados**: Após avaliados diversos algoritmos foi observado que uma simples Regressão Logística obteve os melhores resultados: Acurácia média utilizando 10-fold cross-validation de 81,75%. Vale ressaltar que o algoritmo obteve tal resultado sem uma otimização de hiperparâmetros.

### [Titanic Challenge](https://github.com/otaviomguerra/Portifolio/tree/master/End-to-End%20ML%20Projects%20in%20Jupyter%20Notebooks/Classification/Titanic):
- **Dataset**: O titanic challenge foi um desafio lançado pelo site kaggle.com para tentar prever os sobreviventes da tragédia do titanic beseando-se em algumas informações sobre os passageiros.
- **Objetivo**: O Objetivo é treinar um classificador que seja capaz de prever o status do passageiro após o acidente(sobrevivente vs não-sobrevivente).
- **Resultados**: Utilizando o algoritmo XGBoost obtemos uma acurácia média de 82,72% sem qualquer otimização de hiperparâmetros.
