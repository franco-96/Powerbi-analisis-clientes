# 📊 Demographic Analysis & Customer Segmentation / Análisis Demográfico

🌐 **Language / Idioma:** [English](#-english-version) | [Español](#-versión-en-español)

---

## 🇬🇧 English Version

An end-to-end Data Analytics project featuring demographic analysis and customer segmentation built with **Power BI**, **Power Query (ETL)**, and **Excel**.

![Customer Dashboard](Captura%20de%20pantalla%202026-09-23%20151711.png)

### 📌 Project Overview
This project was developed as an exploratory and strategic analysis for the Marketing department. The primary objective is to define the **Ideal Customer Profile (ICP)** from a dataset of 999 client records by analyzing geographic distribution, age structure, and acquisition trends over time to optimize marketing campaigns.

### 💡 Key Business Insights
* **Primary Target Audience:** **67.5% of the client base** is concentrated between **31 and 50 years old** (average customer age: 41.3 years).
* **Growth Opportunity:** The young adult segment (20–30 years old) represents only **13.8% (138 clients)**, indicating an untapped market opportunity for targeted acquisition strategies.
* **Geographic Distribution:** Solid regional presence with steady historical customer acquisition between 2006 and 2019.

### 🛠️ Technical Methodology & Stack
* **Power Query (ETL):** Data cleansing, text normalization, conditional column creation for age bracket grouping, and regional extraction.
* **DAX Calculations:** Explicit dynamic measures including `Total Customers`, `Average Age`, and segmented demographic KPIs.
* **UI/UX Design:** Structured layout using **UI Container Cards**, integrated top filter bar (**Filter Bar**), and high-contrast corporate color scheme for visual clarity.

### 📂 Repository Structure
* `Dashboard_Clientes.pbix`: Interactive Power BI dashboard file.
* `Clientes_Dataset.xlsx`: Raw Excel dataset (999 records).
* `Captura de pantalla...png`: High-resolution dashboard screenshot preview.

---

## 🇪🇸 Versión en Español

Análisis exploratorio y estratégico de datos para el departamento de Marketing enfocado en la segmentación demográfica y definición del Perfil de Cliente Ideal (**ICP**).

### 📌 Contexto del Proyecto
Este proyecto analiza una base de datos de 999 clientes para evaluar la distribución geográfica, estructura por rango de edad y tendencias de adquisición a lo largo del tiempo, permitiendo optimizar la asignación del presupuesto de marketing.

### 💡 Principales Hallazgos de Negocio
* **Concentración Clave:** El **67.5% de la cartera** se encuentra entre los **31 y 50 años** (edad promedio: 41.3 años).
* **Oportunidad de Mercado:** El segmento joven (20-30 años) representa únicamente el **13.8% de la base (138 clientes)**, lo que sugiere un nicho estratégico para campañas específicas de captación.
* **Estabilidad Histórica:** Ritmo de adquisición constante entre los años 2006 y 2019.

### 🛠️ Metodología Técnica y Herramientas
* **Power Query (ETL):** Limpieza de datos, normalización de cadenas de texto y agrupación por rangos de edad.
* **DAX:** Métricas dinámicas explícitas como `Total Clientes`, `Edad Promedio` y agregaciones demográficas.
* **Diseño UI/UX:** Maquetación mediante **UI Cards**, barra superior de filtros integrados y paleta de colores corporativa de alto contraste.

---

### 🚀 How to Replicate / Cómo Replicar
1. Clone this repository / Clona este repositorio.
2. Open `Clientes_Dataset.xlsx` to inspect the source data.
3. Open `Dashboard_Clientes.pbix` in **Power BI Desktop** to explore the interactive visual metrics and DAX model.
