# disney_recommendation (Sistema de Recomendação para Filmes e Shows da Disney)

O Disney Plus é uma plataforma de streaming que possui uma vasta quantidade de títulos de filmes e shows disponíveis para os usuários.

Contextualização: O objetivo é criar um sistema de recomendação para shows e filmes no Disney Plus, e melhorar a experiência dos usuários de forma eficiente, ajudando-os a descobrir novos conteúdos de seu interesse.

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

# Sistema de Recomendação para Filmes e Shows da Disney

## Descrição do Projeto

Este projeto desenvolve um sistema de recomendação para filmes e shows da Disney, utilizando técnicas de machine learning e análise exploratória de dados (EDA).

## Instalação das Dependências

Para instalar as dependências necessárias para este projeto, siga os passos abaixo:

1. Clone o repositório para a sua máquina local:
    ```bash
    git clone https://github.com/seu_usuario/seu_repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd seu_repositorio
    ```

3. Crie um ambiente virtual (opcional, mas recomendado):
    ```bash
    python -m venv env
    source env/bin/activate  # No Windows use `env\Scripts\activate`
    ```

4. Instale as dependências a partir do arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

Agora, todas as dependências necessárias devem estar instaladas no seu ambiente.

## Como Executar o Notebook

1. Certifique-se de que você instalou todas as dependências seguindo as instruções acima.

2. Inicie o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

3. No navegador, abra o arquivo `nome_do_notebook.ipynb` que está localizado no diretório do projeto.

4. Execute todas as células do notebook para reproduzir as análises e resultados.

## Sumário dos Principais Resultados e Conclusões

### Resultados da Análise Exploratória de Dados (EDA)

- **Distribuição das Notas:** A maioria dos filmes e shows tem notas altas, indicando uma recepção geralmente positiva.
- **Distribuição dos Gêneros:** Os gêneros mais comuns são [Gênero 1, Gênero 2, etc.], mostrando a diversidade de conteúdos disponíveis.
- **Correlação entre Variáveis:** Observamos correlações significativas entre variáveis como gênero e nota, o que ajudou a informar o modelo de recomendação.

### Resultados do Modelo de Recomendação

- **Modelo Utilizado:** Utilizamos o algoritmo K-Nearest Neighbors (KNN) para criar o sistema de recomendação.
- **Desempenho do Modelo:** O modelo foi capaz de identificar filmes e shows similares com base nas notas e gêneros, oferecendo recomendações precisas e relevantes.

### Conclusões

- O sistema de recomendação desenvolvido demonstrou ser eficaz na sugestão de conteúdos aos usuários com base em suas preferências.
- A Análise de Componentes Principais (PCA) ajudou a reduzir a dimensionalidade dos dados, facilitando a visualização e a interpretação dos resultados.
- As próximas etapas incluem o ajuste fino dos hiperparâmetros do modelo e a experimentação com outros algoritmos de recomendação para potencialmente melhorar ainda mais a precisão.

### Próximos Passos

- Implementar personalização adicional no sistema de recomendação, levando em conta mais características dos usuários.
- Explorar outros algoritmos de recomendação, como modelos baseados em filtragem colaborativa ou redes neurais.
- Continuar a otimizar e validar o modelo com mais dados à medida que estiverem disponíveis.

## Referências

- [Link para o dataset](https://www.kaggle.com/code/shivamb/disney-shows-and-movies-exploratory-analysis/notebook)
- Documentação das bibliotecas utilizadas: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

