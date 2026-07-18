# House Prices ML - Rental Prices Prediction in São Paulo

## Visão Geral

* Este projeto tem como objetivo desenvolver um sistema de Machine Learning capaz de estimar o valor de aluguel de imóveis residenciais na cidade de São Paulo a partir de suas características estruturais e geográficas.

* Mais do que construir um modelo preditivo, o projeto busca reproduzir o fluxo de desenvolvimento utilizado em projetos profissionais de Ciência de Dados, desde a definição do problema até a disponibilização do modelo para uso.

* Ao longo do desenvolvimento serão aplicadas boas práticas de organização de código, versionamento, documentação e reprodutibilidade, transformando este repositório em um estudo de caso completo de Machine Learning.

---

## Objetivos

Os principais objetivos deste projeto são:

* Construir um pipeline completo de Ciência de Dados para um problema de regressão.
* Explorar e compreender os fatores que influenciam o valor do aluguel de imóveis.
* Desenvolver e comparar diferentes modelos de Machine Learning.
* Avaliar o desempenho dos modelos utilizando métricas apropriadas para problemas de regressão.
* Produzir um projeto organizado, documentado e reproduzível, seguindo boas práticas de engenharia de software.

---

## Problema

* O mercado imobiliário depende de estimativas de preços para apoiar decisões de proprietários, imobiliárias, investidores e plataformas digitais.

* Neste projeto será desenvolvido um modelo capaz de estimar o valor mensal de aluguel de imóveis residenciais na cidade de São Paulo utilizando informações como localização, área, número de quartos, vagas de garagem, banheiros e demais características disponíveis no conjunto de dados.

---

## Dataset

* Os dados utilizados neste projeto foram obtidos a partir de um conjunto de dados público disponibilizado no [Kaggle](https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices?resource=download), contendo informações de imóveis anunciados para aluguel na cidade de São Paulo.

* Nesta primeira etapa, o dataset foi incorporado ao repositório para facilitar a reprodução do projeto por qualquer pessoa que realizar o clone do repositório.

* As características do conjunto de dados, bem como sua análise exploratória, serão documentadas nas próximas etapas do projeto.

---

## Estrutura do Projeto

```text
House-Prices-ML/

├── data/
│   ├── raw/          # Dados originais
│   ├── interim/      # Dados intermediários
│   └── processed/    # Dados preparados para modelagem
│
├── models/           # Modelos treinados
│
├── notebooks/        # Exploração e experimentos
│
├── reports/
│   ├── figures/      # Figuras e gráficos
│   └── metrics/      # Métricas e resultados
│
├── src/              # Código reutilizável do projeto
│
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Tecnologias Utilizadas

* Python 3.12
* Jupyter Notebook
* Visual Studio Code
* Git
* GitHub
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Status do Projeto

**Em desenvolvimento**

Etapas concluídas até o momento:

* Estruturação inicial do repositório.
* Configuração do Git e GitHub.
* Criação do ambiente virtual (`.venv`).
* Configuração do VS Code e Jupyter Notebook.
* Definição da arquitetura do projeto.
* Organização das pastas.
* Inclusão do conjunto de dados.

---

## Próximas Etapas

* Compreensão do conjunto de dados.
* Análise exploratória (EDA).
* Limpeza e preparação dos dados.
* Engenharia de atributos.
* Treinamento dos modelos.
* Avaliação dos resultados.
* Interpretabilidade do modelo.
* Deploy da solução.
