# ETL de Business Intelligence em Python

Este é um guia prático para um script Python que exemplifica o processo de Extração, Transformação e Carregamento (ETL) de dados para fins de Business Intelligence (BI). O script utiliza as bibliotecas Pandas para manipulação de dados e SQLite3 para interação com o banco de dados.

## Objetivo do Script:

Este script tem como objetivo demonstrar um fluxo simplificado de ETL para análise de vendas de duas filiais diferentes. Ele ilustra como extrair dados de fontes variadas, como arquivos CSV e Excel, realizar transformações nos dados e armazená-los em formatos adequados para análise posterior.

## Funcionalidades Destacadas:

1. **Extração de Dados**: Extrai dados de vendas de uma filial de um arquivo CSV e outra filial de um arquivo Excel.
2. **Transformação de Dados**: Realiza transformações nos dados, calculando o valor total de vendas para cada filial.
3. **Exportação para CSV**: Salva os dados transformados em arquivos CSV para facilitar a análise ou compartilhamento.
4. **Carregamento em Banco de Dados**: Carrega os dados transformados em um banco de dados SQLite, permitindo consultas mais avançadas.
5. **Consulta SQL**: Demonstra como recuperar os dados do banco de dados utilizando consultas SQL, útil para análises mais complexas.

## Instruções de Utilização:

1. **Instalação de Dependências**: Certifique-se de ter as bibliotecas `pandas` e `sqlite3` instaladas em seu ambiente Python.
2. **Download de Dados**: Baixe os arquivos `vendas_filial1.csv`, `vendas_filial2.xlsx` e `dados_transformados.db` de [Google Colab](https://colab.research.google.com/drive/18WmEDVLTJiJSLf3v-8RGC0cZazrx5Xk9?usp=sharing).
3. **Organização de Arquivos**: Coloque os arquivos na mesma pasta do script Python para garantir o correto funcionamento.
4. **Execução do Script**: Execute o script Python para iniciar o processo de ETL.

## Notas Adicionais:

Certifique-se de seguir as instruções e pré-requisitos para garantir uma execução adequada do script. Este guia destina-se a fornecer uma visão geral do fluxo de trabalho, permitindo adaptações conforme necessário para cenários específicos de análise de dados.
