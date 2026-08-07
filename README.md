# 🌱 Climate Crop Planner

## 📌 Descripción
Automatización del análisis y la planificación de campañas agrícolas mediante Excel, VBA y Open-Meteo.

<img width="1863" height="844" alt="image" src="https://github.com/user-attachments/assets/ece19fbe-3580-4806-a94a-533e79f69466" />

---

## 🎯 Objetivo
Este proyecto busca demostrar cómo herramientas ampliamente utilizadas en entornos empresariales, como Microsoft Excel, pueden combinarse con VBA, Power Query y APIs públicas para automatizar procesos de análisis y planificación agrícola.
El objetivo no fue únicamente visualizar datos climáticos, sino desarrollar una herramienta capaz de asistir en la toma de decisiones relacionadas con la planificación de campañas, reduciendo tiempos de procesamiento y facilitando la interpretación de la información.

---

## 🚀 Características

🌎 Obtención automática del clima mediante coordenadas.
📊 Análisis de campañas históricas.
📈 Planificación de campañas futuras.
⚡ Automatización mediante VBA.
☁️ Integración de API Open-Meteo.
📉 Visualización de períodos críticos mediante diagramas Gantt.

---

## 📊 Analizador Climático – Campaña 2025/26

Esta herramienta permite analizar las condiciones climáticas reales de la campaña agrícola **2025/2026** para cualquier ubicación.

A partir de las coordenadas geográficas ingresadas por el usuario, la aplicación obtiene automáticamente la información meteorológica correspondiente mediante la API de **Open-Meteo**.

Luego, ingresando los datos del cultivo:

- 🌱 Lote
- 🌽 Híbrido
- 📅 Fecha de siembra
- 🌡️ Temperatura base
- 📈 Grados Día (GDD) hasta floración

La herramienta calcula automáticamente la fecha de floración y representa el período crítico del cultivo sobre un gráfico climático que integra:

- Temperatura máxima
- Temperatura mínima
- Temperatura media
- Precipitaciones
- Diagrama tipo Gantt del período crítico

De esta forma es posible evaluar cómo influyeron las condiciones ambientales durante el desarrollo del cultivo.

---

## 📈 Planificador Climático – Proyección Histórica (15 años)

Funciona de manera similar al **Analizador Climático**. 

Solo hay que agregarle el año de siembra en el que estamos proyectandonos y de esta forma, nos va a representar en el gráfico, los periodos críticos sobre un gráfico climático que contiene eñ **promedio climático de los últimos 15 años**.

---

## 🛠️ Herramientas utilizadas

- Microsoft Excel
- Power Query
- Gráficos combinados
- Modelado y transformación de datos
- Macros VBA, con apoyo de Gemini para poder ejecutarlas.

