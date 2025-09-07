# EDA – Dataset de Vuelos (Planes)
*Exploratory Data Analysis & visual storytelling*

EDA del dataset de vuelos (India, 2019). Basado en ejercicios de *DataCamp*
y extendido con pasos propios de limpieza, feature engineering y visualizaciones.

---

**English summary:**  
Exploratory Data Analysis of a flights dataset (India, 2019). Based on *DataCamp* exercises 
and extended with additional cleaning, feature engineering, and visualizations.

## Contenido
- Notebook principal: `EDA_Planes_dataset.ipynb`
- Variables derivadas: 
  - `Duration_minutes`
  - `Duration_category`
  - `Total_Stops_num`

## Herramientas utilizadas
- Python (Pandas, NumPy)
- Visualización: Seaborn, Matplotlib

## Principales hallazgos
- Los vuelos cortos (Short-haul) tienen precios claramente más bajos.  
- Medium, Long-haul y Extreme duration muestran medianas similares y fuerte solapamiento.  
- Jet Airways presenta precios más altos, mientras que Air Asia y SpiceJet se ubican en el extremo inferior.  
- Los precios tienden a aumentar con la duración y el número de escalas.  

## Cómo usar
1. Clonar o descargar el repositorio completo.  
2. Ejecutar el notebook en Jupyter Notebook o Google Colab.  
   - El dataset `planes.csv` se encuentra en la carpeta `data/`.  
   - No modificar la ubicación del archivo ni del notebook para que las rutas funcionen correctamente.

## Licencia
MIT License
