# **Customer Churn and Contextual Chat (C4)**
Este proyecto emula un Data Product de Machine Learning (ML) completo, inspirado en la Arquitectura Arana, enfocado en la predicción de la fuga de clientes (Customer Churn) en un entorno simulado de centros comerciales (MallPlaza). El producto culmina con una estrategia de despliegue en AWS.

Incluye la ingesta de datos sintéticos, un análisis exploratorio exhaustivo, el entrenamiento y fine tuning de un modelo de clasificación, y la planificación de su puesta en producción en la nube.

##  🏗 **Módulos del Proyecto**
El proyecto está organizado en cuatro módulos principales, cubiertos por los Notebooks de Colab adjuntos, que siguen el flujo de un proyecto de Machine Learning de principio a fin:

1. **Creación de Datos Sintéticos (DSMarketWiFi_DataCreation.ipynb)**
Emula un proceso de ELT (Extracción, Carga y Transformación) para la ingesta de datos. Este módulo genera un dataset sintético que simula el comportamiento de usuarios de WiFi en un centro comercial, culminando en un conjunto de datos limpio y listo para el entrenamiento del modelo.

2. **Análisis Exploratorio de Datos (EDA) (C4_EDA.ipynb)**
Se centra en la Exploración y Visualización de Datos para identificar insights relevantes. Incluye la búsqueda de características de enriquecimiento y el desarrollo de Feature Engineering crucial para mejorar el rendimiento del modelo.

3. **Entrenamiento y Evaluación del Algoritmo (C4ML_train.ipynb)**
En este módulo, se desarrollan, entrenan y ajustan los modelos de clasificación para predecir el Churn. Se enfoca en la evaluación de métricas de ajuste, precisión y el Fine Tuning del algoritmo para lograr el mejor rendimiento.

4. **Despliegue en AWS**
Este módulo detalla la implementación y prueba del despliegue del modelo y la pipeline de datos en la nube de AWS (Amazon Web Services), demostrando la arquitectura de un Data Product operacional.
---

## 🌳 Estructura de Ramas
Este repositorio utiliza una estrategia de ramificación para gestionar el desarrollo y la producción:

* **main** -	**Producción** -	Contiene el código estable, probado y listo para producción. Las versiones desplegadas en entornos de usuario final se basan en esta rama.
* **staging**	- **Desarrollo / Proceso** -	Se utiliza para integrar las nuevas funcionalidades y correcciones antes de ser fusionadas con main. Es el entorno de prueba previo a la producción.

**Flujo de Trabajo:** Las contribuciones deben realizarse en ramas de feature o fix que se fusionan en *staging* para pruebas y validaciones, y solo cuando son estables, se fusionan a *main*.

---
# 🚀 Prerrequisitos y Configuración
Para replicar este proyecto y ejecutar los Notebooks, necesitarás:
* Python 3.x
* Librerías de ML y Data Science: pandas, numpy, scikit-learn, matplotlib, seaborn, etc.
* Credenciales de AWS: Configuración local de credenciales (Access Key ID y Secret Access Key) para la carga de datos a S3 y el despliegue del Módulo 4.
---
Este Notebook fue desarrollado por:

Cristhian Calle Severino

GitHub: https://github.com/CristhianSeverino

LinkedIn: https://www.linkedin.com/in/cristhianandrescalleseverino/
