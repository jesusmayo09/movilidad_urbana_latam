# Analisis de Movilidad Urbana en LATAM

### Dataset 1: tomtom_traffic.csv
Registra información sobre niveles de tráfico y congestión en tiempo real en distintas ciudades monitoreadas por TomTom, una empresa global de geolocalización.

### Dataset 2: oecd_city_economy.csv
Contiene indicadores anuales sobre economía urbana, empleo, contaminación y población recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económicos).

### Herramientas

![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)

### 💡 Preguntas del negocio:

* ¿Qué ciudades presentan alta congestión y baja productividad económica?
* ¿Cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte)?
* ¿Qué variables parecen tener una relación más fuerte con el desarrollo urbano?

Flujo General del Proyecto

| Paso | Acción | Resultado esperado |
| :--- | :--- | :--- |
| **1** | Cargar y explorar los datasets | Identificar las columnas, tipos de datos, y comprender la estructura general de los archivos. |
| **2** | Limpiar y corregir formatos | Estandarizar nombres de columnas, y corregir tipos de datos. |
| **3** | Extraer el año y filtrar año 2024 | Trabajar solo con el período más reciente y relevante, el año 2024. |
| **4** | Calcular promedios de tráfico por ciudad | Obtener una vista consolidada de la movilidad urbana. |
| **5** | Combinar datasets de tráfico y economía | Unir los dos DataFrames en un solo dataset con información unificada por ciudad. |
| **6** | Visualizar relaciones entre variables | Generar gráficos para explorar patrones entre tráfico y economía. |
| **7** | Elaborar informe e incluir reflexión final | Redactar un informe ejecutivo con hallazgos, implicaciones y reflexiones personales sobre la relación entre economía y movilidad. |

