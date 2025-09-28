# Proyecto Final - Minería de Datos  
**Predicción de Éxito de Nuevos Productos en la Industria Textil**

## Descripción General  
Este proyecto es una aplicación web que integra un **frontend en [Streamlit](https://proyectofinalmineriadatosupb.streamlit.app/)** con un **backend basado en Machine Learning supervisado**.  
El objetivo es **predecir el éxito de nuevos productos o prendas** en una empresa textil de Medellín, utilizando como modelo principal un **clasificador SVM (Support Vector Machine)** entrenado con datos históricos de ventas (ventas_promedio_2025 y ventas_totales_2025)y características de los productos.  

De esta manera, la empresa puede tomar decisiones basadas en datos respecto al lanzamiento de nuevas referencias en el mercado.

---

## Características principales  
- **Frontend en Streamlit**: interfaz intuitiva, accesible desde la web, que permite al usuario ingresar datos del producto (color, talla, tipo de prenda, entre otros).  
- **Backend con Machine Learning**: modelo de clasificación supervisada con **SVM**, entrenado para predecir si un producto será exitoso o no.  
- **Pipeline de datos**: incluye preprocesamiento (entendimiento del negocio, entendimiento de los datos y preparación de datos (incluyendo un EDA)), balanceo de clases, y codificación de variables categóricas. 
- **Interpretabilidad**: resultados fáciles de entender para usuarios no técnicos.  

---

## 🛠️ Tecnologías utilizadas  
- **Lenguaje**: Python 3.x  (Numpy, Pandas, Scikit-Learn, Matplotlib, Seaborn, etc...)
- **Frontend**: [Streamlit](https://streamlit.io/)  
- **Machine Learning**:  
  - Scikit-learn (SVM, Redes Neuronales, Árboles de decisión, XGBoost, Gradient Boost, preprocesamiento, métricas, etc...)  
  - Imbalanced-learn (SMOTE/SMOTENC)  
- **Persistencia del modelo**: Pickle 
- **Entorno**: Jupyter Notebook / IDE de Python  

---

## 📊 Flujo del proyecto  
1. **Recolección de datos**: atributos de productos textiles históricos y sus ventas.  
2. **Preprocesamiento**: limpieza, balanceo de clases con SMOTENC y codificación de variables categóricas.  
3. **Entrenamiento del modelo**: aplicación del algoritmo **SVM** para clasificación.  
4. **Evaluación**: métricas como Accuracy, Precision, Recall y F1-Score.  
5. **Despliegue**: integración en Streamlit para interacción con usuarios finales.  

---

## ▶️ Uso de la aplicación  
1. Accede al frontend en Streamlit:  
   👉 [Aplicación desplegada](https://proyectofinalmineriadatosupb.streamlit.app/)  
2. Ingresa los datos del nuevo producto (color, talla, tipo de prenda, etc.).    
3. Obtendrás como resultado si el producto **tiene alta probabilidad de éxito** o **no es recomendable lanzarlo**.  

---

## 📈 Resultados esperados  
- **Apoyo a la toma de decisiones**: permite anticipar el éxito de un producto antes de invertir en producción.  
- **Reducción de riesgos**: evita pérdidas asociadas a productos con baja aceptación.  
- **Escalabilidad**: la solución puede adaptarse a otros sectores con problemas similares de predicción de éxito.  

---

## 👥 Autores  
Proyecto desarrollado como parte del curso de **Minería de Datos - Universidad Pontificia Bolivariana (UPB) - Thomas Camilo Vanegas Acevedo (https://www.linkedin.com/in/thomasvanegasdev/)**.  

---

## 📜 Licencia  
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.  
