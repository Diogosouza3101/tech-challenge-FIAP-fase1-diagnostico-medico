# Tech Challenge - Fase 1 - Diagnóstico Médico com IA

## 1. Descrição do Projeto

Este projeto foi desenvolvido como parte do Tech Challenge da Fase 1 da pós-graduação em Inteligência Artificial para Desenvolvedores.

O objetivo do projeto é construir uma solução inicial de Inteligência Artificial aplicada ao contexto médico, utilizando técnicas de Machine Learning para apoio ao diagnóstico com dados estruturados e, como entrega extra, uma abordagem de Visão Computacional com Redes Neurais Convolucionais (CNN) para análise de imagens médicas.

A proposta é apoiar a triagem e a análise inicial de exames, destacando padrões relevantes nos dados. O sistema não substitui a avaliação médica, sendo uma ferramenta de apoio à decisão clínica.

---

## 2. Problema de Negócio

Um hospital universitário busca implementar uma solução inteligente para auxiliar médicos e equipes clínicas na análise inicial de exames e dados médicos.

Com o crescimento do volume de pacientes, exames e prontuários digitalizados, torna-se necessário utilizar soluções de IA que possam acelerar a triagem, reduzir falhas operacionais e apoiar decisões médicas.

Neste projeto, foram desenvolvidas duas abordagens:

- Classificação de diagnóstico médico com dados estruturados.
- Classificação de imagens médicas utilizando CNN como entrega extra.

---

## 3. Datasets Utilizados

### 3.1 Dataset Principal - Dados Estruturados

Foi utilizado um dataset público relacionado ao diagnóstico de câncer de mama, com o objetivo de classificar os casos como benignos ou malignos.

Dataset:

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data

### 3.2 Dataset Extra - Imagens Médicas

Como entrega extra, foi utilizado um dataset de imagens médicas para construção de um modelo de Visão Computacional com CNN.

Dataset:

https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset/data

---

## 4. Tecnologias Utilizadas

As principais tecnologias utilizadas no projeto foram:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- EfficientNetB0
- SHAP
- Jupyter Notebook
- Docker
