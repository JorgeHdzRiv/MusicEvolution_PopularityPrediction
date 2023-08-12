# Ciencia de Datos - Top 10000 Songs on Spotify 1960-Now

![](./img/dataset-cover.jpg)

Este proyecto tiene como objetivo realizar un análisis profundo de la evolución de los géneros musicales a lo largo del tiempo y construir un modelo de aprendizaje automático capaz de predecir la popularidad de canciones en función de sus atributos musicales. 

Utilizaremos el conjunto de datos "Top 10000 Spotify Songs - ARIA and Billboard Charts" para lograr este objetivo.

[Datos de Kaggle](https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now)

## Tabla de Contenidos
- [Descripción](#descripción)
- [Requisitos](#requisitos)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Descripción
Realizar un análisis profundo de la evolución de los géneros musicales a lo largo del tiempo y construir un modelo de aprendizaje automático que prediga el éxito de canciones en función de sus características, utilizando el conjunto de datos "Top 10000 Spotify Songs - ARIA and Billboard Charts". Este proyecto tiene como objetivo comprender cómo los géneros musicales han cambiado a lo largo de las décadas y cómo las características musicales influyen en la popularidad de las canciones, ofreciendo insights valiosos tanto desde la perspectiva de la ciencia de datos como del aprendizaje automático.

## Requisitos
Antes de comenzar, asegúrate de tener los siguientes requisitos y dependencias instalados en tu entorno:

- **Python**: Este proyecto está desarrollado en Python. Asegúrate de tener instalada una versión de Python 3.7 o superior.

- **pip**: El sistema de gestión de paquetes de Python. Debería estar disponible por defecto si tienes una instalación de Python reciente.

- **Entorno Virtual (Opcional pero recomendado)**: Se recomienda crear un entorno virtual para este proyecto para evitar conflictos entre dependencias. Puedes usar `venv` (incluido en Python) o `conda` (si usas Anaconda).

- **Dependencias**: Las dependencias requeridas están listadas en el archivo `requirements.txt`. Puedes instalarlas utilizando el siguiente comando:
  ```bash
  pip install -r requirements.txt

## Uso

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias utilizando `pip install -r requirements.txt`.
3. Explora los notebooks en la carpeta `notebooks/` para seguir cada etapa del proyecto.
4. Ejecuta el código en los notebooks para realizar análisis y entrenar modelos.
5. Explora la carpeta `app/` para interactuar con la aplicación interactiva.


## Estructura del Proyecto

El proyecto esta organizado de la siguiente manera:

- [**data/**](data/): Carpeta que almacena el conjunto de datos.
  - [`top_songs.csv`](data/top_songs.csv): Archivo CSV con las canciones y sus atributos.

- [**notebooks/**](notebooks/): Notebooks de Jupyter para cada etapa del proyecto.
  - [`01_Exploratory_Analysis.ipynb`](notebooks/01_Exploratory_Analysis.ipynb): Análisis exploratorio de géneros y atributos.
  - `02_Data_Preprocessing.ipynb`: Preprocesamiento y limpieza de datos.
  - `03_Feature_Engineering.ipynb`: Ingeniería de características.
  - `04_Model_Training.ipynb`: Entrenamiento y evaluación de modelos.

- **src/**: Scripts y módulos reutilizables.
  - `data_loading.py`: Carga los datos desde el archivo CSV.
  - `feature_engineering.py`: Funciones para la ingeniería de características.
  - `model.py`: Define y entrena el modelo de predicción.

- **reports/**: Informes y visualizaciones generadas.
  - **figures/**: Gráficos generados en los notebooks.
  - `summary_report.md`: Resumen de los resultados y hallazgos.

- **app/** (si aplica): Carpeta para la aplicación/web interactiva.
  - **templates/**: Plantillas HTML para la interfaz.
  - **static/**: Archivos estáticos (CSS, JS, imágenes).
  - `app.py`: Código de la aplicación interactiva.

- **README.md**: Este archivo que proporciona una descripción general del proyecto.

- **requirements.txt**: Lista de paquetes y versiones requeridos para el entorno.

- **LICENSE**: Licencia del proyecto.



## Contribución
Si deseas contribuir a este proyecto, siéntete libre de hacerlo. Puedes informar problemas, proponer mejoras o enviar solicitudes de extracción. Tu colaboración es bienvenida.

## Licencia
Este proyecto está bajo la [Licencia MIT](LICENSE).

---
