# Análisis de Ventas con SQLAlchemy y Jupyter

Este proyecto carga datos de ventas históricas (2017-2019) desde archivos CSV, los inserta en una base de datos SQLite usando SQLAlchemy, y permite hacer análisis exploratorios y consultas SQL directamente desde un Jupyter Notebook.

## Estructura

- `sales.csv`: Ventas diarias por tienda y producto.
- `product_hierarchy.csv`: Jerarquía y dimensiones de productos.
- `store_cities.csv`: Información de ciudades, tipos y tamaños de tiendas.
- `analisis_sqlalchemy.ipynb`: Notebook con la carga, inserción y consultas SQL.

## Tecnologías

- Python
- pandas
- SQLAlchemy
- SQLite
- Jupyter
- Visual Studio Code

## Notas importantes

🔹 Por tamaño, los archivos `sales.csv` y `ventas.db` no están incluidos en este repositorio.  
🔹 Para ejecutar el análisis, asegúrate de tener estos archivos localmente.

## ¿Qué se puede analizar?

- Ventas totales por ciudad
- Promedios de precio y cantidad por producto
- Impacto de promociones en ingresos
- Tendencias de ventas por fecha o por jerarquía de producto

## Requisitos

```bash
pip install pandas sqlalchemy jupyter matplotlib
