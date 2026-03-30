# NovaRetail+ – Análisis de Factores de Comportamiento del Cliente 2024 - Proyecto Sprint 8

Este repositorio contiene el análisis correlacional desarrollado para el equipo de **Crecimiento y Retención** de NovaRetail+, plataforma de comercio electrónico en Latinoamérica.

El dataset `novaretail_comportamiento_clientes_2024` incluye 15,000 registros de clientes con variables de comportamiento, segmentación y valor económico correspondientes al cierre del año 2024.

> ⚠️ **Este es un análisis correlacional y exploratorio. Correlación ≠ causalidad.**

---

## 📂 Contenido del repositorio

- `notebooks/S8_Student_Version_Project_NovaRetail_(2).ipynb`
  → Notebook principal con exploración, preparación de datos, visualizaciones, cálculo de correlaciones, interpretación de hallazgos, limitaciones y próximos pasos.

---

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1M72ITAY9Icx8l4ct6kCOSOg4DEpgVojb?usp=sharing)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

---

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S8_Student_Version_Project_NovaRetail_(2).ipynb`
2. Conecta el entorno de ejecución en Colab o Jupyter
3. Asegúrate de que el dataset `novaretail_comportamiento_clientes_2024.csv` esté disponible en la ruta `/datasets/` o actualiza la ruta de carga en la celda correspondiente
4. Ejecuta las celdas en orden siguiendo el flujo de 6 pasos documentado en el notebook

---

## 🧠 Objetivo del análisis

Responder la pregunta de negocio:

> **¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado en NovaRetail+?**

Para ello, el proyecto construye un análisis correlacional estructurado que combina variables de comportamiento del cliente, segmentación y valor económico, con el fin de generar conclusiones claras, responsables y accionables para el equipo de Crecimiento y Retención.

### 🎯 Objetivos de aprendizaje

1. **Integrar múltiples técnicas de correlación** en un solo análisis — Pearson, Spearman, Punto biserial y V de Cramér, seleccionando el método adecuado según el tipo de variable.
2. **Identificar relaciones significativas** entre variables mediante el uso de scatterplots dirigidos y heatmaps de correlación.
3. **Detectar correlaciones engañosas** — incluyendo inflación de Pearson por distribuciones no normales y posible redundancia entre variables co-construidas.
4. **Documentar supuestos y limitaciones** de forma explícita, distinguiendo entre correlación y causalidad a lo largo de todo el análisis.
5. **Convertir hallazgos en recomendaciones de negocio** accionables para decisiones de crecimiento, retención y experimentación futura.
6. **Escribir un reporte profesional** estructurado con evidencia visual, evidencia numérica, interpretación responsable e implicaciones de negocio.

---

## 🛠️ Herramientas utilizadas

- Python 
- `pandas` · `numpy` · `matplotlib` · `seaborn` · `scipy`
- Jupyter Notebook / Google Colab

---

## 🔄 Flujo del proyecto

| Paso | Acción | Resultado |
|------|--------|-----------|
| 1 | Cargar y explorar el dataset | Estructura, tipos de datos y métricas clave |
| 2 | Preparar datos y documentar supuestos | Datos limpios y variables relevantes definidas |
| 3 | Visualizar relaciones iniciales | Heatmap de correlaciones y scatterplots dirigidos |
| 4 | Calcular correlaciones adecuadas | Pearson, Spearman, Punto biserial, V de Cramér |
| 5 | Interpretar resultados | Hallazgos con evidencia visual, numérica e implicación de negocio |
| 6 | Limitaciones y próximos pasos | Qué no se puede concluir y qué análisis seguirían |

---

👤 Autor Juan Castelblanco - Analista de Datos - Sprint 8 - Análisis de Factores de Comportamiento de Clientes 2024 NovaRetail

📝 Licencia Este proyecto es de uso educativo y forma parte del programa de análisis de datos.
