# 🚀 Análisis de los Resultados del Examen de Admisión UNMSM 2026-I con Power BI, Python y n8n 📊

## 🧠 Descripción del Proyecto
Este proyecto tiene como objetivo analizar los **resultados del examen de admisión de la Universidad Nacional Mayor de San Marcos (UNMSM) 2026-I**, integrando **automatización de datos, análisis con Python y visualización interactiva en Power BI**.

A través de un proceso automatizado, se extrajeron los datos directamente desde la página oficial de la OCA, se limpiaron y transformaron con Python, y finalmente se visualizaron mediante un dashboard dinámico en Power BI para resaltar los principales indicadores del proceso de admisión.

---

## 🔍 Extracción automatizada con n8n
- Se utilizó **[n8n](https://n8n.io/)** para automatizar la extracción de datos desde la página oficial de resultados:  
  👉 [https://admision.unmsm.edu.pe/Website20261/A/A.html](https://admision.unmsm.edu.pe/Website20261/A/A.html)
- El flujo permitió **descargar automáticamente el archivo Excel** con los resultados directamente en Google Drive.
- Tiempo total del proceso: ⚡ **37 segundos**.

---

## 🐍 Análisis y limpieza con Python (Pandas en Google Colab)
- Se realizó la **limpieza, estructuración y análisis exploratorio de datos (EDA)** utilizando **pandas**.
- Se identificaron **patrones, valores atípicos y tendencias generales**.
- Se preparó el dataset para su posterior integración en Power BI.

---

## 📊 Visualización y análisis en Power BI
El dashboard diseñado en Power BI permite visualizar de forma clara los indicadores clave:
- ✅ Número de **postulantes, ingresantes y ausentes** por carrera.
- ✅ **Puntajes mínimos, máximos y promedios** por carrera.
- ✅ Comparativas entre áreas académicas y niveles de competitividad.

---

## 💡 Resultados
Gracias a la integración de **n8n, Python y Power BI**, se logró:
- Automatizar el proceso **ETL completo (Extracción, Transformación y Carga)**.
- Reducir el tiempo de extracción de datos a segundos.
- Mejorar la precisión del análisis.
- Obtener una **visualización dinámica e intuitiva** del desempeño de los postulantes.

---

## 🧰 Tecnologías utilizadas
- 🧩 **n8n** – Automatización y Web Scraping  
- 🐍 **Python (Pandas, Colab)** – Limpieza y análisis de datos  
- 🗄️ **Excel** – Almacenamiento de datos intermedio  
- 📊 **Power BI** – Dashboard y visualización interactiva  

---

## 🧑‍💻 Autor
**Bryan Edwin Toma Rojas**  
💼 Estudiante de Ingeniería de Sistemas 
📍 Lima, Perú  
📧 bryantoma.dev@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bryan-toma-rojas-9b7826371/)
