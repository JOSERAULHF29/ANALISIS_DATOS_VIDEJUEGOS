🎮 Proyecto de Análisis de Datos: Mercado Global de Videojuegos


Este repositorio contiene un proyecto integral de Ciencia de Datos que abarca desde la limpieza (ETL) hasta la visualización estratégica del dataset vgsales. El objetivo es identificar patrones de éxito, ciclos de vida de productos y diferencias culturales en el consumo de videojuegos.

⚙️ Flujo de Trabajo (Pipeline)
1. Ingeniería de Datos (ETL)
Carga: Ingesta del dataset original vgsales.csv.

Limpieza: Tratamiento de valores nulos y estandarización de tipos de datos.

Transformación: Creación de tablas pivote y agrupaciones para preparar los datos para el análisis visual.

📊 Análisis Visual (6 Gráficos Clave)
El estudio presenta un Gráfico de Barras comparando ventas regionales por género y una Línea de tendencia (Roja) para el histórico global de ventas. Se incluye un Gráfico Circular (Pie) de promedios por género para medir rentabilidad, junto a un Stackplot que muestra la evolución de la cuota de mercado a través del tiempo. Por último, se analiza el ciclo de vida de PS3 vs PS4 con Líneas comparativas y se detectan diferencias culturales entre EE.UU. y Japón mediante un Mapa de Calor (Heatmap).

🧠 Insights y Hallazgos
Eficiencia vs. Volumen: El análisis de la variable personalizada de "Calidad" (promedio de ventas) destaca a publishers como mixi, Inc, Wizard Video Games y Westwood Studios con un score perfecto de 1.0, demostrando alta eficiencia.

Divergencia Cultural: El Heatmap confirma estadísticamente que Japón es un mercado aislado con preferencias únicas, mientras que Norteamérica y Europa muestran una correlación más fuerte.

🛠️ Tecnologías Utilizadas
Python: Lenguaje principal.

Pandas: Manipulación de DataFrames y agrupaciones.

Matplotlib: Generación de gráficos de líneas, barras, pastel y stackplot.

Seaborn: Visualización estadística avanzada (Heatmap).
