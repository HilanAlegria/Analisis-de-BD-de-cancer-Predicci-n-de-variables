Este proyecto realiza un análisis de datos y predicción de variables relacionadas con el cáncer de mama, utilizando técnicas de **machine learning** para evaluar la precisión de diferentes modelos de clasificación.

---

readme_content = """# Análisis y Predicción de Supervivencia en Cáncer de Mama

---

## 📂 Archivos del Proyecto
- **`analisis_de_bd_de_cancer_predicción_de_variables_.py`**  
  Contiene el código Python para:
  - Lectura y preprocesamiento de datos.
  - Separación en conjuntos de entrenamiento y prueba.
  - Entrenamiento de modelos:
    - Regresión Logística
    - Máquinas de Vectores de Soporte (SVM)
    - Árboles de Decisión
  - Cálculo de métricas de evaluación como `accuracy_score` y matrices de confusión.

- **`Breast cancer survival.xlsx`**  
  Dataset en formato Excel con información clínica de pacientes, utilizado para la predicción de supervivencia o diagnóstico.

---

## 🛠 Tecnologías Utilizadas
- **Python 3**
- Librerías:
  - `pandas` → Manejo y análisis de datos.
  - `scikit-learn` → Modelado y evaluación de algoritmos de machine learning.

---

## 🚀 Ejecución del Proyecto
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/nombre-repositorio.git
   cd nombre-repositorio
