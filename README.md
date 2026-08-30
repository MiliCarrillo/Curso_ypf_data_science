# EnergIA Digital: Data Science Portfolio

## Executive Summary
Este repositorio centraliza el desarrollo, análisis y experimentación de datos correspondientes al programa de Data Science de la Fundación YPF (EnergIA Digital). El enfoque principal de este workspace es la aplicación de buenas prácticas de ingeniería de software al análisis de datos, garantizando la limpieza del código y la reproducibilidad de los entornos.

## Stack Tecnológico
* **Lenguaje:** Python 3.12
* **Data Manipulation & Análisis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Entorno & Herramientas:** Jupyter Notebooks, Conda, Git

## Arquitectura del Repositorio
Para mantener la escalabilidad y el orden del proyecto, el repositorio sigue la siguiente estructura de directorios:

* `/notebooks`: Contiene el código fuente (`.ipynb`) enfocado en Exploratory Data Analysis (EDA), limpieza de datos y experimentación algorítmica.
* `/datasets`: Directorio destinado a los archivos fuente crudos y procesados. *Nota: Los binarios pesados son excluidos del control de versiones mediante `.gitignore`.*
* `requirements.txt`: Archivo de manifiesto para la replicación exacta de las dependencias y versiones del entorno virtual aislado.

## Reproducibilidad (Local Setup)
Para clonar y reproducir este entorno de desarrollo localmente:
1. Clonar el repositorio: `git clone https://github.com/tu-usuario/curso_ypf_data_science.git`
2. Crear el entorno virtual con Conda: `conda create --name ds_ypf python=3.12`
3. Activar el entorno: `conda activate ds_ypf`
4. Instalar las dependencias: `conda install pandas numpy matplotlib seaborn scikit-learn jupyter`

## Changelog / Registro de Sprints
| Fecha | Feature / Tarea | Estado |
| :--- | :--- | :--- |
| 24/08/2026 | Inicialización del workspace, configuración de entorno Conda y `.gitignore`. | `Merged` |
| 30/08/2026 | Exploratory Data Analysis (EDA) inicial utilizando Pandas y NumPy. | `Merged` |

---
## Autor
**Milagros Belén Carrillo Bumjeil**

Desarrolladora de software en etapa de graduación, expandiendo mi stack analítico y de infraestructura hacia el ecosistema de Data Science. 

* [LinkedIn](www.linkedin.com/in/milagros-carrillo-65575a2a3)
* [GitHub] (https://github.com/MiliCarrillo)