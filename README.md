# Tendencias-energeticas
Análisis predictivo y de visualización de tendencias energéticas.

Objetivo del proyecto
El principal propósito fue analizar y visualizar las tendencias en las reservas de petróleo y el consumo a nivel mundial, con el fin de:
Identificación
Construir modelos predictivos para anticipar tendencias y ayudar en la toma de decisiones estratégicas.
Pasos Realizados
Carga y Exploración de Datos:
Datos utilizados:
Reservas prob
Consumo anual
Datos organizados por país o región y año (1995-202)
Se exploraron las columnas para identificar posibles valores nulos y estru
Limpieza de datos:
Se eliminaron columnas irrelevantes y se filtraron años no relevantes (fuera del rango 1995-2022).
Conversión de datos no numéricos a valores numéricos mediante el manejo de errores y valores faltantes.
Eliminación de datos duplicados y limpieza de valores extremos.
Análisis Exploratorio de Datos (EDA):
Análisis de tendencias generales a lo largo de los años para el consumo y las reservas.
Identificación de los años pico para consumo y reservas.
Uso de estadísticas descriptivas para resumir los datos (media, mediana, máximos y mínimos).
Visualizaciones:
Gráficos de líneas:
Para observar la evolución anual del consumo global de petróleo.
Para analizar cómo las reservas han cambiado con el tiempo.
Comparación de tendencias:
Un gráfico combinado que muestra tanto el consumo como las reservas, permitiendo visualizar posibles relaciones entre ambos.
Modelado Predictivo:
Regresión lineal y árboles de decisión: Se probaron modelos para predecir el consumo futuro de petróleo basado en tendencias históricas.
Random Forest: Se utiliza para obtener una estimación más precisa de las relaciones no lineales entre las variables.
Evaluación de rendimiento:
Métricas como el R² y el error cuadrático medio (MSE) fueron empleadas para evaluar el desempeño de los modelos.
Fusión de datos:
Los conjuntos de datos de consumo y reservas fueron combinados en un único DataFrame basado en el año, lo que permitió analizar su relación de manera conjunta.
Identificación de patrones: Por ejemplo, si un incremento en el consumo precede a una disminución en las reservas.
Clave de Hallazgos
Tendencias identificadas:
Consumo:
Aumento sostenido en el consumo de petróleo, con picos en ciertos años específicos, influenciados por factores económicos y tecnológicos.
Reservas:
Aunque las reservas han mostrado cierta estabilidad, en los últimos años han comenzado a disminuir en algunos países clave.
Patrones destacados:
Relación inversa: En algunos períodos, el incremento del consumo coincide con una reducción en las reservas globales.
Dependencias regionales: Diferencias significativas en las tasas de consumo y reservas entre regiones (por ejemplo, países productores frente a consumidores netos).
Resultados predictivos:
Los modelos predictivos sugieren que el consumo seguirá aumentando en las próximas décadas, pero podría desacelerarse debido a la transición hacia fuentes de energía renovable.
Las reservas probadas podrían continuar disminuyendo en ausencia de descubrimientos significativos o avances tecnológicos.
Impacto y Aplicaciones del Proyecto
Este análisis y modelado tiene aplicaciones prácticas, como:
Planificación energética: Ayuda a gobiernos y empresas a anticipar cambios en el mercado de combustibles fósiles.
Sostenibilidad: Contribuye a entender la necesidad de diversificar las fuentes de energía.
Estrategias empresariales: Informa a las empresas de energía sobre oportunidades y riesgos futuros en su industria.
Conclusión general
El proyecto proporciona un análisis completo de cómo se han comportado las reservas y el consumo de petróleo durante casi tres décadas, con herramientas analíticas y predictivas que pueden ser utilizadas para decisiones estratégicas en el ámbito energético.
