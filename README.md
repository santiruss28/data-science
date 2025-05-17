# 🎧 Recomendador de Canciones Similar por Características Acústicas

Este proyecto implementa un sistema de recomendación de canciones utilizando técnicas de análisis de datos y aprendizaje automático, específicamente **K-Nearest Neighbors (KNN)**, aplicado a un dataset con características musicales y emocionales.

## 📦 Contenido

- Limpieza y preprocesamiento del dataset.
- Análisis exploratorio de variables numéricas y categóricas.
- Reducción de dimensionalidad con PCA.
- Prueba de agrupamiento con DBSCAN y KMeans.
- Implementación del modelo de recomendación con KNN.

## 🛠️ Librerías utilizadas

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🚀 Cómo ejecutar

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/spotify-song-recommender.git
   cd spotify-song-recommender
   ```

2. Crear un entorno virtual e instalar dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate  # en Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Ejecutar el notebook:
   - Abrí `recomendacion de canciones.ipynb` con Jupyter Notebook o JupyterLab.

## 🎯 Cómo usar el recomendador

Dentro del notebook, podés buscar una canción específica con:

```python
entrada = 'I Go Hard'
```

Y el sistema devolverá canciones similares según sus características acústicas.

## 📊 Dataset

El dataset incluye atributos como:
- Tempo
- Loudness
- Danceability
- Energy
- Emotion
- Genre
- Entre otros

> Los datos fueron procesados para eliminar valores atípicos y normalizar los valores antes de construir el modelo.

## 📌 Conclusión

Aunque se evaluaron algoritmos de clustering, el uso de KNN resultó ser más efectivo al momento de recomendar canciones similares de forma personalizada. El sistema es modular y puede ser extendido fácilmente para incluir filtros por contexto o preferencias del usuario.

