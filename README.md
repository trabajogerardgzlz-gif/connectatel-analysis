# 📊 Proyecto 6 - Análisis de Clientes de ConnectaTel

## 📖 Descripción

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en Latinoamérica.

A partir de la información de los usuarios, los planes contratados y el uso de llamadas y mensajes, se realizó un análisis exploratorio, limpieza de datos, segmentación de clientes y generación de recomendaciones de negocio para apoyar la toma de decisiones.

---

## 🎯 Objetivos

- Explorar y comprender la estructura de los datos.
- Identificar y corregir problemas de calidad.
- Analizar el comportamiento de uso de los clientes.
- Detectar valores atípicos (outliers).
- Segmentar clientes por edad y nivel de uso.
- Generar insights y recomendaciones para el negocio.

---

## 📂 Datasets utilizados

El proyecto utiliza tres conjuntos de datos:

- **plans.csv** → Información de los planes disponibles.
- **users_latam.csv** → Información demográfica y contractual de los clientes.
- **usage.csv** → Registro histórico de llamadas y mensajes realizados por los usuarios.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

---

## 📈 Etapas del análisis

El desarrollo del proyecto siguió el siguiente flujo de trabajo:

1. Carga y exploración de datos.
2. Identificación de problemas de calidad.
3. Limpieza y estandarización de datos.
4. Análisis estadístico descriptivo.
5. Visualización de distribuciones.
6. Detección de outliers mediante el método IQR.
7. Segmentación de clientes.
8. Elaboración de insights ejecutivos y recomendaciones.

---

## 🔍 Principales hallazgos

- Se detectaron y corrigieron valores inválidos, sentinels y fechas fuera de rango.
- Se identificó que la mayoría de los clientes pertenece al segmento de **Uso medio**.
- La mayor parte de la base de clientes corresponde al grupo de **Adultos**.
- Se identificaron usuarios con consumos significativamente superiores al promedio, los cuales representan oportunidades para la creación de planes especializados.
- Se generaron recomendaciones enfocadas en la optimización de la oferta comercial y la fidelización de clientes.

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar este repositorio o descargar el notebook.
2. Colocar los archivos `.csv` dentro de la carpeta `/datasets`.
3. Abrir el notebook en **Jupyter Notebook**.
4. Ejecutar todas las celdas en orden.

---

## 👨‍💻 Autor

**Gerardo González Guzmán**

Proyecto desarrollado como parte del programa de Ciencia de Datos de TripleTen.
