# 📡 Telecom X - Fase 2: Inteligencia Predictiva y Retención Estratégica

Este repositorio contiene la segunda fase del desafío **Telecom X**, enfocada en la creación de modelos de Machine Learning para predecir la fuga de clientes (Churn) y el análisis del impacto financiero de estas decisiones mediante estadística avanzada.

## 🎯 Objetivo del Proyecto
Transformar datos históricos en una herramienta predictiva que permita identificar clientes en riesgo, analizando los factores críticos que impulsan la cancelación y cuantificando el ingreso mensual que la empresa podría perder si no se toman acciones preventivas.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.12
* **Bibliotecas Clave:** `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`
* **Entorno:** Google Colab / Jupyter Notebook

## 📊 Evaluación y Comparativa de Modelos
Durante la Fase 5, se entrenaron y evaluaron dos algoritmos para determinar la mejor capacidad de respuesta ante el problema de negocio:

| Métrica | Regresión Logística | Random Forest (Seleccionado) |
| :--- | :--- | :--- |
| **Poder de Discriminación (AUC)** | ~0.83 | **0.84** |
| **Sensibilidad (Recall)** | **~80%** | ~78% |
| **Principal Fortaleza** | Detección masiva de riesgo | **Precisión y estabilidad general** |

**Nota:** Se seleccionó **Random Forest** como el modelo principal para las conclusiones estratégicas debido a su robustez y su excelente análisis de importancia de variables.

## 📁 Estructura del Repositorio
* `TelecomX_LATAM_FASE2.ipynb`: Notebook principal con las 7 fases del análisis.
* `requirements.txt`: Lista de dependencias para replicar el entorno de desarrollo.
* `LICENSE`: Licencia MIT que rige el uso y distribución del código.

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio: `git clone https://github.com/tu-usuario/Challenge-TelecomX-Fase2.git`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Abre el notebook y ejecuta las celdas. **Nota:** Los datos se cargan automáticamente vía API desde el repositorio de la Fase 1, garantizando la trazabilidad del dataset original.

## ⚖️ Licencia
Este proyecto está bajo la **Licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---
**Desarrollado por [Luis Orozco]** - Científico de Datos en formación.
