# 🌱 Planificador y Analizador climático para siembra de Maíz

## 📌 Descripción
Herramienta desarrollada en Excel para automatizar el análisis y la planificación de campañas de maíz mediante datos climáticos obtenidos desde Open-Meteo, Power Query y VBA.

<img width="1865" height="822" alt="image" src="https://github.com/user-attachments/assets/bdf4e675-d230-4038-88f2-79ba1e2cde47" />

---

## 🎯 Objetivo
Este proyecto busca demostrar cómo herramientas ampliamente utilizadas en entornos empresariales, como Microsoft Excel, pueden combinarse con VBA, Power Query y APIs públicas para automatizar procesos de análisis y planificación agrícola.
El objetivo no fue únicamente visualizar datos climáticos, sino desarrollar una herramienta capaz de asistir en la toma de decisiones relacionadas con la planificación de campañas, reduciendo tiempos de procesamiento y facilitando la interpretación de la información.

---

## 📈 Todo surge de...

la evolución de mi primer proyecto de análisis climático. 
Inicialmente, la herramienta permitía analizar únicamente una campaña agrícola utilizando datos climáticos de una ubicación específica. A partir de aqui, decidí ampliar su alcance incorporando la obtención automática de datos meteorológicos mediante coordenadas geográficas y desarrollando un módulo de planificación basado en información histórica.

---

## 🚀 Características

🌎 Obtención automática del clima mediante coordenadas.

📊 Análisis de campañas históricas.

📈 Planificación de campañas futuras.

⚡ Automatización mediante VBA.

☁️ Integración de API Open-Meteo.

📉 Visualización de períodos críticos mediante diagramas Gantt.

---

## 📊📈 Analizador Climático – Campaña 2025/26

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

## 📊📈 Planificador Climático – Proyección Histórica (15 años)

Funciona de manera similar al **Analizador Climático**. 

Solo hay que agregarle el año de siembra en el que estamos proyectandonos y de esta forma, nos va a representar en el gráfico, los periodos críticos sobre un gráfico climático que contiene el **promedio climático de los últimos 15 años**.

---

## 🛠️ Herramientas utilizadas

- Microsoft Excel
- Power Query
- Gráficos combinados
- Modelado y transformación de datos
- Macros VBA con asistencia de IA para acelerar la implementación.

---

## 📈 Resultado del proyecto

Este proyecto demuestra como Excel puede evolucionar de una simple planilla de cálculo a una herramienta capaz de automatizar procesos, consumir información desde APIs externas y generar visualizaciones dinámicas para apoyar la toma de decisiones.

La integración entre VBA, Power Query y la API de Open-Meteo permitió desarrollar una solución que automatiza la obtención y el procesamiento de datos climáticos, facilitando tanto el análisis de campañas finalizadas como la planificación de futuras estrategias de siembra.

Más allá del resultado técnico, el objetivo fue desarrollar una herramienta práctica que resuelva una necesidad real mediante la automatización y el análisis de datos.

---

## 📂 Estructura del proyecto

```text
📦 climate-crop-planner
│
├── 📄 README.md
│
├── 📁 excel-files
│   ├── 📊 Analizador_siembra_maiz_2526.xlsm
│   ├── 📈 Planificador_siembra_maiz.xlsm
│   └── README.md
│
│
├── 📁 images
│   ├── calculadora_planificador.png
│   ├── planificador.png
│   ├── grafico.png
│   └── demo.gif
│
└── 📁 ejemplos
    └── 📍 coordenadas.txt
```

## 👨‍💻 Autor

Nicolás Zárate

LinkedIn: https://www.linkedin.com/in/nicolaszarate99/

GitHub: https://github.com/nicolas-zarate



