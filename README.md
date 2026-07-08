# Consulta de Dados com Pandas 📊🐍

Este repositório contém um projeto prático focado na exploração, manipulação e análise de dados utilizando a biblioteca **Pandas** em Python. O objetivo principal é demonstrar a aplicação de técnicas essenciais de Engenharia e Análise de Dados para extrair informações úteis de bases de dados estruturadas.

---

## 📌 Sobre o Projeto

O projeto simula um cenário real de análise de dados de negócios, onde foi necessário processar um volume de dados brutos, realizar a limpeza necessária e responder a perguntas estratégicas através de consultas personalizadas.

As principais etapas abordadas neste projeto incluem:
- **Carga de Dados:** Importação de arquivos em diferentes formatos (CSV, Excel, SQLite).
- **Tratamento e Limpeza (Data Cleaning):** Identificação e tratamento de valores ausentes, remoção de duplicados e conversão de tipos de dados.
- **Filtros e Consultas Avançadas:** Utilização de métodos como `.loc[]`, `.iloc[]`, `.query()` e máscaras booleanas para segmentar informações.
- **Agrupamentos e Agregações:** Aplicação de `.groupby()` e funções agregadoras (`sum`, `mean`, `count`) para gerar resumos estatísticos gerenciais.

---

## ⚙️ Tecnologias e Ferramentas

- **Python** (Versão 3.x)
- **Pandas:** Biblioteca principal para manipulação de dados.
- **Jupyter Notebook / VS Code:** Ambientes de desenvolvimento utilizados para a análise interativa.

---

## 📂 Estrutura do Repositório

```text
├── data/               # Pasta contendo a base de dados (ex: dados_vendas.csv)
├── notebooks/          # Jupyter Notebooks com os códigos passo a passo
│   └── analise_dados.ipynb
├── README.md           # Documentação do projeto
└── requirements.txt    # Dependências do projeto
