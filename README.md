# Predicción de Asistencia a Citas Médicas mediante IA

## Descripción

Tarea semana 8: Inteligencia Artificial y Aprendizaje Automático que utiliza una red neuronal para predecir la asistencia de pacientes a sus citas médicas. Además, incorpora un agente inteligente que clasifica el riesgo de inasistencia y propone acciones de seguimiento.

## Tecnologías utilizadas

- Python
- Google Colab
- TensorFlow / Keras
- Pandas y NumPy
- Scikit-learn
- Matplotlib
- SHAP

## Estructura del proyecto

El proyecto se desarrolla mediante cinco scripts:

1. **Construcción de la red neuronal:** preparación de los datos y definición de la arquitectura del modelo.
2. **Entrenamiento y evaluación:** entrenamiento de la red neuronal, control del sobreajuste y cálculo de métricas.
3. **Agente inteligente:** clasificación de pacientes según su riesgo de inasistencia y generación de recomendaciones.
4. **Evaluación del agente:** comparación entre las predicciones y los resultados reales de asistencia.
5. **Interpretabilidad y monitoreo:** análisis de las variables que influyen en las predicciones y definición de indicadores de impacto.

## Datos utilizados

El conjunto de datos contiene 150 registros de pacientes e incluye variables como edad, días de espera, ausencias previas, consultas durante el último año, distancia al centro médico, canal de confirmación y asistencia a la cita.

## Ejecución

1. Abrir los scripts en Google Colab.
2. Cargar el archivo `S8_DATASET_TAREA_SET_A_INTAA1301.xlsx`.
3. Ejecutar los scripts en orden, desde el 1 hasta el 5.
4. Revisar las métricas, los gráficos y los resultados generados.

**Umbral de clasificación:** 0,60 para la probabilidad de asistencia.

## Objetivo

Evaluar cómo una solución basada en inteligencia artificial puede apoyar el seguimiento de pacientes, facilitar la identificación de posibles inasistencias y contribuir a mejorar la gestión de las citas médicas.

## Consideraciones

Los resultados corresponden a un ejercicio académico con datos limitados. Antes de utilizar el modelo en un entorno real, se requiere validar su desempeño, reforzar la seguridad de los datos y monitorear su capacidad para detectar inasistencias.

## Autor

**Alumno:** Jorge Salas.
**Ramo:** Inteligencia artificial y aprendizaje automático.
**Carrera:** Ingeniería en informática.
