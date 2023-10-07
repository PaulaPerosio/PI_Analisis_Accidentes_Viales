<h1 align="center">Análisis de Víctimas Fatales por Accidentes Viales en CABA </h1>
<hr>

<h2 align="center">Proyecto Individual N°2 - Data Science - Henry</h2>
<hr>

<h3 align="center"> Rol de Data Analyst para: Observatorio de Movilidad y Seguridad Vial (OMSV) - Secretaría de Transporte </h3>

<p align='center'>
<img src = 'https://static.lajornadaestadodemexico.com/wp-content/uploads/2022/08/Siniestros-viales.jpg' height = 300>
<p>

## Descripción
<p align="justify">

  Este proyecto está enfocado en el análisis de datos de víctimas fatales en accidentes viales y la presentación de los mismos para contribuir a la correcta toma de decisiones y acciones futuras que lleven a la disminución de muertes en la Ciudad Autónoma de Buenos Aires (CABA), Argentina.

  Se trabajó con los datos de víctimas de accidentes viales entre 2016 y 2021 provenientes de la página web Buenos Aires Data **([Link](https://data.buenosaires.gob.ar/dataset))**, junto a datos relevantes para dar contexto y brindar información clara y precisa.

  También se presenta un resumen del análisis construido en un dashboard interactivo de Power BI. El mismo se entrelaza con indicadores clave de rendimiento, los cuales nos ayudan a entender el efecto de determinadas métricas de seguridad vial en el transcurso del tiempo.

</p>

## Datos y Herramientas
<p align="justify">

Los datasets utilizados en este proyecto se tomaron de la página web de Buenos Aires Data **([Link](https://data.buenosaires.gob.ar/dataset))**. Se trabajó con:

  - **Homicidios** : Datos de hechos y víctimas fatales por accidentes viales en CABA **([Link](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales))**.

  - **Comunas** : Datos de las comunas y sus barrios en CABA  **([Link](https://data.buenosaires.gob.ar/dataset/comunas))**.

  - **Cruces Semaforizados** : Datos de ubicación de semáforos en CABA **([Link](https://data.buenosaires.gob.ar/dataset/cruces-semaforizados))**.

  - **Flujo Vehicular** : Datos del flujo vehicular en CABA **([Link](https://data.buenosaires.gob.ar/dataset/flujo-vehicular-anillo-digital))**.
  
Además, se utilizaron datos poblacionales del **INDEC** y artículos periodísticos e informativos para tener un conocimiento del contexto.

Se trabajó en **Jupyter Notebook** para realizar el análisis exploratorio de los datos, utilizando principalmente las librerías **pandas/numpy** y
**matplotlib/seaborn** específicamente para gráficos.

El dashboard presentado, junto a las tranformaciones y vinculaciones con otros datos se realizaron en **Power BI**.

</p>


## Organización Repositorio
<p align="justify">

  - **Power_BI**: Carpeta donde se encuentra el dashboard del proyecto y los archivos utilizados en él. Archivos generados luego del proceso de EDA y archivos de datos complementarios consumidos directamente en Power BI.
  - **EDA-Homicidios.py**: Análisis exploratorio de los datos de homicidios (Hechos y víctimas), con algunas transformaciones e imputaciones necesarias.
  - **homicidios.xlsx**: Dataset inicial con tablas de hechos y víctimas fatales por accidentes viales, los cuales fueron trabajados en el EDA.
  - **Informe.pdf**: Informe del trabajo realizado.

</p>


## Etapas del proyecto

### 1. Analisis Exploratorio de Datos  ([EDA](https://github.com/PaulaPerosio/PI_Analisis_Accidentes_Viales/blob/main/EDA-Homicidios.ipynb))

<p align="justify">

  Luego de la ingesta de los datos, se realizó un análisis exploratorio de los mismos en cada uno de los archivos del dataset proporcionado para este proyecto (Hechos y Víctimas). Como parte inicial del proceso de EDA, se evaluó la estructura general de los datos, la presencia de nulos, duplicados, tipos y cantidad de datos. Posteriormente, se repitió este análisis pero en cada una de las columnas que componen cada archivo y de manera mas detallada. Se realizaron también transformaciones, imputaciones o eliminaciones de datos (siendo esta última la de menor proporción).

  Este proceso de análisis se acompañó de una gran cantidad de gráficos y descripciones estadísticas para poder observar de manera clara las relaciones, tendencias o outliers en la visualización de los datos. Se utilizaron gráficos de barras por cantidad, gráficos de torta, de densidad, histogramas y matriz de correlación, entre otros.
  Este EDA, ádemas se complementó con la información propia de la página web de donde se tomó el dataset y con información de contexto; lo cual permitió entender ampliamente el comportamiento de los datos.
  Al finalizar, se crearon nuevos archivos para utilizar en el dashboard.

</p>


### 2. KPI's y EDA complementario

<p align="justify">
  
  Dentro de este proyecto se establecieron tres KPIs para medir el proceso de ciertas métricas relativas a los accidentes de tránsito y la seguridad vial.

  KPI´s desarrollados:

  + **Tasa de homicidios en siniestros viales**: (Número de homicidios en siniestros viales / Población total) * 100,000

    Objetivo: Reducir en un 10% respecto al semestre anterior

  + **Cantidad de accidentes fatales de motociclistas**

    Objetivo: Reducir en un 7% respecto al año anterior.

  + **Cantidad de accidentes fatales en cruces de calles**
  
    Objetivo: Reducir en un 7% respecto al año anterior.

  Para el desarrollo de estos KPIs se utilizaron otros datasets e información complementaria para el estudio. Debido a esto, se llevó a cabo un segundo análisis exploratorio de datos (EDA) en Power BI.Además, se aplicaron transformaciones y ajustes específicos para garantizar que los datos estuvieran en condiciones óptimas para el correcto funcionamiento del DashBoard.

</p>


### 3. Dashboard Interactivo ([Link](...))

<p align="justify">

  Se desarrolló un tablero interactivo en Power BI con el propósito de proporcionar una representación visual y dinámica de los datos, permitiendo a los usuarios explorar y comprender la información de manera efectiva. Alli se analizan los indicadores clave de rendimiento (KPIs) vinculados a la seguridad vial; acompañados de gráficos de importancia destacada. Esto posibilita la visualización dinámica y la interpretación sencilla de datos cruciales, facilitando así la toma de decisiones futuras.

</p>


### 4. Informe ([Link](https://github.com/PaulaPerosio/PI_Analisis_Accidentes_Viales/blob/main/Informe.pdf))

<p align="justify">

  Después del análisis de los datos, de establecer relaciones con otros conjuntos de datos y de evaluar el cumplimiento de los KPIs, entre otras cosas; se realizó un informe descriptivo para colaborar en la toma de decisiones futuras respecto a los accidentes viales.

</p>


## **Enlaces**

+ Acceso al Informe [Link](https://github.com/PaulaPerosio/PI_Analisis_Accidentes_Viales/blob/main/Informe.pdf)

+ Acceso al Dashboard [Link](...).

+ Acceso a las bases de datos [Link](https://data.buenosaires.gob.ar/dataset).


## **Contacto**

+ Paula Perosio [LinkedIn](https://www.linkedin.com/in/paula-perosio/)







