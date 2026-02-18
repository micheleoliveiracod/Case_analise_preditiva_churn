# Projeto CHURN - Predição de Evasão de Clientes

## 📋 Visão Geral

Este projeto se trata de um algoritimo de Machine Learning para predição de churn (evasão) de clientes, utilizando técnicas de análise de dados e algoritmos de classificação para identificar clientes com alta probabilidade de cancelamento. Modelo estatistico de arvore de decisão.

## 🎯 Objetivos

Objetivo Principal: Desenvolver um modelo preditivo para identificar clientes propensos ao churn

Objetivos Específicos:
Analisar padrões comportamentais dos clientes
Fornecer insights acionáveis para retenção de clientes
Criar visualizações interpretáveis dos resultados
Implementar e comparar diferentes algoritmos de ML

## 🔧 Tecnologias Utilizadas

Linguagens e Frameworks

- Python: Linguagem principal
- Pandas: Manipulação de dados
- Openpyxl: Formatação de dataset
- Nbformat: Formatos notebooks
- Ipykernel: Execução notebooks
- NumPy: Computação numérica
- Scikit-learn: Algoritmos de Machine Learning
- Plotly: Gráficos interativos

Ferramentas de Desenvolvimento

- Visual Studio Code: Desenvolvimento interativo
- Jupyter Notebook: Desenvolvimento interativo
- Git: Controle de versão

## 📊 Metodologia

1. Análise Exploratória

- Estatísticas descritivas dos dados
- Identificação de padrões
- Visualização da distribuição do target (churn)

2. Pré-processamento

- Tratamento de valores ausentes
- Codificação de variáveis categóricas e numéricas
- Normalização/padronização de features numéricas
- Divisão dos dados (treino 70% e teste 30%)

3. Feature Engineering

- Criação de novas variáveis derivadas
- Seleção de features relevantes

4. Modelagem

Algoritmos implementados:
- Árvore de decisao (Escolhido para fazer a aprevisão)
- K-NN

5. Avaliação

Métricas utilizadas:
- Acuracia: Precisão geral

## 📁 Estrutura dos Dados

Análise descritiva
- Base de dados: dataset_cancelamentos
- Script: dataset_descritiva.ipynb
- Graficos: Escolhidos por nivel de impacto no esclarecimento do cenario

Análise preditiva
- Base de dados: dataset_novos_clienets
- Script: dataset_preditiva.ipynb

## 📄 Licença
Todo o conteúdo é compartilhado sob a Licença MIT.
