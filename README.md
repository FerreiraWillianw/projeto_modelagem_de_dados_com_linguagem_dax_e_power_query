# Construção de Star Schema com Power BI e Power Query

Este projeto demonstra a modelagem de dados utilizando o **Star Schema (Esquema Estrela)** no **Power BI**, partindo de uma única base de dados plana. O objetivo é transformar dados brutos em um modelo otimizado para análise e criação de relatórios de *Business Intelligence*.

## ⭐️ Star Schema

O Star Schema é um modelo de dados dimensional caracterizado por uma tabela de fatos central que se conecta a várias tabelas de dimensão. Sua estrutura simples em forma de estrela é ideal para otimizar o desempenho de consultas e facilitar a compreensão dos dados pelos usuários de BI.

## 🛠 Tecnologias e Linguagens Utilizadas

* **Power BI Desktop**: Ferramenta principal para modelagem e análise de dados.
* **Power Query**: Utilizado para o processo de *Extract, Transform, Load* (ETL), limpando e transformando a fonte de dados.
* **Linguagem M**: Empregada no Power Query para manipulações avançadas e criação das novas tabelas a partir da fonte única.
* **Linguagem DAX (Data Analysis Expressions)**: Utilizada para a criação de colunas calculadas de `ID_Produto` e outras lógicas de suporte à modelagem.

## 📂 Estrutura do Projeto

O projeto foi construído em cima de uma única fonte de dados, a planilha `Financial Sample.xlsx`, e resultou na criação de 5 novas tabelas dimensionais e de fato, interligadas em um Star Schema.

| Arquivo | Descrição |
| :--- | :--- |
| `modelagem_e_extracao_de_dados_com_DAX.pbix` | Arquivo do Power BI que contém a fonte de dados, todas as transformações realizadas no Power Query e o modelo Star Schema finalizado. |
| `modelagem_e_extracao_de_dados_com_DAX.docx` | Documento de diretrizes que detalha o passo a passo e as instruções para a construção do projeto. |
| `star_schema_financial_sample_pbix.png` | Print do Star Schema. |
| `Financial Sample.xlsx` | Base de dados original utilizada como fonte. |

## 🚀 Como Visualizar o Projeto

1.  **Pré-requisito:** Certifique-se de ter o **Power BI Desktop** instalado em sua máquina.
2.  **Clone o Repositório:** Faça o download ou clone este repositório para sua máquina local.
3.  **Abra o Arquivo:** Abra o arquivo `modelagem_e_extracao_de_dados_com_DAX.pbix` no Power BI Desktop.
4.  **Explore:**
    * **Visualização de Dados:** Observe a estrutura do Star Schema na aba **Modelo**.
    * **Transformações (Power Query):** Acesse **Transformar dados** para visualizar os passos de ETL e o código M utilizado na criação das 5 tabelas.
    * **Cálculos (DAX):** Verifique as colunas calculadas criadas com DAX nas tabelas para entender a lógica de geração dos IDs.

## ✨ Resultado

O projeto demonstra a capacidade de transformar uma fonte de dados não estruturada em um modelo dimensional robusto, pronto para análises de BI e criação de indicadores de desempenho (KPIs) com alta performance.
