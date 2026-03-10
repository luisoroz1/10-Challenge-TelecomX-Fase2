# 📡 Telecom X - Fase 2: Inteligencia Predictiva y Retención Estratégica

Este repositorio contiene la segunda fase del desafío **Telecom X**, enfocada en la creación de modelos de Machine Learning para predecir la fuga de clientes (Churn) y el análisis del impacto financiero de estas decisiones.

## 🎯 Objetivo del Proyecto
Transformar datos históricos en una herramienta predictiva que permita identificar clientes en riesgo, analizando los factores críticos que impulsan la cancelación y cuantificando el ingreso mensual en riesgo.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.12
* **Bibliotecas Clave:** `pandas`, `scikit-learn`, `seaborn`, `matplotlib`
* **Entorno:** Google Colab / Jupyter Notebook

## 📊 Resultados Principales
| Métrica | Resultado |
| :--- | :--- |
| **Modelo Seleccionado** | Random Forest |
| **Poder de Discriminación (AUC)** | 0.84 |
| **Sensibilidad (Recall)** | ~80% |
| **Variable más Influyente** | Cargos Mensuales (account.Charges.Monthly) |

## 📁 Estructura del Repositorio
* `TelecomX_LATAM_FASE2.ipynb`: Notebook principal con las 7 fases del análisis.
* `requirements.txt`: Lista de dependencias para replicar el entorno.
* `LICENSE`: Archivo de licencia que rige el uso del código.

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio: `git clone https://github.com/tu-usuario/Challenge-TelecomX-Fase2.git`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Abre el notebook y ejecuta las celdas. **Nota:** Los datos se cargan automáticamente vía API desde el repositorio de la Fase 1.

## ⚖️ Licencia
Este proyecto está bajo la **Licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles sobre los permisos de uso, modificación y distribución.

---
**Desarrollado por [Luis Orozco]** - Científica de Datos en formación.
