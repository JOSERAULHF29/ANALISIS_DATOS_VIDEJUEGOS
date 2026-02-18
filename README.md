🎮 Proyecto de Análisis de Datos: Mercado Global de Videojuegos


Este repositorio contiene un proyecto integral de Ciencia de Datos que abarca desde la limpieza (ETL) hasta la visualización estratégica del dataset vgsales. El objetivo es identificar patrones de éxito, ciclos de vida de productos y diferencias culturales en el consumo de videojuegos.

⚙️ Flujo de Trabajo (Pipeline)
1. Ingeniería de Datos (ETL)
Carga: Ingesta del dataset original vgsales.csv.

Limpieza: Tratamiento de valores nulos y estandarización de tipos de datos.

Transformación: Creación de tablas pivote y agrupaciones para preparar los datos para el análisis visual.

2. Análisis Exploratorio (EDA)
El script genera 6 visualizaciones clave que responden a preguntas de negocio específicas:

Visualización,                             Tipo de Gráfico,                   Descripción del Análisis
Ventas por Género y Región,                Gráfico de Barras,      "Comparativa de cómo rinden los géneros (Acción, Deportes, etc.) en Norteamérica, Europa y Japón."
Ventas Totales por Año,                   Gráfico de Línea (Rojo),  Tendencia histórica que muestra el auge y la caída del volumen de ventas globales.
Promedio de Ventas por Género,            Gráfico Circular (Pie Chart), Distribución porcentual que revela qué géneros son más eficientes en promedio por título lanzado.
Evolución de Cuota de Mercado,            Stackplot (Áreas),             Visualización de cómo la popularidad de los géneros ha cambiado a lo largo de las décadas.
Ciclo de Vida: PS3 vs PS4,              Gráfico de Líneas,                 Comparativa directa del rendimiento anual entre generaciones de consolas Sony.
Correlación NA vs JP,                  Mapa de Calor (Heatmap),       Matriz que evidencia la baja correlación entre los gustos del mercado americano y el japonés.

🧠 Insights y Hallazgos
Eficiencia vs. Volumen: El análisis de la variable personalizada de "Calidad" (promedio de ventas) destaca a publishers como mixi, Inc, Wizard Video Games y Westwood Studios con un score perfecto de 1.0, demostrando alta eficiencia.

Divergencia Cultural: El Heatmap confirma estadísticamente que Japón es un mercado aislado con preferencias únicas, mientras que Norteamérica y Europa muestran una correlación más fuerte.

🛠️ Tecnologías Utilizadas
Python: Lenguaje principal.

Pandas: Manipulación de DataFrames y agrupaciones.

Matplotlib: Generación de gráficos de líneas, barras, pastel y stackplot.

Seaborn: Visualización estadística avanzada (Heatmap).
