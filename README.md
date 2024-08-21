# Análise, Modelagem e Visualização de Dados

## Visão Geral
Este projeto visa analisar, modelar e visualizar dados de vendas de uma empresa fictícia ao longo de 4 anos. Inclui importação e análise de dados, tratamento de valores nulos, criação de gráficos e tabelas pivot, e análise temporal. Utilizando Python e bibliotecas como `pandas` e `matplotlib`, criamos gráficos para entender as tendências de vendas por ano, mês, categoria e produto.

## Base de dados
Fonte: https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

## Descrição

Este projeto realiza a análise e modelagem de dados para um conjunto de vendas, utilizando Python. 

## Etapas do Código

1. **Importação e Análise da Base**
   - Carrega o arquivo CSV e realiza análise inicial do DataFrame.
   
2. **Tratamento de Dados**
   - Identifica e corrige valores nulos.
   - Remove colunas se necessário.
   - Cria tabelas pivot para análise de dados.
   
3. **Manipulação de Datas**
   - Converte colunas de datas para o formato `datetime`.
   - Cria colunas adicionais e analisa vendas por ano.

4. **Visualização de Dados**
   - Cria gráficos de barras para visualização de vendas anuais e mensais.
   - Adiciona títulos, rótulos e ajusta estilos.
  
5. **Análise de Vendas por Ano:** Gráfico de barras para visualizar as vendas totais por ano.
6. **Análise de Vendas por Mês e Ano:** Comparação das vendas mensais de cada ano.
7. **Análise de Vendas por Categoria:** Comparação das vendas por categoria ao longo dos anos.
8. **Análise dos Itens Mais Vendidos:** Gráficos de barras horizontais mostrando os produtos mais vendidos.

## Requisitos

- pandas
- numpy
- matplotlib



## Como Executar

1. Clone o repositório.
2. Instale as dependências com `pip install -r requirements.txt`.
3. Execute o script Python para realizar a análise e visualização.

## Conclusões
Os dados revelam um crescimento constante nas vendas ao longo dos anos, com a categoria 'Technology' sendo a mais promissora. A análise detalhada dos itens mais vendidos pode ajudar na tomada de decisões estratégicas para o inventário e promoções.


