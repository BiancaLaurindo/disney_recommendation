# disney_recommendation (Sistema de Recomendação para Filmes e Shows da Disney)

Este projeto tem como objetivo desenvolver um sistema de recomendação para a plataforma Disney+, melhorando a experiência do usuário ao ajudá-lo a descobrir novos programas e filmes de seu interesse. Atualmente, devido à vasta biblioteca disponível, os usuários podem ter dificuldade em encontrar conteúdo que corresponda às suas preferências pessoais. Um sistema de recomendação eficaz pode não apenas aumentar o engajamento do usuário, mas também melhorar a satisfação geral, facilitando a descoberta personalizada de conteúdo relevante.

Como podemos recomendar filmes e shows da Disney que atendam aos interesses dos usuários?
- Entendendo o comportamento dos dados;
- Desenvolvendo um modelo de recomendação baseado em filtragem de conteúdo
- Critérios de Seleção: Seleção de filmes e shows com base em popularidade, gênero, classificações, título, Ano de Lançamento, Nota dos Usuários.

Dataset
O conjunto de dados utilizado contém 1.535 entradas e 15 colunas, incluindo detalhes como ID do título, tipo, título, país, elenco, data de adição, diretores, classificações, ano de lançamento e duração. Estes dados foram utilizados para treinar o modelo de recomendação.

Colunas Principais:
id: ID do título no JustWatch
title: Nome do título
show_type: Tipo de conteúdo (Série ou Filme)
description: Descrição breve do conteúdo
release_year: Ano de lançamento
age_certification: Classificação indicativa
runtime: Duração do episódio ou filme
genres: Lista de gêneros
production_countries: Países produtores do título
imdb_id: ID no IMDB
imdb_score: Pontuação no IMDB
tmdb_popularity: Popularidade no TMDB
tmdb_score: Pontuação no TMDB

Fonte do Dataset: https://www.kaggle.com/datasets/victorsoeiro/disney-tv-shows-and-movies/data?select=titles.csv

Data Wrangling
Os dados foram carregados e preparados, removendo valores nulos e limpando colunas como genres (gêneros) e production_countries (países de produção). 

Foram realizadas as seguintes etapas de limpeza:
Gêneros e Países de Produção: Remoção de caracteres desnecessários e seleção do primeiro gênero e país na lista, mantendo apenas um por título.
Remoção de Linhas e Colunas: Remoção de duplicatas e valores nulos em colunas críticas. Substituição de valores nulos em colunas numéricas por zero.
Preenchimento de Valores Faltantes: Substituição dos valores faltantes na coluna age_certification (classificação indicativa) com base na distribuição das certificações por gênero.

Análise Exploratória de Dados (EDA)
Distribuição de Anos de Lançamento: A maioria dos títulos foi lançada a partir do ano 2000, com um pico em torno de 2020.
Distribuição de Duração: A duração dos títulos varia, com picos em torno de 25 minutos e 100 minutos, sugerindo diferentes formatos de conteúdo.
Distribuição de Tipos (Filme ou Série): A maioria dos títulos é de filmes.
Popularidade e Avaliação: A popularidade é altamente assimétrica, com poucos títulos extremamente populares. A avaliação segue uma distribuição mais normal.
Gêneros: Gêneros como comédia e família são os mais comuns.
Países de Produção: A maioria dos títulos é produzida nos Estados Unidos.
Classificação Indicativa: A classificação mais comum é G, adequada para todos os públicos.
