# Análisis de ventas para optimizar la rentabilidad y toma de decisiones comerciales

## Descripción del Proyecto
Este proyecto realiza un análisis de un conjunto de datos de ventas con el objetivo de identificar tendencias, productos más rentables, desempeño de tiendas y vendedores, y proporcionar recomendaciones para la toma de decisiones comerciales.

El análisis incluye herramientas como Python (Pandas, NumPy, Matplotlib), Excel, y se puede complementar con SQL y dashboards para visualización avanzada.

## Objetivo
- Identificar los productos que generan más ingresos.
- Evaluar el desempeño de las tiendas y vendedores.
- Detectar tendencias de ventas por mes y categoría.
- Generar insights accionables para optimizar la estrategia de ventas.


## Dataset
El conjunto de datos contiene **500 registros de ventas** con la siguiente información:
- Fecha
- Tienda
- Categoría de producto
- Vendedor
- Producto
- Cantidad
- Precio
- Total de la venta

## Análisis realizados
- Ventas totales del negocio
- Ticket promedio por venta
- Ventas por tienda
- Productos más vendidos
- Rendimiento por categoría
- Desempeño de vendedores
- Tendencia de ventas por mes

## Herramientas utilizadas
- Python (Pandas, Numpy, Matplotlib)
- Excel

## Análisis realizados
- Ventas totales y ticket promedio
- Análisis por tienda y vendedor
- Identificación de productos más rentables
- Tendencias temporales de ventas

## Insights Clave

## 1. Rendimiento General
Ventas totales: S/ 2,035,144.73
Ticket promedio por venta: S/ 4,070.29

## 2. Productos más vendidos
- El Puzzle 1000 piezas es el producto que más ingresos genera (S/ 127,851.96), aunque no es el más vendido en unidades.
- Algunos productos con muchas unidades vendidas (Cafetera Delonghi, Perfume Dior) generan ingresos menores.

Recomendación
Priorizar marketing y stock en productos que generan más ingresos, no solo en los más vendidos por cantidad.


## 3. Desempeño por Tienda

| Tienda | Ventas        |
| ------ | ------------- |
| E      | S/ 463,384.73 |
| D      | S/ 431,107.13 |
| A      | S/ 424,228.05 |
| B      | S/ 384,941.41 |
| C      | S/ 331,483.41 |

Recomendación:
Analizar estrategias de la Tienda E para replicarlas en tiendas con menor desempeño (C y B).


## 4. Desempeño por vendedor
José (S/ 293,871.59) y Pedro (S/ 291,807.96) lideran ventas.
Rosa (S/ 188,165.30) tiene menor rendimiento.

Recomendación:
- Capacitación y seguimiento a vendedores con bajo desempeño.
- Incentivos por metas para mejorar resultados individuales.

## 5. Tendencas por Mes
| Mes  | Ventas                       |
| ---- | ---------------------------- |
| 3    | S/ 293,002.56                |
| 1    | S/ 232,293.16                |
| 2    | S/ 221,013.98                |
| 6–12 | S/ 96,956.75 – S/ 143,129.23 |

Insight:
Hay estacionalidad clara: caída de ventas de junio a diciembre.

Recomendación:
Implementar campañas promocionales en meses de baja demanda.

## 6. Rendimiento por Categoria

| Categoría   | Ventas        |
| ----------- | ------------- |
| Hogar       | S/ 395,862.04 |
| Juguetes    | S/ 359,299.37 |
| Ropa        | S/ 337,784.71 |
| Electrónica | S/ 331,688.48 |
| Belleza     | S/ 312,072.66 |
| Deportes    | S/ 298,437.47 |

Recomendación:
Mantener stock óptimo en Hogar y Juguetes.
Impulsar ventas de categorías con menor desempeño a través de promociones o bundles.

## Conclusión
El análisis permite tomar decisiones estratégicas basadas en datos, identificando los productos, tiendas, vendedores y meses que requieren atención o potenciación, y ofreciendo recomendaciones claras para mejorar la rentabilidad y eficiencia comercial.
