# 🧠 MALACKATHON 2025 – Análisis de Salud Mental

Este repositorio forma parte del proyecto desarrollado para el **II Malackathon 2025**, centrado en el análisis y visualización de datos de **salud mental a partir de ingresos hospitalarios**.  
El objetivo principal es construir una **solución completa de análisis de datos e interfaz web** que facilite el trabajo de investigación de profesionales sanitarios.

---

## 🎯 Objetivo del Reto

El Malackathon 2025 propone aplicar técnicas de **ciencia de datos**, **inteligencia artificial** y **desarrollo web** para generar valor social a partir de datos reales.  
En esta edición, los participantes trabajaron con un **dataset proporcionado por la iniciativa Cyber Guardians**, garantizando la anonimización y el uso ético de los datos.

### Lo que se busca lograr:
- 🧹 **Procesamiento de datos:** preparación, limpieza y estructuración de información hospitalaria.  
- 📊 **Visualización avanzada:** creación de dashboards claros y funcionales para investigadores.  
- 🧠 **Pensamiento analítico aplicado:** identificación de patrones clínicos y tendencias en salud mental.  
- 🤖 **Integración de IA:** exploración del potencial de los modelos de lenguaje en la interpretación de datos.  
- 💬 **Impacto social y ético:** reflexión sobre la aplicación responsable del análisis de datos en contextos sanitarios.

---

## ⚙️ HITOS BÁSICOS DEL PROYECTO

### 1️⃣ Hito Base de Datos (OCI + Autonomous Database)
- Creación de una base de datos **Autonomous Database 23ai** en **Oracle Cloud Infrastructure (OCI)**.  
- Definición del esquema con las tablas proporcionadas y relaciones normalizadas.  
- Implementación de la vista `VISTA_MUY_INTERESANTE`, que sintetiza información relevante del modelo de datos.

### 2️⃣ Hito Desarrollo Web (Oracle APEX)
- Desarrollo de una **aplicación web interactiva** conectada directamente con la base de datos del Hito 1.  
- Implementación de funcionalidades de:
- Filtrado y selección dinámica de datos  
- Visualización mediante gráficos interactivos y tablas dinámicas  
- Acceso autenticado a través de **Oracle APEX Accounts**  
- La aplicación se despliega en OCI y está disponible públicamente para evaluación.  

🔗 **URL de acceso:**  
[https://gc8623ecf961b72-databasemalackathon.adb.eu-madrid-1.oraclecloudapps.com/ords/f?p=103:1:102973057004328:::::](https://gc8623ecf961b72-databasemalackathon.adb.eu-madrid-1.oraclecloudapps.com/ords/f?p=103:1:102973057004328:::::)

### 3️⃣ Hito Análisis Exploratorio de Datos
El análisis exploratorio se realizó utilizando **Python y Oracle Cloud Machine Learning**, con el objetivo de:
- Analizar la distribución de variables, valores nulos y *outliers*.  
- Estandarizar tipos de datos y aplicar codificación de variables categóricas.  
- Derivar nuevas variables e indicadores significativos para fases futuras del análisis.  
- Generar visualizaciones descriptivas que faciliten la interpretación de resultados.  

📁 Los resultados y gráficos se documentan en la carpeta `reports/`.

---

## 🧩 Arquitectura de la Solución

La arquitectura del sistema se construyó sobre un entorno **Oracle Cloud completamente gestionado**, con integración de herramientas de análisis externas.

1. **Oracle Autonomous Database (23ai)**  
   - Almacena los datos anonimizados y el modelo relacional normalizado.
2. **Oracle APEX**  
   - Proporciona la interfaz web para la interacción y visualización de los datos.  
3. **Python + Oracle Cloud ML**  
   - Permiten el análisis exploratorio y la generación de informes.  
4. **GitHub**  
   - Gestiona el control de versiones y documentación del proyecto.  

📊 Diagrama general de la arquitectura:
![Arquitectura del Proyecto](architecture_diagram.png)

---

## 🧱 Tecnologías Utilizadas

| Categoría | Tecnologías |
|------------|--------------|
| **Base de Datos** | Oracle Autonomous Database 23ai |
| **Plataforma Cloud** | Oracle Cloud Infrastructure (OCI) |
| **Frontend / Aplicación** | Oracle APEX |
| **Análisis de Datos** | Python, Pandas, NumPy, Matplotlib |
| **Control de Versiones** | Git + GitHub |
| **Documentación y Reporting** | Oracle Cloud ML Notebooks, PDF Reports |

---

## 📂 Estructura del Repositorio
  ├── apex_app/ # Archivos exportados de Oracle APEX
  
  ├── notebooks/ # Notebooks de análisis exploratorio
  
  ├── reports/ # Informes PDF con resultados y visualizaciones
  
  ├── sql/ # Scripts y consultas SQL
  
  └── README.md # Este archivo



---

## 🧾 Licencia

Este proyecto se distribuye bajo la licencia **MIT**, permitiendo su uso, modificación y redistribución con fines educativos y de investigación.

---

## 👥 Autores

Proyecto desarrollado por  
**Juan Fernando Jiménez**
**Juan Carlos Alcausa**
**Paula Ruiz**
**Alejandro Varela**
**Alberto Gallego**

Universidad de Málaga - Malackathon 2025
---

### ⭐ Si este proyecto te resulta interesante, deja una estrella en el repositorio y comparte tus sugerencias.

