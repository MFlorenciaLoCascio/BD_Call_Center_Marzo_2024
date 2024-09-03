# Dashboard de Call Center - Marzo 2023

### Este proyecto presenta un análisis detallado de los registros de llamadas de un Call Center durante el mes de marzo de 2023. Los datos incluyen el ID de llamada, fecha, asistente, área, estado de resolución del llamado, velocidad de respuesta, duración de la llamada, duración con asistente en segundos e índice de satisfacción.

#### Puede visualizar el dashboard: 

# Objetivos del Análisis

### Este análisis permite identificar áreas de mejora en cuanto a la calidad de las llamadas, la satisfacción del cliente y las áreas que requieren mayor atención. Los resultados obtenidos ayudarán a optimizar el rendimiento del Call Center y a mejorar la experiencia del cliente.

# Análisis Realizado
El análisis se enfocó en responder las siguientes preguntas:

#### **1-** ¿Qué área recibe la mayor cantidad de llamados?

#### **2-** ¿Cuál es el asistente con mayor velocidad de respuesta?

**3-** ¿Cuál es la satisfacción promedio del cliente?

**4-** ¿Qué área tiene la mayor y menor satisfacción del cliente?

**5-** ¿Qué asistente tiene la mayor y menor satisfacción del cliente?

**6-** ¿Cuál es la cantidad de llamados resueltos y no resueltos?

**7-** ¿Qué asistente tiene la mayor y menor cantidad de llamados resueltos?

**8-** ¿Qué día de la semana se recibe la mayor cantidad de llamados y de qué tipo?

**9-** ¿Cuál es la cantidad total de clientes y llamados?

# Limpieza de Datos en Power Query

**1-** *Verificación y Modificación de Tipos de Datos:* Se ajustaron los tipos de datos correspondientes a cada columna para asegurar la correcta interpretación de los datos.

**2-** *Corrección de Palabras en la Columna "Área":* Se corrigieron errores y inconsistencias en los nombres de las áreas para estandarizar la información.

**3-** *Eliminación de Columnas Innecesarias:* Se eliminaron columnas que no eran relevantes para el análisis, reduciendo el tamaño del archivo y mejorando el rendimiento.

# Tabla Calendario y Conexión a la Tabla Principal
Se creó una tabla calendario para facilitar el análisis temporal y se conectó a la tabla principal del modelo de datos, permitiendo la visualización de métricas y KPIs a lo largo del mes.

# Medidas DAX :

**-** Cantidad de clientes

**-** Cantidad de llamados

**-** Satisfacción promedio

**-** Promedio de velocidad de respuesta

**-** Promedio de duracion de llamada 

# Tarjetas del Dashboard

**Clientes:** Cantidad total de clientes.

**Llamados:** Total de llamadas recibidas.

**Satisfacción Promedio:** Promedio de la satisfacción del cliente.

**Velocidad de Respuesta en Segundos:** Tiempo promedio de respuesta.

**Duración de la Llamada en Segundos:** Tiempo promedio de duración de las llamadas.

# Gráficos del Dashboard

**1- Cantidad y Porcentaje de Llamados Resueltos y No Resueltos**

Muestra la distribución de llamados resueltos frente a no resueltos, tanto en cantidad como en porcentaje.

**2- Cantidad de Llamados por Agentes**

Representa el número de llamadas atendidas por cada asistente.

**3- Cantidad de Llamados por Áreas**

Ilustra la cantidad de llamados recibidos por cada área del Call Center.

**4- Cantidad de Llamados por Día**

Visualiza la cantidad de llamados recibidos cada día de la semana.
