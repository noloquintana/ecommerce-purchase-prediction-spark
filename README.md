# 📊 Predicción de Intención de Compra en E-commerce con Apache Spark

## 🧠 Descripción del proyecto  
Este proyecto tiene como objetivo desarrollar un modelo de Machine Learning capaz de predecir la probabilidad de que un usuario realice una compra en un sitio de e-commerce.

El modelo fue implementado utilizando **Apache Spark MLlib**, lo que permite trabajar con grandes volúmenes de datos de forma distribuida y eficiente.

---

## 🎯 Objetivo  
Construir un modelo de clasificación supervisada que permita identificar patrones en el comportamiento de los usuarios y estimar su intención de compra.

---

## 🛠️ Tecnologías utilizadas  

- Python 3.11  
- Apache Spark  
- PySpark  
- MLlib  
- DataFrames  

---

## 📁 Dataset  

Se utilizó el dataset **Online Shoppers Purchasing Intention**, el cual contiene información sobre el comportamiento de usuarios en un sitio web de e-commerce.

Incluye variables como:
- Número de visitas  
- Duración de sesión  
- Páginas vistas  
- Tipo de visitante  
- Mes  

La variable objetivo es:
- **Revenue** → indica si el usuario realizó una compra (1) o no (0)

---

## ⚙️ Metodología  

El flujo de trabajo del proyecto fue el siguiente:

1. Carga de datos con PySpark  
2. Exploración de datos (EDA)  
3. Preprocesamiento:
   - Conversión de variables categóricas (StringIndexer)  
   - Transformación de variables booleanas  
   - Creación de vector de características (VectorAssembler)  
4. División de datos (train/test)  
5. Entrenamiento del modelo (Regresión Logística)  
6. Generación de predicciones  
7. Evaluación del modelo  

---

## 📈 Resultados  

El modelo obtuvo un valor de:

👉 **AUC = 0.876**

Esto indica un buen desempeño en la capacidad de distinguir entre usuarios que realizan compras y aquellos que no.

---

## ⚠️ Consideraciones  

- El dataset presenta desbalance de clases (mayoría de usuarios no compra)  
- Se utilizó la métrica AUC-ROC para una evaluación más adecuada  

---

## 🚀 Posibles mejoras  

- Implementar modelos más avanzados (Random Forest, Gradient Boosting)  
- Aplicar técnicas de balanceo de datos  
- Optimizar hiperparámetros mediante validación cruzada  
- Desplegar el modelo en un entorno distribuido en la nube  

---

## 👨‍💻 Autor  

**Manuel Quintana**  
Data Science & Big Data  

---

## 📌 Nota  

Este proyecto forma parte del curso **Fundamentos de Big Data**, enfocado en el uso de Apache Spark para el desarrollo de soluciones de Machine Learning escalables.
