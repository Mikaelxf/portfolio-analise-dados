# Consulta de Dados com Pandas

Este repositório contém um projeto prático de análise de dados utilizando Python e a biblioteca Pandas. O objetivo é demonstrar conceitos fundamentais de manipulação, tratamento e consulta de dados a partir de uma base fictícia de empresas.

## Sobre o Projeto

O projeto simula um cenário simples de análise de negócios, no qual os dados são criados diretamente no código para facilitar a reprodução do estudo.

A análise trabalha com informações como quantidade de funcionários, ramo de atuação, tempo de mercado, faturamento anual, avaliação dos funcionários e lucro anual.

As principais etapas abordadas incluem:

- Criação de uma base de dados sintética
- Construção de um DataFrame com Pandas
- Conversão de tipos de dados
- Filtros condicionais em colunas específicas
- Cálculo de métricas simples
- Extração de informações relevantes para análise empresarial

## Tecnologias e Ferramentas

- Python 3
- Pandas
- Jupyter Notebook
- VS Code

## Análises Realizadas

- Visualização inicial da base de dados
- Conversão de colunas numéricas armazenadas como texto
- Filtro de empresas com 500 ou mais funcionários
- Cálculo da relação entre faturamento anual e lucro anual
- Identificação de empresas com relação faturamento/lucro maior que 10
- Cálculo da média de avaliação dos funcionários
- Contagem de empresas com lucro anual superior a R$ 500.000,00
- Identificação de empresas do ramo de fast food

## Estrutura do Repositório

```text
├── DADOS_COM_PANDAS.ipynb  # Notebook principal contendo a criação dos dados e as análises
└── README.md               # Documentação do projeto
```

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Instale a biblioteca necessária:

```bash
pip install pandas
```

3. Abra o arquivo `DADOS_COM_PANDAS.ipynb` em um dos ambientes abaixo:

- Jupyter Notebook
- Google Colab
- VS Code com extensão para notebooks

4. Execute as células na ordem para visualizar a criação da base, os tratamentos e os resultados das análises.

## Objetivo de Aprendizado

Este projeto foi desenvolvido com foco na prática dos fundamentos de análise de dados com Pandas.

Ele demonstra habilidades iniciais importantes para quem está estudando dados, como criação de DataFrames, tratamento de tipos, aplicação de filtros e geração de métricas simples a partir de dados estruturados.

## Observações

A base de dados utilizada é fictícia e foi criada apenas para fins educacionais. Os valores não representam empresas reais.
