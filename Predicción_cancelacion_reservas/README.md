# Predicción de Cancelación de Reservas

## Resumen
Este proyecto tiene como objetivo analizar patrones en la cancelación de reservas de hoteles y construir un modelo predictivo que permita identificar los factores clave asociados con este comportamiento. Esto puede ayudar a los hoteles a tomar decisiones informadas y reducir pérdidas económicas.

## Contenido del Proyecto
- **Notebook principal:** Contiene el análisis exploratorio y la creación del modelo predictivo.
- **Dataset:** Datos históricos sobre reservas, cancelaciones y características de los clientes.
- **Visualizaciones:** Gráficos que destacan las tendencias más relevantes, como cancelaciones por temporada o tipo de cliente.

## Metodología
1. **Preparación de datos:**
   - Limpieza y transformación de los datos para su análisis.
   - Identificación de valores nulos y outliers.
2. **Análisis exploratorio:**
   - Estadísticas descriptivas.
   - Visualización de correlaciones entre variables.
3. **Modelo predictivo:**
   - Selección de características relevantes.
   - Entrenamiento y evaluación de un modelo de clasificación para predecir cancelaciones.
4. **Resultados:**
   - Identificación de los factores más influyentes en las cancelaciones.
   - Métricas de evaluación del modelo (precisión, F1-Score, etc.).

## Resultados Clave
- **Factores principales:** Descubrimos que las cancelaciones están altamente correlacionadas con la duración de la estancia y la política de reembolso.
- **Modelo predictivo:** Logramos un modelo con un 85% de precisión al identificar cancelaciones.

## Herramientas y Tecnologías Utilizadas
- **Librerías de Python:** Pandas, keras, Matplotlib, Seaborn, Scikit-learn.
- **Entorno:** Jupyter Notebook.

## Cómo Ejecutarlo
1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
2. Navega a la carpeta del proyeccto:
   ```bash
   cd proyectos/prediccion_cancelacion_reservas
   ```
3. Abre el archivo cancelacion_reservas.ipynb en Jupyter Notebook.

4. Asegúrate de instalar las dependencias con:
  ```bash
 pip install -r requirements.txt
  ```
