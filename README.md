# Análisis de Tiendas (Challenge de Alura Latam)

Este proyecto realiza un análisis comparativo entre 4 tiendas a través de indicadores de rendimiento como datos de ventas, categorías, calificaciones, productos más y menos vendidos y costos de envío. El objetivo es determinar cuál de las tiendas presenta el menor desempeño global, facilitando la toma de decisiones para futuras reinversiones comerciales.

## Descripción del Proyecto

El proyecto se centra en la extracción y análisis de datos proporcionados en 4 archivos CSV de diferentes tiendas. Sobre los cuales se realizan los análisis, gráficos y mapas correspondientes.

## Instalación

### Requisitos

- Cuenta en **Google Colab** para ejecutar el archivo AluraStoreLatam.ipynb
- Python 3.11.12 o superior
- Pandas (instalar con `pip install pandas`)
- Matplotlib (instalar con `pip install matplotlib`)
- Folium (instalar con `pip install folium`)

### Archivos CSV

Los datos para este proyecto provienen de los siguientes archivos CSV:

- [tienda_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [tienda_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [tienda_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [tienda_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

## Análisis Realizado

### 1. **Análisis de Facturación**

Calcula los ingresos totales por tienda y determina cuál tienda tiene el mayor y menor ingreso.

### 2. **Ventas por Categoría**

Analiza la distribución de ventas por categoría de productos y determina las categorías más vendidas por tienda.

### 3. **Calificación Promedio por Tienda**

Calcula el promedio de las calificaciones de los clientes por tienda.

### 4. **Productos Más y Menos Vendidos**

Determina cuál es el producto más y menos vendido en cada tienda.

### 5. **Costo de Envío Promedio por Tienda**

Calcula el costo promedio de envío por tienda y compara los costos entre las diferentes tiendas.

### Gráficos

Los gráficos de los puntos (1), (2), (3) y (5) son generados con **Matplotlib** y representan visualmente los resultados del análisis de facturación, distribución de ventas por categorías, calificación promedio y costos de envío.

### **Informe Final**

El análisis comparativo concluye que **la Tienda Nº 4 presenta el menor desempeño global**, destacándose por un costo de envío promedio bajo, pero con bajos ingresos y calificaciones promedio. Se recomienda considerar la venta de esta tienda para destinar esos recursos a unidades de negocio con mejor rendimiento comercial.

### Mapas

Los mapas, incluyendo un **Heatmap de Ingresos** y un **Mapa de Calificaciones**, son generados con **Folium**, proporcionando una visualización geoespacial de los datos para evaluar el rendimiento en diferentes ubicaciones.
