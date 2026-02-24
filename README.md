📊 Análisis de Rentabilidad de Tarifas de Telecomunicaciones: Megaline

📝 Descripción del Proyecto
Este proyecto se enfoca en analizar el comportamiento de 500 clientes del operador de telecomunicaciones Megaline. El objetivo principal es determinar cuál de las dos tarifas de prepago ofrecidas (Surf y Ultimate) genera mayores ingresos para la compañía, permitiendo al departamento comercial optimizar su presupuesto publicitario.

🎯 Objetivos
Limpieza y Preparación de Datos: Procesar múltiples fuentes de datos (llamadas, mensajes, internet, usuarios y planes).

Análisis del Comportamiento del Consumidor: Analizar cuántos minutos, mensajes y MB consumen los usuarios de cada plan mensualmente.

Pruebas de Hipótesis: Aplicar métodos estadísticos para validar si existen diferencias significativas en los ingresos promedio entre los planes y las regiones.

🛠️ Herramientas y Librerías Utilizadas
Python: Lenguaje base del análisis.

Pandas: Manipulación y limpieza de estructuras de datos.

Numpy: Cálculos matemáticos avanzados.

Matplotlib & Seaborn: Visualización de tendencias y distribuciones.

Scipy (Stats): Realización de pruebas T de Student para validación de hipótesis.

🚀 Proceso de Análisis
Inicialización y Carga: Importación de 5 datasets con información de 2018.

Preprocesamiento: * Corrección de tipos de datos (fechas y IDs).

Tratamiento de valores ausentes (usuarios con planes activos).

Redondeo de duración de llamadas y consumo de datos según las políticas de Megaline.

Enriquecimiento: Cálculo mensual por usuario de minutos consumidos, mensajes enviados y volumen de datos.

Cálculo de Ingresos: Aplicación de fórmulas de tarificación para determinar el excedente de consumo y el ingreso total por cliente.

Análisis Estadístico: Comparación de medias y varianzas.

📈 Conclusiones Clave (Insights)
[Aquí puedes agregar un insight real cuando termines el notebook, por ejemplo: "El plan Ultimate genera un ingreso base más alto, pero el excedente del plan Surf lo hace competitivo en ciertos segmentos."]

La distribución de los datos muestra que los usuarios en la región de NY-NJ tienen comportamientos de consumo distintos al resto del país.
