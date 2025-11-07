# 📊 Data science en Alura Store
## 📈 Análisis de ventas y rendimiento - Alura Store Latam
Este proyecto es un Análisis Exploratorio de Datos (EDA) sobre un conjunto de datos de ventas de la tienda ficticia AluraStore Latam.

El objetivo principal es limpiar, procesar y visualizar los datos para extraer insights accionables sobre el rendimiento de las ventas, las tiendas, los productos y la logística. El análisis se realizó en un notebook de Google Colab (.ipynb).

## 🚀 Tecnologías utilizadas
Este proyecto se desarrolló enteramente en Python, utilizando las siguientes librerías:
- Pandas: Para la manipulación, limpieza y agregación de datos.
- Matplotlib: Para la creación de las visualizaciones base.
- Seaborn: Para la creación de visualizaciones estadísticas avanzadas y estéticas.
- Google Colab: Como entorno de desarrollo interactivo (notebook).

## 📊 Análisis Realizado
El notebook sigue un flujo lógico para investigar y responder preguntas clave del negocio. Los principales análisis incluyen:

### Ventas por Categoría y Tienda
Se agruparon las ventas totales (Precio) por Categoría del Producto y por tienda para entender la distribución de ingresos.
Visualización: Se utilizó un facet grid (matriz de gráficos) de Seaborn para mostrar las ventas de cada tienda dentro de su respectiva categoría, permitiendo una comparación visual rápida.

### Análisis de Productos (Best-Sellers)
Se investigó qué productos son los más importantes para el negocio desde dos perspectivas:
- Por Ingresos (Rentabilidad): Identificación del Top 10 de productos que más ingresos totales generaron (groupby().sum()).
- Por Unidades (Frecuencia): Identificación del Top 10 de productos más populares o vendidos con más frecuencia (.value_counts()).

### Rendimiento de Tiendas
Se analizaron métricas clave a nivel de tienda:
- Calificación Promedio: Se calculó la Calificación media de cada tienda para identificar la satisfacción del cliente.
- Costos de Envío: Se calculó el Costo de envío promedio por tienda para analizar la eficiencia logística y su posible impacto en las ventas.

## Autor
Niko Vidovic
