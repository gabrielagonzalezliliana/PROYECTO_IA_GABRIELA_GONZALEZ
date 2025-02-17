# PROYECTO_IA_GABRIELA_GONZALEZ


# Presentación del Problema a Abordar
En la actualidad existen muchas empresas pequeñas que quieren empezar el camino de analizar sus  datos para obtener insights relevantes y se encuentran con  dificultades para extraer información relevante de los datos de los que disponen , y a la vez se encuentran con otro problema, que se requieren de equipos especializados con  conocimiento técnico en SQL o Python para realizar consultas y generar gráficos a través de los cuales  puedan interpretar la información, lo que limita la accesibilidad de los datos a personas que no tengan conocimientos técnicos en estos campos.
Este problema se puede observar  en el ámbito del análisis de ventas, donde las decisiones dependen de la interpretación de las tendencias de mercado.  La falta de herramientas sin tener un equipo especializado en análisis de datos dificulta que gerentes y equipos de ventas puedan analizar sus datos sin depender de analistas especializados.

# Desarrollo de la Propuesta de Solución
Para abordar esta problemática, propongo desarrollar una herramienta basada en Prompt Engineering que permita a los usuarios generar análisis de datos de ventas a partir de lenguaje natural. La solución se centrará en dos modelos de IA:
1.	Texto a Texto: Un modelo de lenguaje (Groq) interpretará las consultas en lenguaje natural y me retorna un reporte con los datos analizados.
2.	Texto a Imagen: Un modelo de generación de imágenes, con incorporacion de la imagen al reporte.

# Funcionamiento de la Herramienta
1.	El usuario sube un dataset de ventas en formato CSV. el Dataset utilizado en este caso fue: https://drive.google.com/file/d/1nM_EjkrgmGV9HnUz95RmfjHb72gOmfFm/view?usp=sharing
2.	Introduce una consulta en lenguaje natural, por ejemplo:
Actúa como un científico de datos especializado en análisis de ventas y genera un informe analítico exhaustivo basado en los insights extraídos del dataset proporcionado. El informe debe ser técnico, estructurado y respaldado por datos, destacando patrones, correlaciones y estrategias de optimización para mejorar la rentabilidad y eficiencia del negocio.

Estructura del Informe:

Resumen Ejecutivo Breve descripción del análisis realizado. Principales hallazgos sobre el comportamiento de las ventas. Contexto del negocio y su impacto en la toma de decisiones.
Exploración de Datos y Calidad del Dataset Descripción del dataset analizado: columnas, tipos de datos, valores nulos, duplicados. Estadísticas descriptivas generales. Identificación y tratamiento de valores atípicos o inconsistencias.
Análisis de Tendencias y Patrones Evolución de las ventas a lo largo del tiempo (mensual, anual, estacionalidad). Identificación de temporadas de mayor y menor demanda. Comparación del rendimiento entre distintas regiones y segmentos de clientes. Segmentación de clientes según comportamiento de compra.
Análisis de Factores Determinantes en las Ventas Impacto de variables clave: Descuentos vs. Rentabilidad: ¿Cómo afectan los descuentos al margen de ganancia? Relación entre cantidad vendida y precio promedio. Comparación de rendimiento entre distintas categorías y subcategorías de productos. Métodos de envío y su relación con la satisfacción del cliente y el valor de compra. Análisis de correlaciones: Matriz de correlación entre variables clave. Relación entre tipo de cliente, frecuencia de compra y ticket promedio.
Identificación de Anomalías y Puntos Críticos Detección de valores extremos en ventas, descuentos y cantidades. Regiones o segmentos con rendimiento inusual. Posibles errores en la captura de datos o patrones atípicos en la demanda.
Modelado Predictivo Aplicación de modelos de regresión para predecir ventas futuras. Análisis de componentes principales (PCA) para reducir dimensionalidad y mejorar la interpretación de los datos. Evaluación del modelo con métricas como R², RMSE y MAE.
Recomendaciones Estratégicas Basadas en Datos Estrategias de optimización de precios y descuentos. Mejora en la gestión de inventario y predicción de demanda. Sugerencias para personalizar la experiencia del cliente según el análisis de segmentos. Acciones para mejorar la rentabilidad y eficiencia operativa basadas en los hallazgos.
Conclusión Final y Próximos Pasos Síntesis de hallazgos clave. Recomendaciones para futuras optimizaciones y toma de decisiones basadas en datos.
En base a los datos disponibles me podrias realizar una prediccion de las ventas para los proximos 12 meses y predicciones en montos mes a mes, usando distintos modelos de machine learning, y mostrando el rendimiento de cada modelo y cual fue el modelo elegido para las predicciones.


3.	El modelo de texto a texto convierte el prompt en código Python/SQL.
4.	El código se ejecuta y me genera un reporte con los datos solicitados.
5.	El modelo de texto a imagen  genera la imagen que ze incorpora al reporte.
6.	Se descarga un pdf con el reporte generado.

   
# Justificación de la Viabilidad del Proyecto
El proyecto es viable técnicamente y factible de desarrollar con las siguientes tecnologías:
•	Lenguaje de Programación: Python.
•	Procesamiento de Lenguaje Natural (PLN): Groq
•	Manejo de Datos: Pandas.
•	Visualización: Matplotlib, Seaborn o Plotly para generar gráficos.
•	Generación de Imágenes: Deepai
•	Interfaz de Usuario: Django para permitir la carga de archivos y la interacción con los prompts.

# Conclusión
Este proyecto orientado a pequeñas empresas,  permitirá a cualquier usuario sin experiencia en programación analizar datos de ventas de manera rápida  utilizando prompts en lenguaje natural. Al combinar modelos de texto a texto para la generación de reportes y de texto a imagen para la creación de una imagen en el reporte, se ofrecerá una solución  accesible para el análisis de datos, sin la necesidad de contar con un equipo especializado.
![image](https://github.com/user-attachments/assets/2aa6eae9-1e56-44e5-bc89-35413748611c)
