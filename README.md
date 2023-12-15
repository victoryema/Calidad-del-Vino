# Modelos de Regularización para la Predicción de Calidad del Vino

## Descripción
Este proyecto se centra en la predicción de la calidad del vino utilizando modelos de regularización como Ridge, Lasso y ElasticNet. Se realiza un análisis exploratorio de datos, visualización de variables y se escalan las características antes de ajustar los modelos. Se comparan y evalúan los resultados de los tres métodos de regularización.

## Instrucciones de Uso
- Clona este repositorio en tu máquina local.
- Asegúrate de tener las dependencias instaladas ejecutando pip install -r requirements.txt.
- Ejecuta el notebook Jupyter Prediccion_Calidad_Vino.ipynb para explorar el análisis y los modelos.

## Dependencias
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter (para ejecutar el notebook)

## Estructura del Proyecto
- Prediccion_Calidad_Vino.ipynb: Notebook principal con el código y análisis.
- winequality-red.csv: Conjunto de datos utilizado.
- README.md: Documentación del proyecto.
- requirements.txt: Lista de dependencias y versiones.

## Conjunto de Datos
El conjunto de datos incluye información sobre la composición química del vino, como ácidos, azúcares, dióxido de azufre, densidad, pH, sulfatos, alcohol, y la calidad del vino según evaluaciones de expertos.

## Análisis Exploratorio de Datos (EDA)
Se realiza un análisis detallado, incluyendo visualizaciones sobre la distribución de variables y la relación entre las características y la calidad del vino.

## Modelos Utilizados
Se ajustan modelos RidgeCV, LassoCV y ElasticNetCV y se evalúan en términos de Median Absolute Error (MAE) y Root Mean Squared Error (RMSE). Se selecciona el mejor modelo en base a estas métricas.

## Resultados
El modelo RidgeCV presenta un mejor desempeño, con los valores más bajos tanto para MAE como para RMSE. Se realiza un análisis de los coeficientes de los modelos, destacando las variables que más influyen positiva o negativamente en la calidad del vino.

## Autor
Víctor Urra

## Agradecimientos
Agradezco a las bibliotecas de código abierto utilizadas.
