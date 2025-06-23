# Análisis de Datos de Ventas de Tiendas

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar los datos de ventas de cuatro tiendas para evaluar su rendimiento individual y comparativo. Se examinan métricas clave como facturación total y promedio, ventas por categoría y producto, calificaciones de los clientes y costos de envío. El análisis busca identificar patrones, tendencias y áreas de oportunidad para mejorar el rendimiento de las tiendas.

## Datos

Los datos utilizados en este proyecto provienen de cuatro archivos CSV, cada uno representando las ventas de una tienda diferente:

* `tienda_1.csv`
* `tienda_2.csv`
* `tienda_3.csv`
* `tienda_4.csv`

Cada archivo contiene información sobre transacciones individuales, incluyendo:

* **Producto:** Nombre del producto vendido.
* **Categoría del Producto:** Categoría a la que pertenece el producto.
* **Precio:** Precio del producto.
* **Costo de envío:** Costo asociado al envío del producto.
* **Fecha de Compra:** Fecha en la que se realizó la compra.
* **Vendedor:** Nombre del vendedor que realizó la venta.
* **Lugar de Compra:** Ciudad donde se realizó la compra.
* **Calificación:** Calificación otorgada por el cliente a la transacción.
* **Método de pago:** Método utilizado para realizar el pago.
* **Cantidad de cuotas:** Número de cuotas si se pagó a crédito.
* **lat:** Latitud del lugar de compra.
* **lon:** Longitud del lugar de compra.

## Análisis Realizado

El análisis se centró en los siguientes aspectos:

1.  **Análisis de Facturación:**
    *   Cálculo de la facturación total y promedio por tienda.
    *   Identificación de los productos con mayor facturación a nivel global y por tienda.

2.  **Ventas por Categoría:**
    *   Análisis de la cantidad de ventas por categoría de producto a nivel global y por tienda.

3.  **Calificación Promedio de la Tienda:**
    *   Cálculo de la calificación promedio general y por cada tienda.

4.  **Productos Más y Menos Vendidos:**
    *   Identificación de los 10 productos más y menos vendidos a nivel global.

5.  **Categorías Más y Menos Vendidas:**
    *   Identificación de las 5 categorías más y menos vendidas a nivel global.

6.  **Envío Promedio por Tienda:**
    *   Cálculo del costo de envío promedio para cada tienda.

## Resultados y Visualizaciones

Los resultados del análisis se presentan a través de tablas y visualizaciones (gráficos de barras, gráficos de pastel y gráficos de dispersión) que ilustran los hallazgos clave en cada área analizada.

*(Aquí se incluirían las celdas de código y sus resultados de los análisis y visualizaciones realizados anteriormente en el notebook)*

## Conclusiones

Basado en los análisis realizados, se extrajeron conclusiones sobre el rendimiento de cada tienda, las categorías y productos más exitosos, la satisfacción del cliente y los costos de envío. Estas conclusiones pueden servir como base para la toma de decisiones estratégicas.

*(Aquí se incluirían las conclusiones detalladas presentadas anteriormente)*

## Cómo Ejecutar el Proyecto

Para replicar este análisis, sigue los siguientes pasos:

1.  Asegúrate de tener Python y las librerías pandas, numpy, matplotlib y seaborn instaladas.
2.  Descarga los archivos CSV de las URL proporcionadas.
3.  Ejecuta el código en un entorno Python, como un notebook de Colab o Jupyter.

## Dependencias

*   pandas
*   numpy
*   matplotlib
*   seaborn
