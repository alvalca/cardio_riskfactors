# Predicción de Enfermedades Cardiovasculares usando Aprendizaje Automático

Este proyecto tiene como objetivo desarrollar un modelo predictivo utilizando técnicas de aprendizaje automático para predecir el riesgo de enfermedad cardiovascular en las personas. Se busca identificar los principales factores de riesgo asociados con las enfermedades cardiovasculares y comprender su relación con diversos aspectos demográficos, socioeconómicos y de estilo de vida.

## Descripción del proyecto

Las enfermedades cardiovasculares representan una carga significativa para la salud pública a nivel mundial. Este proyecto utiliza un conjunto de datos del Sistema de Vigilancia de Factores de Riesgo del Comportamiento (BRFSS) de los Centros para el Control y la Prevención de Enfermedades (CDC) de Estados Unidos, el cual contiene información sobre comportamientos de riesgo, prácticas preventivas y acceso a la atención médica en la población adulta. La investigación se centra en identificar patrones y relaciones entre los factores de riesgo y el desarrollo de enfermedades cardiovasculares, con el objetivo de mejorar la prevención y el manejo de estas afecciones.

## Descripción de Variables del Conjunto de Datos

El conjunto de datos contiene información sobre diversos factores de riesgo, incluyendo:

- `Factores demográficos`: edad, sexo, raza/etnia.
- `Factores de estilo de vida`: tabaquismo, consumo de alcohol, actividad física, duración del sueño.
- `Comorbilidades`: asma, cáncer, enfisema, depresión, enfermedad renal, artritis, diabetes.
- `Discapacidades`: sordera, ceguera, deterioro cognitivo, dificultades para caminar, vestirse o hacer recados.
- `Factores socioeconómicos`: nivel educativo, nivel de ingresos, zona de residencia.
- `Salud general y mental`: percepción de salud, días de mala salud física y mental.
- Historial de COVID-19.

La variable objetivo es CARDIO, que indica la presencia o ausencia de enfermedades cardiovasculares.

## Estructura del repositorio

- `tfm_cardio.ipynb`: Notebook de Jupyter que contiene todo el código del proyecto, incluyendo el preprocesamiento de datos, entrenamiento de modelos, evaluación y visualización de resultados.
- `datos/`: Carpeta que almacena los archivos de datos utilizados en el proyecto, incluyendo el conjunto de datos original y los datos preprocesados.
- `README.md`: Archivo principal de documentación del proyecto.
- `requirements.txt`: Archivo que especifica las dependencias y versiones de las bibliotecas utilizadas en el proyecto.

## Instalación

Si deseas replicar el análisis, sigue estos pasos:

1. Clona el repositorio a tu máquina local:

   ```
   git clone https://github.com/alvalca/cardio_riskfactors.git
   ```

2. Instala las dependencias necesarias:

    ```
    pip install -r requirements.txt
    ```

## Uso

1. Abre el notebook `tfm_cardio.ipynb` en Jupyter Notebook y ejecuta las celdas en orden para reproducir el análisis y generar los resultados.

`Nota`: El archivo original con extensión .xpt está comprimido, ya que sin comprimir ocupa alrededor de 1GB. Si deseas ejecutar la parte de preprocesamiento y análisis exploratorio, debes descomprimir primero el archivo LLCP2022XPT. Sin embargo, si solo deseas ejecutar los entrenamientos con el conjunto de datos ya procesado, puedes saltar a la celda correspondiente.

## Entorno

Este proyecto fue desarrollado utilizando:

- Python 3.12.2
- Jupyter Notebook 7.0.8

## Créditos

* Desarrollado por Alejandro Valderrama Cardenas como parte del Trabajo Final de Máster en Ciencia de Datos.

## Licencia

Este proyecto está bajo la licencia MIT.

