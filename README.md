# Vehicle Analysis App

Este proyecto es una aplicación web desarrollada con Streamlit que permite a los usuarios realizar un análisis exploratorio de datos sobre un conjunto de datos de autos usados. La aplicación proporciona las siguientes funcionalidades:

- Mostrar un histograma de kilometraje de los coches (`odometer`).
- Mostrar un gráfico de dispersión que muestra la relación entre el kilometraje (`odometer`) y el precio (`price`).

## Estructura del Proyecto

- `app.py`: Archivo principal de la aplicación Streamlit.
- `notebooks/`: Contiene los Jupyter Notebooks utilizados para el análisis exploratorio.
- `vehicles_us.csv`: Conjunto de datos utilizado en la aplicación.
- `streamlit/config.toml`: Archivo de configuración necesario para el despliegue en Render.
- `requirements.txt`: Archivo que lista las dependencias del proyecto.

## Cómo Ejecutar la Aplicación

Para ejecutar la aplicación localmente, sigue estos pasos:

1. Asegúrate de tener el entorno virtual configurado (`vehicles_env`).
2. Instala las dependencias usando el comando:
```bash
pip install -r requirements.txt
