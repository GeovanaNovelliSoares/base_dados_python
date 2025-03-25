# Lendo grandes bases de dados exigindo menos a capacidade do computador e agrupando dados.
## 📌 Descrição

Este projeto demonstra como ler grandes bases de dados utilizando Python e Pandas de forma eficiente, minimizando o uso de memória e otimizando a performance do computador. A base de dados utilizada contém transações financeiras e é proveniente do Kaggle, sendo um grande conjunto de dados que pode causar problemas de desempenho ao ser carregado diretamente na memória.

## 🔗 Fonte de Dados

Kaggle: [IBM Transactions for Anti-Money Laundering (AML)](https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-Laundering-aml)

Nome original do arquivo: HI-Large_Trans.csv

Nome utilizado no projeto: large.csv

## ⚙️ Tecnologias Utilizadas

- Python

- Pandas

## 🚀 Funcionalidades

- Leitura otimizada de grandes arquivos CSV usando chunksize.

- Identificação de colunas relevantes para reduzir a memória consumida.

- Conversão de tipos de dados para otimizar a utilização de RAM.

- Agregação de dados para análise eficiente.

## 🏆 Benefícios

- Evita estouro de memória ao processar arquivos grandes.

- Possibilita manipular grandes volumes de dados em máquinas com recursos limitados.

- Permite realizar análises e agrupamentos sem carregar toda a base de dados de uma vez.
