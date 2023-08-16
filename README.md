# Manejo de Datos Faltantes: Imputación

## Agradecimientos y Contexto del Curso

Antes de comenzar con la descripción del proyecto, es importante mencionar que este trabajo se realizó como parte del Curso de Manejo de Datos Faltantes de la plataforma educativa Platzi, con la valiosa guía del instructor Jesús Vélez Santiago. El curso proporcionó las bases y las herramientas necesarias para abordar con éxito el análisis y la imputación de valores faltantes en el conjunto de datos del Estudio Nacional de Examen de Salud y Nutrición (NHANES).

## Análisis de Valores Faltantes en Datos de NHANES

Este proyecto se centra en el manejo de valores faltantes en el conjunto de datos del Estudio Nacional de Examen de Salud y Nutrición (NHANES). El objetivo es explorar diferentes estrategias para abordar los valores faltantes y comprender cómo estas estrategias afectan la calidad y la interpretación de los datos.

## Introducción

En este proyecto, se exploraron y aplicaron diversas técnicas y métodos para manejar valores faltantes en los datos de NHANES. Se utilizaron herramientas de Python, como Pandas, NumPy, Matplotlib, Seaborn y scikit-learn, para llevar a cabo el análisis y la imputación de valores faltantes.

## Contenido

El proyecto se desarrolló a lo largo de los siguientes seis mensajes:

1. Exploración Inicial de Valores Faltantes: En este mensaje, se realizó una exploración inicial de la cantidad y distribución de los valores faltantes en el conjunto de datos. Se utilizaron gráficos y visualizaciones para comprender mejor la naturaleza de los valores faltantes.

2. Análisis de Patrones de Valores Faltantes: Aquí se investigaron los posibles patrones detrás de los valores faltantes. Se exploraron correlaciones y relaciones entre variables para determinar si la falta de valores estaba relacionada con ciertos factores.

3. Estrategias de Imputación Simple: En este mensaje, se examinaron estrategias simples de imputación, como la imputación por valores constantes, mediana y media. Se evaluaron las ventajas y desventajas de cada enfoque y se generaron visualizaciones para comparar los resultados.

4. Imputación Basada en Métodos Estadísticos: Se exploraron métodos más avanzados, como la imputación por interpolación y la imputación utilizando el algoritmo KNN. Se explicaron los conceptos detrás de estos métodos y se demostró cómo aplicarlos en los datos de NHANES.

5. Imputación por Modelos de Regresión: Aquí se utilizó la imputación por modelos de regresión para estimar valores faltantes basados en relaciones entre variables. Se detalló el proceso de construcción de modelos y cómo aplicarlos para llenar los valores faltantes.

6. Imputaciones Múltiples por Ecuaciones Encadenadas (MICE): Se presentó el enfoque MICE, que utiliza modelos de regresión condicional para imputar valores faltantes de manera iterativa. Se discutió la metodología y se demostró cómo implementarla en el proyecto.

## Resultados
A lo largo del proyecto, se logró:

- Identificar y entender la distribución de valores faltantes en el conjunto de datos NHANES.
- Evaluar y comparar diferentes estrategias de imputación, desde enfoques simples hasta métodos más complejos basados en modelos.
- Aplicar técnicas avanzadas como la imputación por interpolación, KNN y modelos de regresión.
- Comprender cómo la elección de una estrategia de imputación afecta la distribución de los datos y las relaciones entre variables.
- Familiarizarse con el enfoque MICE y su aplicación para imputación iterativa.

## Conclusión

El análisis de valores faltantes es un paso crucial en el proceso de análisis de datos. Elegir la estrategia adecuada depende del contexto del conjunto de datos y los objetivos del análisis. Este proyecto proporciona una introducción completa al manejo de valores faltantes y ofrece una variedad de enfoques para abordar este desafío.

# Autor
[José Pablo Cabrera Romo]

## Recursos Adicionales

Si deseas explorar más sobre cómo manejar valores faltantes y mejorar tus habilidades en análisis de datos, aquí hay algunos recursos adicionales:

- Numpyninja's Explanation of the MICE Algorithm
- Documentación de Pandas
- Documentación de scikit-learn
- Documentación de Seaborn
  
## Installation guide

Please read [install.md](install.md) for details on how to set up this project.

## Project Organization

    ├── LICENSE
    ├── tasks.py           <- Invoke with commands like `notebook`.
    ├── README.md          <- The top-level README for developers using this project.
    ├── install.md         <- Detailed instructions to set up this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    ├── .here              <- File that will stop the search if none of the other criteria
    │                         apply when searching head of project.
    │
    ├── setup.py           <- Makes project pip installable (pip install -e .)
    │                         so imputation can be imported.
    │
    └── imputation               <- Source code for use in this project.
        ├── __init__.py    <- Makes imputation a Python module.
        │
        ├── data           <- Scripts to download or generate data.
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling.
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions.
        │   ├── predict_model.py
        │   └── train_model.py
        │
        ├── utils          <- Scripts to help with common tasks.
            └── paths.py   <- Helper functions to relative file referencing across project.
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations.
            └── visualize.py

---
