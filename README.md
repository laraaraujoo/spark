# Spark
Demonstração breve sobre o spark

Código desenvolvido no Colab

## Passo 1: Baixar as libs
- pip install matplotlib
- pip install spark 

## Passo 2 : Importar as libs

Importamos as libs que serão utilizados nesse projeto 
- import matplotlib.pyplot as plt
- from pyspark.sql  import *  
- from pyspark.sql.functions import *
- from pyspark.sql import functions as F
- import spark
- from pyspark.sql import SparkSession
- import pandas as pd

## Passo 3: Criamos o SparkSession

## Passo 4 : Criação do dataframe

Criamos o dataframe simples e objetivo para ficar de fácil entendimento.

Foi criado um dataframe (df) com algumas colunas como: nome, idade e sexo.

Depois de criarmos os dados e as colunas, juntamos as informações no df para começarmos a manipular. 

## Passo 5 : Uso do SQL

Usamos o SQL e o pyspark para fazermos a soma e média das idades.

## Passo 6 : Plotando gráficos

Usamos o matplotlib para criarmos um gráfico de barras, pizza e histograma. 
