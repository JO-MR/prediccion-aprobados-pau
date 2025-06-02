# Predicción de Aprobados en las Pruebas de Acceso a la Universidad (PAU) - Canarias

Este proyecto aborda el análisis y la predicción del número de aprobados en las Pruebas de Acceso a la Universidad (PAU) en Canarias, mediante técnicas de Machine Learning. Se utiliza información pública, extraída del Instituto Canario de Estadística (ISTAC).

---

##  Objetivos del Proyecto

- Construir un modelo de regresión para predecir el número de aprobados en función de variables como año, sexo, tipo de acceso, convocatoria, matriculados y presentados.
- Explorar y analizar los datos para extraer insights clave.
- Simular diferentes escenarios para el año 2025 y observar su impacto en el número de aprobados.
- Visualizar los resultados para facilitar la toma de decisiones informadas.

---

##  Herramientas y Tecnologías

- **Lenguaje**: Python  
- **Bibliotecas**: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Modelo**: Random Forest Regressor  
- **Entorno de trabajo**: Google Colab  
- **Fuente de datos**: Instituto Canario de Estadística (ISTAC)

##  Estructura del Proyecto
prediccion-aprobados-pau/
├── modelado_PAU.ipynb # Notebook principal con el pipeline completo
├── README.md # Descripción del proyecto
├── datos/
│ └── ISTAC_PAUs.csv # Datos crudos de ISTAC
├── outputs/
│ └── predicciones_2025.csv # Resultados del modelo para 2025
│ └── graficos/
│ ├── aprobados_por_sexo.png
│ ├── aprobados_por_acceso.png
│ ├── aprobados_por_convocatoria.png
│ └── aprobados_acceso_sexo.png

##  Evaluación del Modelo

- **MAE (Error medio absoluto)**: 7.94  
- **RMSE (Raíz del error cuadrático medio)**: 18.55  
- **R² (Coeficiente de determinación)**: 0.9995

---

##  Visualizaciones Clave

- Comparativa de aprobados por tipo de acceso.
- Diferencias entre sexos.
- Impacto de la convocatoria ordinaria vs extraordinaria.

---

##  Conclusiones

- La variable **"Presentados"** tiene altísima correlación con los aprobados.
- Los escenarios simulados permiten ver claramente la sensibilidad del modelo a cambios en el tipo de acceso o en la convocatoria.
- El modelo puede utilizarse como herramienta de planificación para instituciones educativas.

---

##  Autor

**Nombre:** Jonás De Martín Rodríguez  
**Rol:** Científico de Datos  
**Contacto:** [jonasdemartin@gmail.com](mailto:jonasdemartin@gmail.com)

---

##  Notas Finales

Este proyecto es parte de mi portafolio profesional.  
Si estás interesado en colaborar o conocer más, ¡no dudes en contactarme!


