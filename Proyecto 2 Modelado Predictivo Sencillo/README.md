# 🎯 Predicción de Supervivencia en el Titanic

Este proyecto aplica técnicas de aprendizaje supervisado para predecir la probabilidad de supervivencia de los pasajeros del Titanic. Se utiliza el dataset preprocesado previamente del proyecto 1.

## 🔧 Herramientas utilizadas

- `pandas`, `matplotlib`
- `scikit-learn`: `Pipeline`, `ColumnTransformer`, `StandardScaler`, `OneHotEncoder`, `GridSearchCV`
- Evaluación con `classification_report`, curvas ROC y métricas comparativas

## 📁 Estructura del análisis

1. **Carga de datos**
2. **Entrenamiento con modelos base**
3. **Detección de fuga de información (`alive`)**
4. **Reentrenamiento sin leakage**
5. **Optimización con `GridSearchCV`**
6. **Comparación visual (matrices de confusión, curvas ROC)**
7. **Tabla resumen de métricas**

## 📊 Resultados

| Modelo              | Accuracy | F1-score | AUC  |
|---------------------|----------|----------|------|
| Árbol de Decisión   | 0.79     | 0.72     | 0.77 |
| KNN                 | 0.82     | 0.76     | 0.86 |
| Regresión Logística | 0.84     | 0.79     | 0.88 |
| Random Forest       | 0.83     | 0.77     | 0.87 |
| SVM                 | 0.84     | 0.78     | 0.88 |

## 🧠 Conclusión

- La eliminación de la variable `alive` evitó una fuga crítica.
- `GridSearchCV` permitió mejorar el rendimiento de todos los modelos.
- `SVM` y `Regresión Logística` resultaron ser las opciones más balanceadas.

## 🚀 Cómo ejecutar

1. Clonar el repo
2. Instalar dependencias:  
   ```bash
   pip install -r requirements.txt
3. Ejecutar el notebook `modelado_titanic.ipynb`

## 📬 Contacto
📍 Publicado como parte de mi portfolio de proyectos de ciencia de datos
📫 [LinkedIn](https://www.linkedin.com/in/ojedajc/)
📂 Repositorio: [GitHub](https://github.com/jFet1/Proyectos_personales)
