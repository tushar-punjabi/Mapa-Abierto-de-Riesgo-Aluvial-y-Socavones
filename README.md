# FUENTES DE DATOS PARA MAPA ABIERTO: TARAPACÁ (IQUIQUE - ALTO HOSPICIO)

## 1. INSTITUCIONES DE CHILE (Datos Locales y Suelos Salinos)

*   **SERNAGEOMIN (Geología y Remoción en Masa)**
    *   **Dato Clave:** Capas GIS de susceptibilidad de deslizamientos de tierra, fallas geológicas y estudios de suelos colapsables en Alto Hospicio.
    *   **Enlace de Descarga:** [Portal GeoMinería - SERNAGEOMIN](https://sernageomin.cl)
*   **IDE Chile (Infraestructura de Datos Geoespaciales)**
    *   **Dato Clave:** Cartografía base oficial de la Región de Tarapacá: límites urbanos, manzanas de Alto Hospicio e Iquique, y red vial regional.
    *   **Enlace de Descarga:** [Catálogo Nacional IDE Chile](https://ide.cl)
*   **Dirección General de Aguas (DGA)**
    *   **Dato Clave:** Inventario de cuencas hidrográficas y caudales de quebradas del Norte Grande.
    *   **Enlace de Descarga:** [Centro de Información de Recursos Hídricos DGA](https://mop.gob.cl)
*   **Dirección Meteorológica de Chile (DMC)**
    *   **Dato Clave:** Datos históricos y de tiempo real de milímetros de lluvia caída (Estación Diego Aracena).
    *   **Enlace de Descarga:** [MeteoChile - Dirección Meteorológica](https://meteochile.gob.cl)

## 2. AGENCIAS ESPACIALES (Satélites Mundiales para Socavones y Aluviones)

*   **Agencia Espacial Europea (ESA) - Programa Copernicus**
    *   **Dato Clave:** Satélite **Sentinel-1 (Radar SAR)** para medir el hundimiento milimétrico del suelo (InSAR) en Alto Hospicio. Satélite **Sentinel-2 (Óptico)** para mapear flujos de lodo en quebradas.
    *   **Enlace de Descarga:** [Copernicus Data Space Ecosystem](https://copernicus.eu)
*   **NASA / USGS (Estados Unidos)**
    *   **Dato Clave:** Catálogo Landsat (8 y 9) para histórico de expansión urbana sobre zonas inundables y datos globales de precipitación satelital (GPM).
    *   **Enlace de Descarga:** [USGS EarthExplorer](https://usgs.gov)
*   **NASA ARIA & JPL (Jet Propulsion Laboratory)**
    *   **Dato Clave:** Mapas automáticos de deformación de superficie y daños por catástrofes climáticas.
    *   **Enlace de Descarga:** [NASA ARIA Project](https://nasa.gov)

## 3. MODELOS DE REFERENCIA (California / Ciencia Internacional)

*   **USGS Landslide Hazards Program**
    *   **Dato Clave:** Modelos de código abierto para calcular el umbral de lluvia crítica que activa deslizamientos en cerros semiáridos.
    *   **Enlace de Descarga:** [USGS Landslides Open Data](https://usgs.gov)
*   **CIGIDEN (Chile)**
    *   **Dato Clave:** Informes técnicos, papers científicos y modelos de riesgo aluvial específicos para el Norte Grande de Chile.
    *   **Enlace de Descarga:** [Repositorio de Investigación CIGIDEN](https://cigiden.cl)

## 4. HERRAMIENTAS DE DESARROLLO (Stack Open Source sugerido)

*   **Procesamiento Masivo:** [Google Earth Engine](https://google.com) (Plataforma en la nube para procesar imágenes Sentinel y Landsat sin descargar gigabytes de datos).
*   **Software de Escritorio:** [QGIS Desktop](https://qgis.org) (Para cruzar las capas de SERNAGEOMIN con el radar de la ESA).
*   **Despliegue Web:** [MapLibre GL](https://maplibre.org) o [Leaflet](https://leafletjs.com) (Librerías JavaScript para renderizar el mapa interactivo final).
