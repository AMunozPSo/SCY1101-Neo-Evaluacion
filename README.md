# SCY1101-Neo-Evaluacion
# Proyecto: Clasificación de Asteroides Cercanos a la Tierra (NEO)
**Asignatura:** SCY1101 - Programación para la Ciencia de Datos  
**Evaluación:** Parcial N°2  

## Integrantes
- Felipe Araya
- Sofia Cortese
- Antonia Muñoz

## Descripción
Proyecto de machine learning aplicado al dataset de Near Earth Objects (NEO) de la NASA. Se implementan y comparan modelos supervisados (Regresión Logística, Random Forest, Árbol de Decisión) y técnicas no supervisadas (PCA, K-Means), con optimización de hiperparámetros mediante GridSearchCV y RandomizedSearchCV.

## Estructura del proyecto
```
proyecto_neo_nasa/
├── data/
│   ├── raw/
│   │   └── neo.csv                       # Dataset original de NASA
│   └── processed/
│       └── neo_clean.csv                 # Dataset preprocesado generado por el notebook
├── notebooks/
│   └── neo_evaluacion2.ipynb   # Notebook principal
└── README.md
```
## Dependencias
pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

## Cómo reproducir
1. Abrir `notebooks/neo_evaluacion.ipynb` en Google Colab
2. Subir `data/raw/neo.csv` al entorno de Colab
3. Ejecutar las celdas en orden
