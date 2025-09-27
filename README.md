# Proyecto Integrador – Fase de Preparacion y Procesamiento de datos 

Este repositorio documenta la **fase de preparación y procesamiento de datos** del Proyecto, enfocado en la **clasificación de nódulos tiroideos** (benignos vs. malignos) a partir de imágenes ecográficas.

La glándula tiroides cumple un rol fundamental en el organismo, y los nódulos que se forman en ella pueden representar un desafío diagnóstico. El objetivo de esta fase es **estructurar un pipeline robusto y reproducible** que siente las bases para un modelo predictivo confiable en contextos clínicos.

---

##  Contenido del Proyecto

Las etapas cubiertas en esta fase incluyen:

1. **Análisis Exploratorio de Datos (EDA):**  
   - Revisión de calidad y estructura de los datos.  
   - Análisis estadístico de intensidad, contraste, entropía y densidad de bordes.  
   - Identificación de outliers y desbalance de clases.  

2. **Limpieza de Datos:**  
   - Validación de formatos y consistencia.  
   - Normalización de intensidades y estandarización de variables tabulares.  
   - Estrategia de tratamiento de outliers y duplicados.  

3. **Feature Engineering Avanzado:**  
   - Creación de variables derivadas (intensidad, contraste, entropía, bordes).  
   - Selección de atributos relevantes mediante ANOVA, Mutual Information y Random Forest.  
   - Uso de PCA para reducción de dimensionalidad.  

4. **Balanceo de Clases:**  
   - Evaluación del desbalance (377 vs. 260 imágenes).  
   - Estrategias probadas: oversampling (SMOTE), undersampling y técnicas híbridas.  
   - Priorización de **Data Augmentation** para imágenes.  

5. **Data Augmentation:**  
   - Aplicación de rotaciones, flips, zooms y variaciones de brillo/contraste.  
   - Incorporación de ruido gaussiano controlado.  
   - Impacto en la robustez y reducción de overfitting.  

6. **Partición Estratificada de Datos:**  
   - División en entrenamiento (70%), validación (15%) y prueba (15%).  
   - Verificación de proporciones y ausencia de data leakage.  

7. **Pipeline de Preprocesamiento Automatizado:**  
   - Diseño modular y parametrizable.  
   - Logging de transformaciones y validación de robustez.  

---

##  Reportes Disponibles

Se incluyen dos versiones del documento:

- 📘 **Análisis Detallado – Fase de Preparación y Procesamiento de Datos**  
  [Descargar en Word](./ANALISIS_DETALLADO.docx) | [Descargar en PDF](./ANALISIS_DETALLADO.pdf)  

- 📘 **Proyecto Integrador – Fase de Preparación y Procesamiento de Datos**  
  [Descargar en Word](./PROYECTO_INTEGRADOR.docx) | [Descargar en PDF](./PROYECTO_INTEGRADOR.pdf)  

---

##  Tecnologías Utilizadas

- Python (Jupyter Notebook)  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-Learn  
- TensorFlow / Keras  

---

##  Autores

**Christian Garcia**  
**Byron Piedra**  
