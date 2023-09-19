# Lab 4 - Mejorando el Análisis de Sentimientos con LSTM y Características Adicionales

## Resumen 

Para este laboratorio partimos del notebook `Analisis_Sentimientos_RNN.ipynb` que tiene una arquitectura secuencial con 3 capas internas. 

La idea es realizar cambios en el modelo original para alcanzar un mejor rendimiento. 

Los cambios que se pueden hacer son: 
- Hiperparámetros (tamaño de lote, número de épocas). 
- Capas utilizadas (LSTM, Dense)
- Funciones de activación (sigmoid, tanh). 
- Tipo de modelo (Secuencial vs Funcional); y los cambios estructurales que esto implica. 
- Manipulación del input (posiblemente asociado a una arquitectura funcional). 
- Cambio en la partición del dataset. 

Además de los cambios en búsqueda de rendimiento existen una serie de cambios obligatorios de la versión original. 




## Resultados


### Enfoque 1: Nueva partición del dataset (cambios menores)

**Archivo:  `Change_Split_Analisis_Sentimientos.ipynb`**



### Enfoque 2: Red neuronal funcional 1 (cambios drásticos)