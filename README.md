# disney_recommendation (Sistema de Recomendação para Filmes e Shows da Disney)

O Disney Plus é uma plataforma de streaming que possui uma vasta quantidade de títulos de filmes e shows disponíveis para os usuários.

Contextualização: O objetivo é criar um sistema de recomendação para shows e filmes no Disney Plus, e melhorar a experiência dos usuários de forma eficiente, ajudando-os a descobrir novos conteúdos de seu interesse.

Problema Abordado: Ajudar os usuários a descobrir novos conteúdos que possam gostar, melhorando a experiência de uso da plataforma.

Como podemos recomendar filmes e shows da Disney que atendam aos interesses dos usuários?
- Entendendo o comportamento dos dados;
- Desenvolvendo um modelo de recomendação;
- Melhorando a satisfação do usuário.

Fonte do Dataset: https://www.kaggle.com/datasets/victorsoeiro/disney-tv-shows-and-movies/data?select=titles.csv
Critérios de Seleção: Seleção de filmes e shows com base em popularidade, gênero, classificações, título, Ano de Lançamento, Nota dos Usuários.

Data Wrangling Processo: Limpeza de dados, tratamento de valores nulos, transformação de variáveis categóricas
Ferramentas Utilizadas: Pandas, NumPy, matplotlib, seaborn, sklearn

Análise Exploratória de Dados (EDA)
- Análise Univariada: Distribuição das classificações, contagem de gêneros, etc.
- Análise Bivariada: Correlação entre classificações e gêneros, etc.
- Análise Multivariada: Análise de componentes principais (PCA) para redução de dimensionalidade.

Filtros e Distribuição
-Filtros Aplicados: Remoção de filmes/shows com poucas classificações, seleção de gêneros mais populares, etc.
-Distribuição dos Dados: Gráficos mostrando a distribuição de classificações, gêneros, ano de Lançamento, Nota dos Usuários

Métricas de Desempenho
- Precisão, recall, F1-score, etc

Modelo de recomendaação simples: RandomForestClassifier
 "O Random Forest é um modelo de ensemble que combina múltiplas árvores de decisão para melhorar a precisão e a robustez do modelo. O RandomForestClassifier é uma escolha sólida, ele é eficaz para conjuntos de dados que contêm tanto variáveis categóricas quanto numéricas e é conhecido por ser resistente ao overfitting, especialmente em problemas de classificação."

 Por que o Random Forest?
Robustez: é menos suscetível ao overfitting em comparação com uma única árvore de decisão.
Versatilidade: Funciona bem com dados categóricos e numéricos
Interpretabilidade: A importância das features pode ser facilmente extraída e interpretada.
