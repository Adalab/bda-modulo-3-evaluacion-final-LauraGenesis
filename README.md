# bda-modulo-3-evaluacion-final-LauraGenesis

En este repositorio se encuentran los ejercicios de evaluación realizados durante el análisis y procesamiento de datos relacionados con reservas de vuelos de una aerolínea.

Exploración Inicial:

Se realizó una exploración inicial de los datos para identificar posibles problemas, como valores nulos, atípicos o datos faltantes en las columnas relevantes.
Se utilizó funciones de Pandas para obtener información sobre la estructura de los datos, la presencia de valores nulos y estadísticas básicas de las columnas involucradas.
Se unieron los dos conjuntos de datos de la forma más eficiente posible.

Limpieza de Datos:

Se  trataron los valores nulos 

Se realizaron ajustes o conversiones necesarias en las columnas (por ejemplo, cambiar tipos de datos) para garantizar la adecuación de los datos para el análisis estadístico.

Gráficas para la visulización:

Barplot:Gráfico de barras es una representación visual de datos que utiliza barras rectangulares de diferentes longitudes para mostrar la frecuencia, cantidad o distribución de una variable categórica.

Pieplot: Un gráfico de pastel es un tipo de gráfico circular que muestra la proporción de cada categoría en un conjunto de datos. Cada categoría se representa por un sector del círculo y el tamaño del sector corresponde a la proporción de esa categoría en el conjunto de datos.

Regplot: Gráfico de regresión , muestra la relación entre dos variables numéricas mediante una línea de regresión. Es útil para visualizar la relación entre una variable independiente (eje x) y una variable dependiente (eje y) y para identificar patrones o tendencias en los datos.


Boxplot:  Diagrama de Caja y Bigote, muestra la distribución de una variable numérica a través de sus estadísticas clave: el mínimo, el primer cuartil (Q1), la mediana (Q2), el tercer cuartil (Q3) y el máximo. También puede mostrar los valores atípicos de los datos. Es útil para identificar la dispersión y la simetría de los datos, así como para detectar valores atípicos.

 Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo:

 Preparación de Datos: Se filtraron los datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.
Análisis Descriptivo: Se agruparon los datos por nivel educativo y se calcularon estadísticas descriptivas básicas del número de vuelos reservados para cada grupo.
Prueba Estadística: Se llevó a cabo una prueba de A/B testing con T de student para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.