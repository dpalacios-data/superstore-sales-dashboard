# Análisis de ventas — Superstore Sales (Canadá)

Proyecto de portafolio con **datos reales y públicos**, pensado para enseñar a
clientes potenciales de servicios de automatización y dashboards.

## Fuente de datos

"Superstore Sales" (Canadá): 8.399 pedidos reales, 2009-2012, con ventas, beneficio,
descuentos, coste de envío, categorías de producto y regiones. Es un dataset público
y de uso extendido en la industria como referencia para portafolios de Business
Intelligence (originalmente distribuido para prácticas de Tableau/Power BI).

Descargado desde: https://raw.githubusercontent.com/curran/data/gh-pages/superstoreSales/superstoreSales.csv

## Qué hace el proyecto

1. **`data/superstore_canada_raw.csv`** — los 8.399 pedidos originales tal como se descargan
2. **`notebooks/analisis_superstore.ipynb`** — el proceso completo, paso a paso y comentado:
   carga, limpieza mínima (nulos en margen base), y agregación por región, categoría y año
3. **`data/reporte_superstore_limpio.xlsx`** — el Excel final con tres pestañas de resumen
4. **`images/`** — los tres gráficos generados automáticamente
5. **`dashboard_superstore.html`** — el resultado visual final, en formato dashboard

## Cómo se vendería este servicio

Mismo flujo que un cliente real con su propio export de ventas: automatizar la limpieza,
agregación y generación de reporte/dashboard sin intervención manual.

**Todos los datos de este proyecto son reales y de fuente pública verificable.**
