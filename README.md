# Data Preparation for Machine Learning

Este repositório reúne **três projetos práticos** com listas de exercícios voltadas à **preparação de dados para Machine Learning**, abordando desde o tratamento de dados numéricos até o processamento de texto e a vetorização de variáveis categóricas.

Os projetos têm como foco o **aprendizado prático de técnicas essenciais de Feature Engineering**, mostrando como diferentes escolhas de pré-processamento impactam a representação dos dados, a interpretabilidade e o desempenho de modelos preditivos.


## Estrutura do Repositório

O repositório está organizado nos seguintes diretórios:

### 1. Palmer Penguins – Data Preparation for Machine Learning 
`palmer-penguins-preprocessing`

Exercícios de pré-processamento de dados numéricos utilizando o dataset **Palmer Penguins**.

#### Conteúdos abordados

- Escalares, vetores e espaços vetoriais em Machine Learning
- Discretização de variáveis contínuas
  - Bins fixos
  - Bins variáveis (quantização)
- Transformações de potência
  - PowerTransformer (Yeo-Johnson)
- Normalização e escalonamento de dados
  - Min-Max Scaling
  - Standard Scaling
- Regressão Linear com regularização L2 (Ridge Regression)

#### Tecnologias

- Python
- Pandas
- Scikit-learn

---

### 2. Feature Engineering e Vetorização de Texto
`machine-learning-vectorization`
Projeto focado em **processamento de dados textuais** e **vetorização de variáveis categóricas**, aplicado a problemas de classificação.

#### Conteúdos abordados

- Vetorização de texto com TF-IDF
- Regressão Logística para classificação de sentimentos
- Análise e visualização de coeficientes do modelo
- Técnicas de codificação de variáveis categóricas:
  - One-Hot Encoding
  - Dummy Encoding
  - Effect Encoding
  - Feature Hashing
  - Bin Counting (Count Encoding)
- Discussão sobre vantagens e desvantagens de cada técnica

#### Datasets utilizados

- Large Movie Review Dataset (IMDB)
- Toy dataset para codificação categórica

#### Tecnologias

- Python
- Pandas
- Scikit-learn
- Statsmodels
- Mglearn
- Matplotlib

---

### 3. Feature Engineering e Pré-processamento de Dados
`preprocessing-feature-engineering`
Exercícios práticos de **engenharia de atributos**, **seleção de features** e **processamento de linguagem natural (NLP)**.

#### Conteúdos abordados

- Escalonamento e normalização de dados
  - StandardScaler
  - Normalização L1 e L2
  - Implementação manual de normalização
- Seleção de features
  - Métodos de Filtragem
  - Métodos Wrapper (RFECV)
  - Métodos Embedded (conceito)
- Vetorização de texto
  - Bag-of-Words
  - Bag-of-n-Grams
- Pré-processamento de texto
  - Remoção de stopwords
  - Stemming
  - Lemmatization

#### Datasets utilizados

- Iris Dataset
- Breast Cancer Dataset
- Textos em língua portuguesa para tarefas de NLP

#### Tecnologias

- Python
- Scikit-learn
- NLTK
- spaCy
- Pandas
- NumPy


## Objetivo

O objetivo deste repositório é **consolidar o estudo prático de técnicas fundamentais de Data Preparation para Machine Learning**, fornecendo exemplos claros e comparativos que auxiliem na compreensão de:

- Como preparar dados numéricos para modelagem preditiva
- Como processar e representar dados textuais
- Como diferentes técnicas de vetorização e codificação afetam modelos de aprendizado de máquina
