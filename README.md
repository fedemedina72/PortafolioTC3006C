# PortafolioTC3006C
**Portafolio para la clase Inteligencia Artificial Avanzada para la Ciencia de Datos, Grupo 101**

Dentro del portafolio se encuentran dos folders importantes: [Modulo1](Modulo1) y [Modulo2](Modulo2/Portafolio1). Estos folders contienen los archivos de los entregables que corresponde a cada uno de los módulos en donde se pide una evidencia de portafolio. 


## Modulo1
Dentro del [Modulo1](Modulo1) encontramos distintos archivos que pertenecen al módulo de Estadística. Este se desgloza de la siguiente manera:

### [LimpiezaDatos.ipynb](Modulo1/LimpiezaDatos.ipynb)


### [ConstruccionModelo.ipynb](Modulo1/ConstruccionModelo.ipynb)





## Modulo2
Dentro del [Modulo2](Modulo2/Portafolio1) encontramos distintos archivos que pertenecen al módulo de Machine Learning. Este se desgloza de la siguiente manera:

### [RegresionLineal.ipynb](Modulo2/Portafolio1/RegresionLineal.ipynb)
En este archivo se utilizó la base de datos llamada [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) con la cual se trabajó con la intención de implementar una técnica de aprendizaje máquina sin el uso de un framework. Para este, se creó un modelo de Regresión Lineal con la intención de predecir cuánto contaminan los vehículos en base a los parámetros que se tienen en la base de datos. Dentro del archivo se hizo la lectura y descripción de los datos, donde encontramos los valores estadísticos de estos y la cantidad de valores nulos en el dataframe. Después se hizo una matriz de correlación para encontrar qué variables tienen relación lineal con la variable de CO2 Emissions para ver cuales causan la contaminación vehicular. Finalmente se crearon gráficos para visualizar los datos y, en base a esto, se eligió la variable Engine Size (L) para usar en el modelo. 


### [RegresionLinealFramework.ipynb](Modulo2/Portafolio1/RegresionLinealFramework.ipynb)
Para este archivo, se utilizó la base de datos [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) con la que se trabajó para crear un modelo de Regresión Lineal utilizando un framework. Para este, se entrenó utilizando LinearRegression() de la librería sklearn. En el archivo se hizo lectura y descripción de los datos para encontrar los valores estadísticos de las variables al igual que verificar que no haya valores nulos. Después se hizo una matriz de correlación con la cual se optó por utilizar todas las variables cuantitativas del dataframe para el modelo. En seguida, se crearon los daots de entrenamiento y de prueba para entrenar el modelo y verificarlo. Finalmente se encontró una función que predice los valores del dataframe junto con los valores de los errores que la regresión obtuvo.


### [Análisis_del_Contexto_y_la_Normatividad_-2.pdf](Modulo2/Portafolio1/Análisis_del_Contexto_y_la_Normatividad_-2.pdf)
Dentro del archivo, se encuentra el Análisis del Contexto y la Normatividad, la cual explica sobre las leyes y la normatividad que involucran el uso de la base de datos de [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) y cómo es que el uso de esta no está rompiendo ninguna ley. Igualmente en esta se hace un análisis de los escenarios en que se puede utilizar de manera no-ética la base de datos.


### [ReporteDesempeño.ipynb](Modulo2/Portafolio1/ReporteDesempeño.ipynb)

