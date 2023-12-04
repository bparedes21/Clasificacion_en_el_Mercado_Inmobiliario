# Descripción del Proyecto: Análisis y Clasificación en el Mercado Inmobiliario 🏡💼

En el contexto del mercado inmobiliario colombiano, caracterizado por la constante variación de precios y el desafío de valorizar las propiedades de manera precisa, este proyecto se centra en implementar un modelo de clasificación para una importante empresa inversora. El objetivo principal es predecir la categorización de propiedades en venta, clasificándolas como "baratas" o "caras" según el criterio del valor promedio de los precios (la media), utilizando datos correspondientes al año 2020.

## Desafío del Mercado Inmobiliario 🌐📈

Los cambios constantes en los precios de los inmuebles, influenciados por las tendencias del mercado, hacen que estimar el valor de una propiedad sea una tarea compleja. En este proyecto, nos enfrentamos a la tarea de abordar esta problemática mediante la implementación de un modelo de regresión logística binaria.

## Pasos Realizados 🛠️

1. **Exploración de Datos:** Se realizó una exploración exhaustiva de los datos proporcionados, analizando variables clave y comprendiendo la estructura del conjunto de datos.

2. **Preprocesamiento de Datos:** Para preparar los datos para el modelo de regresión logística binaria, se realizaron las siguientes acciones:
   - Conversión de variables categóricas en variables dummy para el tipo de propiedad y tipo de moneda.
   - Escalado de columnas numéricas (latitud, longitud, fechas, número de baños) para que el modelo las interprete correctamente.

   Archivos resultantes:
   - `Exploring-the-data_test`
   - `Exploring-the-data_train`

3. **Predicción con Diferentes Métodos de Escalado:** Se llevó a cabo la predicción utilizando diversos métodos de preprocesamiento, como `StandardScaler`, `MinMaxScaler`, `MaxAbsScaler`, y `RobustScaler`. Los resultados se encuentran en la carpeta `jupyter_nt`.

4. **Guardado de Predicciones:** Las predicciones se guardaron en un archivo CSV con una sola columna que indica la clasificación (0 para "barato", 1 para "caro").

## Evaluación de Métodos de Escalado 📊

| Tipo de Escalado | Precisión en el Test- Test_Accuracy |
| ---------------- | --------------------- |
| StandardScaler    | 70.96%                |
| MinMaxScaler      | 70.55%                |
| MaxAbsScaler      | 70.91%                |
| RobustScaler      | 70.50%                |

## Contribución del Modelo 🚀

Este proyecto no solo proporcionará a la empresa inversora una herramienta valiosa para evaluar propiedades, sino que también permitirá una comprensión más profunda de las tendencias del mercado inmobiliario colombiano. Con la capacidad de prever la clasificación de propiedades como "baratas" o "caras", se espera que los inversores tomen decisiones más informadas y estratégicas.

¡Unite en este apasionante viaje de análisis y clasificación en el dinámico mercado inmobiliario de Colombia! 👩‍💻🏡

