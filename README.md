# disney_recommendation (Sistema de Recomendação para Filmes e Shows da Disney)

Disney é uma das maiores empresas de entretenimento do mundo, oferecendo uma vasta gama de filmes e shows.

Contextualização: O objetivo é criar um sistema de recomendação para shows e filmes da Disney, e melhorar a experiência dos usuários dessa eficiência, ajudando-os a descobrir novos conteúdos de seu interesse.

Problema Abordado: Ajudar os usuários a descobrir novos conteúdos que possam gostar, melhorando a experiência de uso da plataforma.

Como podemos recomendar filmes e shows da Disney que atendam aos interesses dos usuários?
- Entendendo o comportamento dos dados;
- Desenvolvendo um modelo de recomendação;
- Melhorando a satisfação do usuário.

Fonte do Dataset: https://www.kaggle.com/code/shivamb/disney-shows-and-movies-exploratory-analysis/notebook
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
