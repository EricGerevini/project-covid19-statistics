# Estudo sobre casos de COVID-19 no Estado de São Paulo utilizando pandas/matplot/numpy
Estudo utilizando python (pandas, numpy e matplotlib) com o dataframe dos infectados de COVID-19 no Estado de São Paulo.

# Objetivos
Neste projeto tenho como objetivo responder 3 perguntas e depois apresentar um modelo probabilístico que será explicado adiante.

1 - Inicialmente ele retornará qual genêro tem maior incidência de COVID-19.

2 - Um gráfico da mortalidade por faixas de idade.

3 - A comorbidade pré-existente mais provável de se encontrar numa pessoa com COVID-19.

4 - Um modelo que estime a probabilidade da pessoa morrer, uma vez que está contaminada com covid, e considerando os inputs de idade, gênero e doenças pré-existentes.


# Pré Requisitos
Necessário importar os pacotes; pandas para trabalhar com o dataframe, numpy para trabalhar com os vetores(array's) e o matplotlib para plotar o gráfico.

```
import pandas as pd

import numpy as np

import matplotlib.pyplot as plt
```

# DataFrame utilizado para o projeto

O dataframe utilizado pode ser encontrado no site: https://www.saopaulo.sp.gov.br/planosp/simi/dados-abertos/ em Microdados dos Casos

Certifique-se que o arquivo csv '202xxxxx_Casos-e-obitos-ESP.csv' esteja no mesmo local que o arquivo do python e atualize dentro do código, este arquivo é atualizado diariamente pelo Governo do Estado de São Paulo.

# Resultados

Os resultados foram bastante satisfatórios e próximos aos que são divulgados por grandes mídias. Infelizmente o modelo para o problema 4 fica fica impreciso conforme o caso se torna cada vez mais incomum (permutação das comorbidades).

# Referências 

https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp

Obrigado e espero que gostem do meu primeiro projeto/estudo em dataframe em python.

Abraços o/






