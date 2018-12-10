# Machine Learning Engineer Nanodegree
# Capstone Project
## Smart BackOrders - Análise e Predição de Pedidos Pendentes (BackOrders) utilizando Modelos de Inteligência Artificial

### Visão Geral do Projeto
Pedidos Pendentes (BackOrders) 

BackOrders de produtos é um problema comum da cadeia de suprimentos, sendo uma preocupação importante na Gestão de Inventário de Produtos.

Definição de BackOrder: Pedido ou compromisso não efetivado ou cumprido. Um pedido pendente é uma demanda imediata de determinado item cujo estoque é insuficiente para satisfazer tal demanda.

Existem diversos fatores que contribuem para a ocorrência de BackOrders. Eis alguns:
- Falha de gestão
- Falta de comunicação
- Incapacidade de fabricar itens suficientes para atender a demanda
- Falta de dados para prever com precisão a demanda
- Ausência de sistema informatizado que auxilie
- Estratégia da empresa.

### Problema
#### Como a Inteligência Artificial pode auxiliar na resolução do problema?
A partir dos fatos já ocorridos, utilizando os dados disponíveis, aplicar modelos e algoritmos que possam estabelecer uma “previsão” sobre a probabilidade de nova ocorrência.

A proposta deste trabalho é contribuir com a análise preditiva de BackOrders, apresentando-a como uma ferramenta auxiliar ao processo de tomada de decisão nas empresas.

Visa especialmente, uma mudança de postura: REATIVA x PRÓ-ATIVA, atuando diretamente nos índices de satisfação de clientes, com a consequente melhoria nas vendas.

Trabalhando para identificar peças em risco de atraso antes do evento, então o negócio tem tempo para reagir.

Este é o objetivo do projeto “Smart BackOrders: Análise e Predição de Pedidos Pendentes (BackOrders) utilizando Modelos de Inteligência Artificial”.

### Install
 
Este projeto requer o **Python 3** Jupyter Notebook instalado e as seguintes bibliotecas:
- Pandas: Python Data Analysis Library
	- http://pandas.pydata.org
- NumPy: NumPy is the fundamental package for scientific computing with Python.
	- http://www.numpy.org/
- Matplotlib: Matplotlib is a Python 2D plotting library
	- https://matplotlib.org/
- Seaborn: Statistical Data Visualization
	- https://seaborn.pydata.org/
- scikit-learn: Machine Learning in Python
	- https://scikit-learn.org/
- imbalanced-learn: under-sampling and over-sampling methods
	- https://imbalanced-learn.org/


### Code

Etapa 01: Conhecer, Preparar e Limpar os Dados (análise preliminar de Features)
- BackOrders_Etapa01_Cleaning-Data-Train.ipynb
- BackOrders_Etapa01_Cleaning-Data-Test.ipynb
- Etapa 1 - Objetivos:
	- Análise dos Tipos de Dados
	- Dados faltantes, inválidos ou nulos
	- Linhas repetidas
	- Outliers
	- Gerar novo arquivo com os dados resultantes

Etapa 02: Análise mais detalhada de Features
- BackOrders_Etapa02_EDA-Trend-Analysis-Train.ipynb
- BackOrders_Etapa02_EDA-Trend-Analysis-Test.ipynb
- Etapa 2 - Objetivos:
	- Relacionamento entre as Features
	- Análise de Tendências
	- Questionamento sobre os dados

Etapa 03: Geração de Modelos e Avaliação dos Resultados
- BackOrders_Etapa03_Model-Fit-Validation.ipynb
- Etapa 3 - Objetivos:
	- Criação e Execução dos Modelos
	- Análise Visual e Avaliação
	- Análise dos Resultados

Etapa 04: Tuning/Calibração de Modelos e Reavaliação dos Resultados
- BackOrders_Etapa04_TuningGradientBoostingModel.ipynb
- Etapa 4 - Objetivos:
	- criar classificador: "baseline"
	- tuning de alguns parâmetros (efeito didático) e criar 2o classificador: "modelo_1"
	- novo tuning de mais alguns parâmetros (efeito didático) e criar classificador final: "modelo_final"
	- visando comparação, utilizar também o "classificador default do sklearn" e o "classificador utilizado na etapa anterior de validação dos modelos"

### Run

Para executar o projeto é necessário que as bases de dados estejam na sub- pasta "data":
- "data/Kaggle_Training_Dataset_v2.csv"
- "data/Kaggle_Test_Dataset_v2.csv"
