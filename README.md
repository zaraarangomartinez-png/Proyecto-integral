# Análisis del Sector Turismo en Colombia (2015–2024)
## Proyecto final – Programación y Decisiones

Integrantes: Zara Arango • Nicolle Ospina
Universidad de La Sabana

### 📌 Descripción del proyecto

Este proyecto analiza la evolución del sector turismo en Colombia desde el año 2015 hasta 2024 utilizando técnicas de análisis de datos, limpieza de información, modelado y visualización.
Se integran tres herramientas fundamentales:

Python: para limpiar, transformar y preparar las bases de datos.

Power BI: para el modelado relacional y la creación de un dashboard gerencial.

GitHub: para documentación, almacenamiento y versionamiento del proyecto.

El objetivo es convertir datos crudos, incompletos y desordenados en insights estratégicos sobre el comportamiento económico del turismo en el país.

### 🎯 Objetivos del proyecto

Obtener, limpiar y transformar datos públicos del MinCIT y del Banco de la República.

Construir tablas maestras que consoliden información mensual del sector turismo.

Diseñar un modelo relacional en Power BI basado en mejores prácticas.

Elaborar un dashboard interactivo que permita el análisis del sector.

Identificar tendencias, relaciones y factores económicos que influyen directamente en el turismo en Colombia.

### 📁 Estructura del Repositorio

El repositorio se organiza en carpetas según el flujo de trabajo:

data_raw
Contiene los datos originales descargados desde las fuentes oficiales. Incluye:

Archivo con indicadores de turismo de MinCIT

TRM histórica del Banco de la República

Visitantes no residentes por país

data_clean
Incluye las tablas ya limpias, corregidas y listas para ser usadas en Power BI:

Tabla maestra mensual del sector turismo

Tabla de visitantes por país de origen

notebook
Contiene el documento donde se realizó todo el proceso de análisis, limpieza, exploración y transformación de datos.

powerbi
Incluye el archivo del dashboard final del proyecto.

README.md
Documento principal donde se describe todo el proyecto.

### 🧹 Proceso de Limpieza y Transformación

El proceso de preparación de datos consistió en:

#### 1. Exploración inicial

Se revisaron columnas, tipos de datos, valores faltantes, formatos inconsistentes y outliers.
Se identificaron problemas como:

Fechas en diferentes formatos

Números con comas o símbolos

Valores vacíos o mal registrados

Columnas que debían dividirse o unificarse

#### 2. Corrección general

Se estandarizaron nombres de columnas, formatos y tipos de datos.
Se eliminaron errores de digitación, símbolos incorrectos y filas incompletas.

#### 3. Conversión de fechas

Las fechas, originalmente escritas como texto, se transformaron en formato fecha, permitiendo ordenamiento y agrupación mensual.

#### 4. Conversión de valores numéricos

Variables como ingresos, visitantes, ocupación o TRM fueron convertidas en números limpios, aptos para cálculos y agregaciones.

#### 5. Agrupación mensual

Una vez limpias las bases, se construyeron valores mensuales para:

Ingresos por turismo

TRM promedio

Visitantes por país

Ocupación hotelera

Exportaciones de viajes

Exportaciones de transporte de pasajeros

#### 6. Unión y creación de tablas maestras

Finalmente se consolidaron todas las bases limpias en dos tablas finales:

Una con KPI mensuales del sector turismo

Otra con visitantes no residentes detallados por país

Estas tablas fueron exportadas para su uso en Power BI.

### 📊 Proceso en Power BI

Una vez cargados los archivos limpios, se realizó lo siguiente:

#### 1. Modelo relacional

Se estableció una relación entre las tablas a través de la columna fecha, construyendo una estructura que permite filtrar y analizar información de forma coherente.

#### 2. Creación de KPIs

Se diseñaron indicadores clave como:

Ingresos totales del turismo

Total de visitantes no residentes

TRM promedio

Ocupación hotelera promedio

Exportaciones de servicios asociados al turismo

#### 3. Construcción del Dashboard

El dashboard contiene gráficos representativos del sector:

Evolución de ingresos por año

Evolución del número de visitantes

Relación entre TRM e ingresos

Ocupación hotelera a lo largo de los años

Exportaciones de viajes y transporte de pasajeros

Ranking de países emisores de turistas hacia Colombia

El diseño se enfoca en claridad, legibilidad y capacidad analítica.

## 📌 Conclusiones Principales

Crecimiento del turismo:
Se observa un crecimiento sostenido en los ingresos y el número de visitantes entre 2015 y 2019, con variaciones posteriores debidas a factores externos.

Visitantes vs ocupación:
Los meses con mayor número de visitantes coinciden con los mayores niveles de ocupación hotelera, confirmando la coherencia entre fuentes.

Efecto de la TRM:
Cambios en la tasa de cambio afectan los ingresos expresados en dólares y la llegada de visitantes internacionales.

Exportaciones de servicios:
Los indicadores de exportaciones por viajes y transporte de pasajeros se comportan de forma muy similar a los ingresos turísticos, reforzando su importancia.

Países emisores:
Estados Unidos, España, México, Argentina y Brasil representan los mercados más importantes para el turismo en Colombia.

👥 Integrantes

Zara Arango,
Nicolle Ospina,
Universidad de La Sabana -
Curso Programación y Decisiones
