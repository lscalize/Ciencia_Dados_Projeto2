# Análise, Modelagem e Visualização de Dados

## Visão Geral
Este projeto tem como objetivo analisar, modelar e visualizar dados de vendas de uma empresa fictícia ao longo de um período de 4 anos. Através de técnicas de ciência de dados, abordamos a importação, limpeza, transformação e análise dos dados, com o objetivo de obter insights valiosos para o negócio. Utilizando Python e bibliotecas como `pandas` e `matplotlib`, foram gerados gráficos e tabelas que nos permitem entender as tendências de vendas por ano, mês, categoria e produto.

## Base de Dados
- **Fonte:** [Kaggle - Sales Forecasting Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

## Objetivos
O projeto busca responder às seguintes perguntas-chave:
- Como foi o **volume de vendas** ao longo do período?
- Qual foi a **categoria de produtos** mais vendida?
- Quais foram os **itens mais vendidos**?

## Etapas do Código

1. **Importação e Análise Inicial dos Dados**
   - Carregamento do arquivo CSV e análise exploratória inicial do DataFrame para compreensão das variáveis.

2. **Tratamento de Dados**
   - Identificação e correção de valores nulos.
   - Remoção de colunas desnecessárias e criação de tabelas pivot para análises específicas.

3. **Manipulação de Datas**
   - Conversão de colunas de datas para o formato `datetime`.
   - Criação de colunas adicionais para análise temporal detalhada, como ano e mês.

4. **Visualização de Dados**
   - Geração de gráficos de barras e outras visualizações para representar as vendas anuais e mensais.
   - Customização de gráficos com títulos, rótulos e estilos para melhor interpretação dos dados.

5. **Análises Específicas**
   - **Vendas por Ano:** Gráfico de barras demonstrando as vendas totais por ano.
   - **Vendas por Mês e Ano:** Comparação das vendas mensais entre os anos.
   - **Vendas por Categoria:** Gráfico que compara as vendas por categoria ao longo dos anos.
   - **Itens Mais Vendidos:** Gráficos de barras horizontais destacando os produtos com maior volume de vendas.

## Conclusões

### 1. Como foi o volume de vendas ao longo do período?
A análise dos dados revelou um crescimento constante nas vendas ao longo dos quatro anos. O gráfico de vendas anuais demonstra uma tendência positiva, indicando que a empresa experimentou um aumento sustentável em suas receitas ano após ano.

### 2. Qual foi a categoria de produtos mais vendida?
A categoria 'Technology' destacou-se como a mais vendida durante o período analisado. Isso sugere que produtos tecnológicos tiveram uma maior demanda e contribuíram significativamente para o crescimento das vendas totais da empresa.

### 3. Quais foram os itens mais vendidos?
Os produtos individuais mais vendidos incluem uma variedade de itens tecnológicos, que reforçam a conclusão de que a categoria 'Technology' liderou em termos de volume de vendas. Esses itens podem ser considerados essenciais para futuras decisões de inventário e promoções direcionadas.

## Requisitos
- `pandas`
- `numpy`
- `matplotlib`

## Como Executar

1. Clone este repositório para sua máquina local.
2. Instale as dependências necessárias utilizando o comando:
   ```bash
   pip install -r requirements.txt


