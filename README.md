📊 Telecom X – Análisis de Churn de Clientes

Este proyecto analiza el fenómeno de Churn (evasión de clientes) en una empresa de telecomunicaciones utilizando Python y técnicas de análisis de datos.

El objetivo es identificar los factores que influyen en la cancelación del servicio y generar insights que ayuden a mejorar la retención de clientes.


📓 Notebook del Proyecto

🔗 https://colab.research.google.com/drive/1IpITJ42IrpaAF5PAAaC9hVVj8h_iQyGz


🎯 Objetivos

Extraer datos desde una fuente externa en formato JSON

Realizar procesos de limpieza y transformación de datos

Desarrollar un Análisis Exploratorio de Datos (EDA)

Identificar patrones asociados al churn

Proponer estrategias de retención de clientes


📂 Dataset

El dataset contiene información sobre 7267 clientes de una empresa de telecomunicaciones, incluyendo:

Datos demográficos

Servicios contratados

Tipo de contrato

Antigüedad del cliente

Cargos mensuales y totales

Variable objetivo: Churn


⚙️ Procesamiento de Datos

Durante el análisis se realizaron varias transformaciones:

Normalización de columnas anidadas del JSON (customer, phone, internet, account)

Limpieza de valores inconsistentes en Charges.Total

Conversión de variables a tipos numéricos

Creación de nuevas variables como Cuentas_Diarias

Estandarización de la variable Churn a formato numérico


📊 Análisis Exploratorio

Se analizaron diferentes variables para entender su relación con el churn, utilizando visualizaciones como:

Gráficos de barras

Histogramas

Boxplots

Gráficos circulares

Herramientas utilizadas:

Pandas

NumPy

Matplotlib

Seaborn


📈 Principales Hallazgos

Aproximadamente 25.6% de los clientes abandonaron el servicio.

El género no muestra diferencias significativas en la tasa de churn.

Los clientes con contratos month-to-month presentan mayor probabilidad de cancelación.

Los clientes con menor antigüedad y menor gasto total tienen mayor riesgo de abandono.


💡 Conclusiones

El churn está fuertemente relacionado con:

Tipo de contrato

Antigüedad del cliente

Gasto acumulado

Estos insights permiten diseñar estrategias de retención enfocadas en clientes nuevos y contratos de corto plazo, ayudando a mejorar la fidelización y el valor de vida del cliente.


🛠️ Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab
