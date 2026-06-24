# Data-Science-III-Unidad-2-An-lisis-de-sentimiento
Procesamiento de Texto y Análisis de Sentimiento

# 🚀 NLP Lab: Procesamiento de Texto y Análisis de Sentimiento

¡Hola! En este repositorio comparto mis desarrollos y laboratorios prácticos enfocados en **Procesamiento de Lenguaje Natural (NLP)** y **Ciencia de Datos**, aplicados a casos de negocio reales utilizando Python.

El proyecto abarca desde la limpieza inicial de texto hasta la evaluación de modelos de clasificación semántica.

---

## 🛠️ Contenido del Repositorio

### 1. Extracción y Limpieza con Expresiones Regulares (Regex)
* **Objetivo:** Automatizar la extracción de datos críticos desde texto corporativo no estructurado (logs, notas de CRM, correos).
* **Patrones identificados:** Emails, fechas válidas (formatos `DD/MM/YYYY` y `DD-MM-YYYY`) y números de teléfono en múltiples formatos complejos (con paréntesis, guiones y pegados).
* **Tecnologías:** Módulo `re` de Python, `pandas`.

### 2. Análisis de Sentimiento: Enfoque Léxico vs. Modelos Preentrenados
* **Objetivo:** Comparar el rendimiento de un diccionario de palabras clave construido manualmente contra un modelo preentrenado para clasificar reseñas de clientes.
* **Dataset:** Muestra real de calificaciones extraída directamente de **Yelp Reviews** mediante la API de `kagglehub`.
* **Pipelines Evaluados:**
  1. *Clasificador Léxico:* Lógica personalizada de conteo de palabras polarizadas.
  2. *TextBlob:* Procesamiento avanzado utilizando la polaridad léxica y reglas contextuales nativas de la librería.
* **Métricas de Clasificación:** Evaluación y comparación utilizando *Accuracy*, *Precision*, *Recall* y *F1-Score* para diagnosticar el comportamiento de los modelos frente al lenguaje natural real.

---

## 📊 Conclusiones Principales del Laboratorio

* **Limitación Léxica:** El enfoque manual es rápido y transparente, pero muy rígido (sufre con modificadores como *"not great"* o palabras fuera del diccionario), lo que penaliza la *Precision*.
* **Poder del Contexto:** El modelo preentrenado (**TextBlob**) demostró mayor robustez general (F1-Score de `0.900`) gracias a su vocabulario extendido y su capacidad para procesar la intensidad y estructura de las oraciones en textos no estructurados.

---

## ⚙️ Tecnologías Utilizadas

* **Python 3.x**
* **Pandas** (Manipulación y análisis de datos)
* **TextBlob** (Procesamiento de texto y analítica de sentimiento)
* **Scikit-Learn** (Métricas de evaluación de modelos)
* **Kagglehub** (Ingesta automatizada de datasets)

---

## 🚀 Cómo Ejecutarlo

1. Clonar este repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
