# 🎮 Video Game Sales Analysis – Ice Games Project

### 📌 Project Description  
This project simulates the analysis of historical video game sales for the online store Ice. Its goal is to identify patterns that can help forecast the commercial success of new titles and support the planning of effective advertising campaigns.

The analysis is based on an open dataset containing information on game titles, platforms, genres, user and expert ratings, ESRB classification, and regional sales.  
The focus is on the year 2016 as a reference point for building marketing strategies targeted at 2017.

---

Análisis de Ventas de Videojuegos – Proyecto Ice Games

Descripción del Proyecto

Este proyecto simula el análisis de ventas históricas de videojuegos para la tienda online **Ice**, con el objetivo de identificar patrones que permiten pronosticar el éxito comercial de nuevos títulos y planificar campañas publicitarias efectivas.

Se trabaja con un conjunto de datos abierto que incluye información sobre títulos, plataformas, géneros, calificaciones de usuarios y expertos, clasificación ESRB y ventas por región. El análisis se enfoca en el año 2016, como base para estrategias dirigidas a 2017.

---

## 📂 Dataset

- **Ruta local:** `/datasets/games.csv`
- **Características del dataset:**
  - Títulos, plataformas, género, año de lanzamiento
  - Ventas regionales: NA, EU, JP, otros
  - Puntajes de críticos y usuarios
  - Clasificación ESRB

---

##  Objetivos del Análisis

- Limpiar y preparar los datos (tipos, valores ausentes, estandarización)
- Identificar plataformas y géneros más rentables por región
- Analizar impacto de reseñas y calificaciones en ventas
- Detectar plataformas emergentes y aquellas en declive
- Realizar pruebas de hipótesis sobre calificaciones y géneros
- Generar insights accionables para estrategias de marketing en 2017

---

##  Estructura del Proyecto

### 1. **Preparación de Datos**
- Conversión de nombres de columnas a minúsculas
- Transformación de tipos de datos
- Manejo de valores ausentes y valores “TBD”
- Cálculo de columna adicional: `total_sales`

### 2. **Análisis General**
- Distribución de lanzamientos por año
- Comparación de ventas por plataforma y año
- Detección de plataformas emergentes y obsoletas
- Boxplots por plataforma para comparar ventas
- Correlación entre calificaciones y ventas

### 3. **Perfil por Región**
- Top 5 plataformas y géneros en NA, EU y JP
- Análisis de impacto de ESRB en cada región

### 4. **Pruebas de Hipótesis**
- 🧪 Hipótesis 1: Promedio de calificaciones de usuarios en Xbox One vs PC
- 🧪 Hipótesis 2: Calificaciones de usuarios en géneros Acción vs Deportes
- Definición de hipótesis nula y alternativa
- Justificación del método estadístico utilizado (p. ej., prueba t de Welch)
- Umbral de significancia (`α`) definido por el analista

---

##  Herramientas Utilizadas

- Jupyter Notebook (Python)
- Bibliotecas: pandas, matplotlib, seaborn, scipy
- Visualización de datos y análisis estadístico
- Markdown para documentar hallazgos

---

##  Notas Finales

El proyecto simula un entorno de análisis predictivo con fines educativos y estratégicos. Aunque se basa en datos ficticios o incompletos de 2016, los hallazgos y patrones son aplicables a contextos reales de planificación comercial en el sector de videojuegos.

