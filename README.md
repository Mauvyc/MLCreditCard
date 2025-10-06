# Proyecto de Predicción de Aprobación de Tarjetas de Crédito 💳

Este proyecto utiliza técnicas de Machine Learning para predecir si una solicitud de tarjeta de crédito será aprobada o no, basándose en diversos factores del solicitante.

## 📋 Descripción del Proyecto

El proyecto analiza un conjunto de datos de solicitudes de tarjetas de crédito, procesando tanto variables numéricas como categóricas para crear un modelo predictivo que pueda determinar la probabilidad de aprobación de una tarjeta de crédito.

## 🎯 Objetivos

- Analizar y procesar datos de solicitudes de tarjetas de crédito
- Crear un modelo de predicción preciso utilizando Regresión Logística
- Optimizar el modelo mediante técnicas de ajuste de hiperparámetros
- Evaluar el rendimiento del modelo en datos de prueba

## 🛠️ Tecnologías Utilizadas

- **Python** como lenguaje de programación principal
- **Pandas** para manipulación y análisis de datos
- **NumPy** para operaciones numéricas
- **Scikit-learn** para:
  - Preprocesamiento de datos
  - Construcción del modelo
  - Evaluación del rendimiento
  - Optimización de hiperparámetros

## 📊 Estructura del Proyecto

```
Proyecto Credit Card/
│
├── creditcard.ipynb     # Notebook principal con el análisis
├── cc_approvals.data   # Dataset de aprobaciones
├── credit_card.jpg     # Imagen ilustrativa
└── README.md          # Este archivo
```

## 📝 Metodología

El proyecto sigue los siguientes pasos:

1. **Preparación y Exploración de Datos**
   - Carga del dataset
   - Análisis exploratorio
   - Estadísticas descriptivas
   - Visualización de datos

2. **Preprocesamiento**
   - Manejo de valores faltantes
   - Codificación de variables categóricas
   - Escalado de features
   - División en conjuntos de entrenamiento y prueba

3. **Modelado**
   - Implementación de Regresión Logística
   - Entrenamiento del modelo inicial
   - Optimización de hiperparámetros mediante Grid Search

4. **Evaluación**
   - Métricas de rendimiento
   - Matriz de confusión
   - Reporte de clasificación

## 🔍 Resultados

El modelo logra predecir con precisión la aprobación de tarjetas de crédito utilizando las características proporcionadas en el dataset. Los resultados incluyen:

- Métricas de rendimiento del modelo
- Comparación entre modelo base y optimizado
- Análisis de características importantes

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/Mauvyc/MLCreditCard.git
```

2. Instala las dependencias necesarias:
```bash
pip install pandas numpy scikit-learn jupyter
```

3. Abre el notebook en Jupyter:
```bash
jupyter notebook creditcard.ipynb
```

## 📈 Futuras Mejoras

- Implementar técnicas de validación cruzada más avanzadas
- Probar diferentes algoritmos de clasificación
- Añadir visualizaciones interactivas
- Implementar feature engineering más sofisticado

## 👥 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir los cambios propuestos.


## 🤝 Contacto

- GitHub: [@Mauvyc](https://github.com/Mauvyc)


