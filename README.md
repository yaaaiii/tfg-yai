# 🧬 TFG: Aplicación de la Inteligencia Artificial en Enfermedades Raras mediante Genómica

Este Trabajo de Fin de Grado propone una solución basada en redes neuronales para la identificación de mutaciones genéticas patogénicas asociadas a la retinosis pigmentaria, una enfermedad rara que provoca degeneración progresiva de la retina.

## 📌 Objetivos

* Preprocesar y unificar datos genómicos (archivos VCF, XLSX, TXT) para su análisis automático.
* Aplicar técnicas de sobremuestreo (SMOTETomek), normalización y aumento de datos para equilibrar las clases.
* Desarrollar una red neuronal convolucional (CNN) que permita clasificar mutaciones como patogénicas o no patogénicas.
* Evaluar el rendimiento del modelo con métricas como accuracy y pérdida.

## 🛠️ Tecnologías utilizadas

* Python 3.10
* Pandas, NumPy, Scikit-learn, Imbalanced-learn
* TensorFlow y Keras
* Jupyter Notebooks
* Visualización: Matplotlib, Seaborn

## 🔍 Descripción técnica

El proyecto parte de un conjunto de datos genómicos de 55 pacientes con diagnóstico de retinosis pigmentaria. Los datos son altamente desbalanceados, lo que exige el uso de técnicas como SMOTETomek, adición de ruido y regularización (L2). El modelo final es una red neuronal convolucional adaptada a datos tabulares, entrenada para predecir si una mutación es patogénica.

## 📊 Resultados destacados

* Precisión de validación alcanzada: **0.799**
* Uso exitoso de BinaryFocalCrossentropy como función de pérdida
* Mejora significativa respecto a modelos iniciales con sobreajuste

## 📚 Conclusión

El modelo demuestra que es viable aplicar redes neuronales convolucionales en problemas genómicos con pocos datos. Las técnicas empleadas permiten entrenar modelos robustos y generalizables. Este enfoque puede ser extendido a otras enfermedades raras con características similares.

## 📄 Informe

Puedes consultar el informe completo en: [`TFG_Yaiza_Escribano.pdf`](/TFG.pdf)

## 👩‍💻 Autora

Yaiza Escribano de la Torre — Ingeniería Informática, UPV

## 🧠 Palabras clave

`machine learning`, `rare diseases`, `neural networks`, `genomics`, `retinitis pigmentosa`, `SMOTETomek`, `CNN`, `BinaryFocalCrossentropy`


![Python](https://img.shields.io/badge/Python-3.10-blue)
