🎯 Objetivo del Proyecto

El propósito de este proyecto es realizar un análisis de datos exhaustivo sobre cuatro tiendas minoristas (Tienda 1 a Tienda 4) para identificar la unidad con el menor rendimiento general y justificar su recomendación de su venta.

El análisis se centra en la combinación de métricas de ventas totales, categorias y productos más vendidos, costos de envio y calificaciones de los clientes.

🛠️ Tecnologías y Librerías

El análisis fue desarrollado utilizando el ecosistema de Python para manipulación y visualización de datos.

    Lenguaje: Python 3.x

    Manipulación de Datos: pandas

    Visualización: matplotlib, seaborn

    Normalización: sklearn.preprocessing (MinMaxScaler)

📈 Metodología del Análisis

La decisión de cierre se basó en la creación de un Índice de Rendimiento Compuesto (una puntuación única por tienda) que pondera los siguientes factores:
Factor	Peso Asignado	Razón
Ventas Totales	50%	Magnitud y volumen de negocio.
Calificación Promedio	30%	Calidad, reputación y satisfacción del cliente.
Costo de Envío Promedio	20%	Eficiencia y costo operativo.

Visualizaciones Clave

    Distribución de Ventas: (Gráfico de pastel) Muestra el volumen de ingresos de cada tienda por porcentaje.

    Análisis de Categoría/Ventas (Gráfico de barras agrupadas) Comparativa de Ventas de las 3 Categorías Principales por Tienda

    Análisis de Categoría/Producto: (Gráfico de Barras Agrupadas) Compara la magnitud de las ventas en las categorías principales vs el producto más vendido de cada tienda.

    Gráfico de Rendimiento Compuesto (Burbujas): Visualiza las cuatro tiendas simultáneamente en función de sus Ventas (Eje X), Calificaciones (Eje Y) y Costo Operativo (Tamaño de la Burbuja).

🚀 Resultados y Recomendación

Tras aplicar el Índice de Rendimiento y analizar las métricas de magnitud:

    Tiendas de Mejor Rendimiento: Tiendas [2 y 3].

    Tiendas de Peor Rendimiento: Tiendas [1 y 4].

Recomendación Final

Se recomienda la venta de la Tienda 4 debido a que obtuvo el índice de rendimiento más bajo al presentar consistentemente:

    Las ventas totales más bajas (o de las más bajas).

    Las peores calificaciones promedio de los clientes.

    El costo de envío promedio (gasto operativo) más alto.
