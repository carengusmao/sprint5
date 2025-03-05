# Análise de Anúncios de Venda de Veículos Usados

Este projeto utiliza um conjunto de dados de anúncios de venda de carros usados para explorar tendências de preços e outros fatores que influenciam a venda dos veículos.

## Estrutura do Projeto
- `app.py` → Aplicação Streamlit para visualização dos dados
- `vehicles_us.csv` → Conjunto de dados com os anúncios de carros
- `notebooks/` → Análises exploratórias em Jupyter Notebooks
- `requirements.txt` → Lista de dependências necessárias

## Funcionalidades
- Geração de histograma para análise da quilometragem dos veículos
- Gráfico de dispersão relacionando preço e odômetro
- Interface interativa usando Streamlit

## Conjunto de Dados
Os dados vêm do arquivo `vehicles_us.csv` e incluem informações sobre preço, ano do modelo, condição, tipo de transmissão, quilometragem, entre outros fatores.

## Tecnologias Utilizadas
- Python
- Pandas
- Plotly Express
- Streamlit