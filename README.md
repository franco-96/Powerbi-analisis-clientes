# Powerbi-analisis-clientes
Análisis demográfico y segmentación de clientes con Power BI y Excel.
# 📊 Análisis Demográfico y Segmentación de Clientes

![Dashboard de Clientes](Captura%20de%20pantalla%202026-09-23%20151711.png)

## 📌 Contexto del Proyecto
Este proyecto forma parte de un análisis exploratorio y estratégico para el departamento de Marketing. El objetivo principal es identificar el **Perfil de Cliente Ideal (ICP)** a partir de una base de datos de 999 registros, evaluando la distribución geográfica, la estructura de edad y las tendencias de adquisición a lo largo del tiempo para optimizar el gasto de campañas publicitarias.

---

## 💡 Hallazgos Clave (Insights de Negocio)
* **Público Objetivo Principal:** El **67.5% de los clientes** se concentra entre los **31 y 50 años** (346 clientes de 31-40 años y 329 clientes de 41-50 años). La edad promedio general es de **41.3 años**.
* **Segmento Joven Aislado:** El grupo de 20 a 30 años representa únicamente el 13.8% de la base (138 clientes), lo que sugiere una oportunidad de captación o una baja afinidad actual del producto con este grupo de edad.
* **Tendencia Temporal:** La adquisición de clientes se ha mantenido estable entre los años 2006 y 2019, promediando entre 50 y 75 altas anuales, con una aceleración notable previa a 2020.

---

## 🛠️ Herramientas y Transformaciones Realizadas

* **Power Query (ETL & Limpieza de Datos):**
  * Separación de cadenas de texto complejas para aislar *Ciudad*, *Estado* y *Código Postal*.
  * Eliminación de datos redundantes o columnas en blanco.
  * Cálculo dinámico de la edad a partir de la fecha de nacimiento mediante *Antigüedad* y *Total de Años*.
  * Creación de reglas condicionales para categorizar los rangos de edad.

* **DAX (Data Analysis Expressions):**
  * `Total Clientes = COUNTROWS('Hoja1')`
  * `Edad Promedio = AVERAGE('Hoja1'[Edad])`
  * Columna calculada de `Rango de edad` mediante la función `SWITCH`.

---

## 🚀 Cómo Replicar este Proyecto
1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `Dashboard_Clientes.pbix` en **Power BI Desktop**.
3. Asegúrate de tener actualizada la versión de Power BI para explorar la interactividad del reporte.
