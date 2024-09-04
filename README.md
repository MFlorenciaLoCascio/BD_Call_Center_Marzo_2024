# Análisis de Call Center - Marzo 2024 📞

### Este proyecto presenta un análisis detallado de los registros de llamadas de un Call Center durante el mes de marzo de 2024. Los datos incluyen el ID de llamada, fecha, asistente, área, estado de resolución del llamado, velocidad de respuesta, duración de la llamada, duración con asistente en segundos e índice de satisfacción.

### 💻 Puede visualizar el dashboard: [Reporting Call Center](https://app.powerbi.com/view?r=eyJrIjoiNmZkMDE0YTItZTgwMS00MWY4LWI3ZWItNzRkMmU1YmFmZDZkIiwidCI6IjdmMmY3MDM3LTljNjMtNDY3Ni04YzRkLWNjZjgyZDZhZjVlMyIsImMiOjR9&pageName=92693618d0e502c8ca9d)

# 🎯 Objetivos del Análisis

### Este análisis permite identificar áreas de mejora en cuanto a la calidad de las llamadas, la satisfacción del cliente y las áreas que requieren mayor atención. Los resultados obtenidos ayudarán a optimizar el rendimiento del Call Center y a mejorar la experiencia del cliente.

# 📊 El análisis se enfocó en responder las siguientes preguntas:

#### **1-** ¿Qué área recibe la mayor cantidad de llamados?

#### **2-** ¿Cuál es el asistente con mayor y menor velocidad de respuesta?

#### **3-** ¿Cuál es la satisfacción promedio del cliente?

#### **4-** ¿Qué asistente tiene la mayor y menor satisfacción del cliente?

#### **5-** ¿Cuál es la cantidad de llamados resueltos y no resueltos?

#### **6-** ¿Qué asistente tiene la mayor y menor cantidad de llamados resueltos?

#### **7-** ¿Qué asistente tiene la mayor y menor cantidad de llamados no resueltos?

#### **8-** ¿Qué día de la semana se recibe la mayor cantidad de llamados y de qué tipo?

#### **9-** ¿Cuál es la cantidad total de clientes y llamados?

# 📄 Limpieza de Datos en Power Query

#### **1- Verificación y Modificación de Tipos de Datos:** 

Se ajustaron los tipos de datos correspondientes a cada columna para asegurar la correcta interpretación de los datos.

#### **2- Corrección de Palabras en la Columna "Área":** 

Se corrigieron errores y inconsistencias en los nombres de las áreas para estandarizar la información.

#### **3-Eliminación de Columnas Innecesarias:** 

Se eliminaron columnas que no eran relevantes para el análisis, reduciendo el tamaño del archivo y mejorando el rendimiento.

# 📅 Tabla Calendario y Conexión a la Tabla Principal

Se creó una tabla calendario para facilitar el análisis temporal y se conectó a la tabla principal del modelo de datos, permitiendo la visualización de métricas y KPIs a lo largo del mes.

# 📈 Medidas DAX :

#### 1- Cantidad de clientes

#### 2- Cantidad de llamados

#### 3- Satisfacción promedio

#### 4- Promedio de velocidad de respuesta

#### 5- Promedio de duracion de llamada 

# 🔲 Tarjetas del Dashboard

#### **1- Clientes:** 

Cantidad total de clientes.

#### **2- Llamados:** 

Total de llamadas recibidas.

#### **3- Satisfacción Promedio:** 

Promedio de la satisfacción del cliente.

#### **4- Velocidad de Respuesta en Segundos:** 

Tiempo promedio de respuesta.

#### **5- Duración de la Llamada en Segundos:** 

Tiempo promedio de duración de las llamadas.

# 🏁 Gráficos del Dashboard

#### **1- Cantidad y Porcentaje de Llamados Resueltos y No Resueltos**

Muestra la distribución de llamados resueltos frente a no resueltos, tanto en cantidad como en porcentaje.

#### **2- Cantidad de Llamados por Agentes**

Representa el número de llamadas atendidas por cada asistente.

#### **3- Cantidad de Llamados por Áreas**

Ilustra la cantidad de llamados recibidos por cada área del Call Center.

#### **4- Cantidad de Llamados por Día**

Visualiza la cantidad de llamados recibidos cada día de la semana.

# 💻 DASHBOARD: 

### [Reporting Call Center]()

![image](https://github.com/user-attachments/assets/ef8b74e3-d7e7-4e67-83cd-9861875c5211)


![image](https://github.com/user-attachments/assets/876ed0ee-3a7a-4398-b43c-6580de2f51ba)


# 📊 Análisis 

### **1-Área con Mayor Cantidad de Llamados:** 

El área de ventas es la que recibe la mayor cantidad de llamados.

### **2-Asistente con Mayor y Menor Velocidad de Respuesta:**

Mayor velocidad de respuesta: Ana S.

Menor velocidad de respuesta: Marcelo F.

### **3-Satisfacción Promedio del Cliente:**

La satisfacción promedio del cliente es de 3.4.

### **4-Asistente con Mayor y Menor Satisfacción del Cliente:**

Menor satisfacción: Juan D. con un puntaje de 2.8.

Mayor satisfacción: Ana S. y Gustavo M.

### **5-Cantidad de Llamados Resueltos y No Resueltos:**

Llamados resueltos: 114.
Llamados no resueltos: 28.

### **6-Asistente con Mayor y Menor Cantidad de Llamados Resueltos:**

Mayor cantidad de llamados resueltos: Juan D. con 169.

Menor cantidad de llamados resueltos: Marcelo F. con 108.

### **7-Asistente con Mayor y Menor Cantidad de Llamados No Resueltos:**

Mayor cantidad de llamados no resueltos: Ana S. con 28.

Menor cantidad de llamados no resueltos: Leandro C. con 6.

### **8-Día de la Semana con Mayor y Menor Cantidad de Llamados:**

Mayor cantidad de llamados: Jueves, con 186, predominantemente en el área de ventas.

Menor cantidad de llamados: Martes, con 114, también mayoritariamente en el área de ventas (55 llamados).

### **9-Cantidad Total de Llamados y Clientes:**

Total de llamados: 1,031.

Total de clientes: 1,009.

# ✅ Hallazgos y Patrones Observados

### Predominio del Área de Ventas: 

El área de ventas claramente domina la carga de trabajo en el Call Center, siendo responsable de la mayor cantidad de llamados tanto en días de alta como de baja actividad.

### Rendimiento Destacado de Ana S.: 

Ana S. no solo muestra la mayor velocidad de respuesta, sino que también mantiene una alta satisfacción del cliente, lo que sugiere una excelente capacidad para manejar eficientemente las llamadas.

### Variabilidad en la Satisfacción del Cliente: 

La satisfacción varía significativamente entre los agentes, con Juan D. mostrando un puntaje notablemente bajo. Esto podría indicar la necesidad de una revisión de su desempeño o de proporcionar apoyo adicional.

### Discrepancia en la Resolución de Llamados: 

A pesar de que Juan D. resuelve la mayor cantidad de llamados, su baja satisfacción promedio podría sugerir que la resolución no siempre cumple con las expectativas del cliente.

### Distribución de Llamados por Día: 

El jueves es el día con mayor carga de trabajo, lo que podría requerir una planificación de recursos adicional para asegurar que todos los llamados se manejen de manera eficiente.

### Alta Tasa de Resolución: 

Con solo 28 llamados no resueltos de 1.031, el Call Center muestra una alta tasa de resolución, aunque los llamados no resueltos parecen estar concentrados en algunos agentes específicos.

# ⚙️ Herramientas utilizadas:
Power Bi, DAX, Power Query Figma para la plantilla PBI
