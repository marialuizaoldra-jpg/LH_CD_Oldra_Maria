# LH_CD_Oldra_Maria_desafio-imdb
# Desafio Ciência de Dados Indicium - Análise de Filmes e notas IMBD

## 1. Sobre o projeto
Este projeto foi desenvolvido como parte de um desafio de Ciência de Dados. O objetivo é explorar dados de filmes do IMDB, realizar análises exploratórias (EDA) e construir um modelo de Machine Learning para prever a nota IMDB de novos filmes.

## 2. Instalação e execução
Passo a passo para rodar o projeto:
1. Clone o repositório:
   git clone https://github.com/marialuizaoldra-jpg/LH_CD_Oldra_Maria.git
   cd LH_CD_Oldra_Maria
## 2. Crie um ambiente virtual e ative-o (Linux/Mac ou Windows).

## 3. Instale as dependências:
   pip install -r requirements.txt
   
## 4. Execute as análises no Jupyter Notebook:
   jupyter notebook notebooks/analise_imdb.ipynb
   
## 3. Estrutura do repositório
notebooks/ → Jupyter Notebook com EDA e modelagem
reports/ → Relatórios em PDF
src/ → Scripts auxiliares (opcional)
modelo_imdb.pkl → Modelo salvo
requirements.txt → Lista de pacotes
README.md → Guia do projeto

## 4. Modelo
O modelo final foi treinado usando RandomForestRegressor, por ser robusto e lidar bem com variáveis numéricas e categóricas. O desempenho foi avaliado com a métrica MAE (Mean Absolute Error), atingindo um erro médio de aproximadamente 0.15 pontos na nota IMDB.

## 5. Autor
Nome: Maria Luiza Oldra
Data: Setembro/2025
Contato: marialuizaoldra@gmail.com
