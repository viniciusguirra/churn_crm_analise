# Projeto de Análise de Churn
Este projeto abrange desde a manipulação de dados até a construção e avaliação de um modelo de previsão de Churn (cliente que deixou de utilizar um serviço) usando Python e bibliotecas populares, como Pandas, SQL, Scikit-Learn, Plotly, Streamlit, Sweetviz e outras.

# Objetivo
O objetivo principal deste projeto é analisar o Churn de clientes com base em dados transacionais e de cadastro, identificando padrões e construindo um modelo preditivo para estimar a probabilidade de Churn.

# Etapas do Projeto
## 1. Manipulação de Dados
Fase Inicial: Conexão com o banco de dados usando DBeaver e execução de consultas SQL para entender a estrutura do banco de dados.
Seleção e Join de Tabelas: Seleção das tabelas fato_churn e dim_clientes e execução de consultas SQL para juntar as informações relevantes.
Limpeza e Transformação de Dados: Tratamento de valores nulos, conversão de tipos de dados, e criação de novas variáveis, como a coluna Churn.
## 2. Exploração e Visualização de Dados
Análise Descritiva: Uso de gráficos e estatísticas para entender a distribuição das variáveis.
Visualizações Interativas: Utilização de Plotly Express para criar gráficos interativos, como barras, boxplots e pizza, para visualizar padrões e insights.
Análise de Information Value via Excel: Aplicação de análise de Information Value usando o Excel para avaliar a influência das variáveis no Churn.
Visualização Prévia com Sweetviz: Utilização da biblioteca Sweetviz para gerar visualizações prévias e compreender a distribuição das variáveis.
## 3. Construção do Modelo Preditivo
Feature Engineering: Criação de novas variáveis, como a coluna dias_sem_transacionar.
Preparação dos Dados: Normalização e divisão do conjunto de dados em treino e teste.
Modelo de Regressão Logística: Utilização do Scikit-Learn para criar e treinar um modelo preditivo.
4. Avaliação do Modelo
Avaliação de Desempenho: Utilização de métricas como acurácia, matriz de confusão e relatório de classificação para avaliar o modelo.
Interpretação dos Resultados: Análise dos resultados para entender a capacidade do modelo em prever Churn.
## 5. Apresentação dos Resultados com Streamlit
Criação de Dashboard Interativo: Utilização do Streamlit para criar um aplicativo web interativo que apresenta visualizações e insights do projeto.
Padronização de Cores: Adaptação do código para garantir uma paleta de cores consistente em todos os gráficos.

Este projeto visa proporcionar uma compreensão abrangente do processo de análise de Churn, desde a manipulação de dados até a apresentação dos resultados em um aplicativo interativo, incorporando também análises via Excel e visualizações preliminares com Sweetviz.
