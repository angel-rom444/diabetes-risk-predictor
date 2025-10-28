# Diabetes Risk Predictor
# Sistema de Predicción de Riesgo de Diabetes Tipo 2

> Proyecto de Machine Learning para identificar población en riesgo alto de desarrollar diabetes tipo 2 en México

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## Objetivo del Proyecto

Desarrollar un sistema de machine learning que identifique personas en riesgo alto de diabetes tipo 2 utilizando factores de riesgo clínicos y demográficos, con el fin de:

- Permitir intervenciones preventivas tempranas
- Reducir diagnósticos tardíos y complicaciones
- Optimizar recursos del sistema de salud

---

## Contexto

- **México:** 6to lugar mundial en prevalencia de diabetes (14.4% adultos)
- **Impacto:** 100,000+ muertes anuales, $85B MXN/año en costos
- **Oportunidad:** Identificación temprana puede reducir incidencia hasta 58%

---

## Stack Tecnológico

- **Lenguaje:** Python 3.10
- **ML:** scikit-learn, XGBoost, LightGBM
- **Visualización:** Matplotlib, Seaborn, Plotly, SHAP
- **Dashboard:** Streamlit (próximamente)

---

## Estructura del Proyecto
```
diabetes-risk-predictor/
├── data/              # Datasets (raw, processed)
├── notebooks/         # Análisis exploratorio y experimentación
├── src/               # Código Python reutilizable
├── models/            # Modelos entrenados
├── reports/           # Reportes y visualizaciones
└── app/               # Aplicación de demostración
```

---

## Quick Start
```bash
# Clonar repositorio
git clone https://github.com/angel-rom444/diabetes-risk-predictor.git
cd diabetes-risk-predictor

# Crear ambiente virtual
conda create -n diabetes-env python=3.10
conda activate diabetes-env

# Instalar dependencias
pip install -r requirements.txt

# Lanzar Jupyter
jupyter notebook notebooks/
```

---

## Roadmap

- Setup del proyecto
- Obtención y exploración de datos (EDA)
- Preprocesamiento y feature engineering
- Entrenamiento de modelos baseline
- Optimización de hiperparámetros
- Interpretabilidad (SHAP)
- Dashboard interactivo
- Documentación final

---

## Autor

**[Angel Gabriel Solis Romero]**  
Data Scientist en formación  
📧 [solromang296@gmail.com](mailto:solromang296@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/angel-romero-a47595315/)  

---

## Estado

**En Desarrollo Activo** - Fecha inicio: [28-10-2025]

---

_Proyecto desarrollado como parte de mi portafolio profesional en Data Science_
