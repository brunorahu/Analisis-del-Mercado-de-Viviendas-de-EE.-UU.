# Análisis del Mercado de Viviendas de EE. UU.
Este proyecto analiza el mercado de viviendas en los Estados Unidos utilizando el índice de Case-Shiller, con un enfoque en identificar las mejores oportunidades de inversión en la costa oeste y en mercados nacionales prometedores del año 2016. Fue realizado en Google Sheets como parte de un bootcamp de Ciencia de Datos.

---

## Tabla de Contenido

1. [Introducción](#introducción)
2. [Dataset](#dataset)
3. [Enfoque Metodológico](#enfoque-metodológico)
4. [Resultados](#resultados)
5. [Visualizaciones](#visualizaciones)
6. [Aprendizajes](#aprendizajes)
7. [Cómo Reproducir el Proyecto](#cómo-reproducir-el-proyecto)

---

## Introducción

En el contexto del 2016, el mercado de viviendas en los Estados Unidos experimentaba cambios significativos. El departamento de "Central Bank Economic Studies" necesitaba analizar los datos del índice de Case-Shiller, una métrica de referencia para precios de viviendas unifamiliares. 

El objetivo era identificar las mejores oportunidades de inversión tanto a nivel estatal como municipal, con un enfoque en la costa oeste y en mercados nacionales prometedores.

---

## Dataset

El conjunto de datos utilizado, denominado "Housing Index Data", fue proporcionado por el bootcamp a través de Google Sheets. Estos datos, originalmente recopilados por DataHub, cumplen con los principios de datos ordenados y están estructurados para facilitar el análisis. 

**Principales características del dataset:**
- Fecha de recopilación de datos.
- Índices de viviendas desglosados por estado y ciudad.
- Códigos para categorías geográficas.

---

## Enfoque Metodológico

El proyecto se estructuró ejercicios secuenciales:

1. **Preparación del dataset:**
   - Creación de una nueva columna `year` para extraer el año a partir de las fechas.

2. **Promedios nacionales:**
   - Cálculo del índice de viviendas promedio por año en los Estados Unidos.

3. **Filtrado temporal:**
   - Restricción del análisis a datos posteriores al año 2000.

4. **Análisis por estado:**
   - Filtrado para incluir solo los estados de la costa oeste: Washington, Oregón y California.

5. **Desglose estatal:**
   - Comparación del índice promedio de viviendas entre estados mediante tablas y gráficos.

6. **Análisis por ciudad:**
   - Creación de tablas dinámicas para ciudades específicas de la costa oeste.

7. **Visualizaciones detalladas:**
   - Gráficos de líneas para comparar tendencias entre estados y ciudades.

8. **Identificación de mercados prometedores:**
   - Análisis de ciudades fuera de la costa oeste con índices superiores a 100 en los últimos cinco años.

---

## Resultados

1. **Estados destacados:**
   - California lidera con el índice de viviendas más alto.
   - Washington y Oregón presentan tendencias similares, pero con menor crecimiento que California.

2. **Ciudades prometedoras:**
   - San Francisco destaca por su acelerado crecimiento, seguido por Seattle y Portland.

3. **Mercados nacionales:**
   - Identificación de ciudades fuera de la costa oeste con gran potencial de inversión.

---

## Visualizaciones

Incluye los siguientes gráficos:

- **Gráfico de líneas:** Tendencias del índice de viviendas por estado.
- **Gráfico de comparación:** Evolución del índice promedio de viviendas por ciudad.

Ejemplos de gráfico:

![Evolución del Index en ciudades del Oeste de USA](https://github.com/user-attachments/assets/9d136255-95b6-4189-948c-61c0cc61e2ef)

![Evolución del Index Promedio en los estados de CA, OR y WA](https://github.com/user-attachments/assets/98e49675-181f-4d04-aeed-44d855f693f3)

---

## Aprendizajes

- Dominio de Google Sheets para preprocesamiento y visualización de datos.
- Comprensión de cómo interpretar datos del índice de Case-Shiller.
- Desarrollo de habilidades para responder preguntas estratégicas basadas en datos.

---

## Cómo Reproducir el Proyecto

1. Descarga el dataset desde el siguiente [enlace](https://docs.google.com/spreadsheets/d/1miRvSrp356AIfZhAoa-1z40n9p5oiB4APuVJ_JPxoCw/edit?usp=sharing).
2. Abre el archivo en Google Sheets.
3. Sigue los pasos descritos en la sección de Enfoque Metodológico.
4. Analiza los datos utilizando tablas dinámicas y gráficos según corresponda.

---

¡Explora más detalles en los resultados del proyecto y comparte tus hallazgos!
