# Propuesta del Proyecto

# Evolución de la Ganadería Vacuna Argentina (1980-2025)

**Fecha de creación:** 18/07/2026

**Estado:** Planificación inicial

---

## Descripción

La ganadería vacuna es una de las actividades económicas más representativas de la República Argentina y posee un rol fundamental en el abastecimiento del mercado interno, las exportaciones y el desarrollo productivo de distintas regiones del país.

Este proyecto tiene como objetivo realizar un análisis integral de la evolución de la ganadería vacuna argentina durante las últimas décadas utilizando datos oficiales provenientes de organismos públicos y entidades relacionadas con el sector.

Se desarrollará un flujo de trabajo completo de análisis de datos, incorporando investigación de fuentes, integración de datos, diseño de una base de datos relacional, consultas SQL, análisis exploratorio y visualización de resultados mediante Python.

---

# Objetivo General

Analizar la evolución de la ganadería vacuna argentina durante las últimas décadas mediante técnicas de análisis de datos, con el propósito de identificar tendencias, cambios relevantes y relaciones entre las principales variables del sector.

---

# Objetivos Específicos

- Investigar y recopilar datos provenientes de fuentes oficiales.
- Diseñar una base de datos relacional utilizando PostgreSQL.
- Integrar información proveniente de diferentes fuentes.
- Realizar procesos de limpieza y transformación de datos.
- Construir consultas SQL para responder preguntas relacionadas con el sector.
- Realizar un Análisis Exploratorio de Datos (EDA).
- Crear visualizaciones que permitan interpretar los resultados.
- Elaborar conclusiones basadas en evidencia obtenida a partir de los datos.

---

# Preguntas de análisis

El proyecto buscará responder preguntas como:

- ¿Cómo evolucionó el stock bovino argentino durante las últimas décadas?
- ¿Cuáles fueron los períodos de crecimiento y disminución del rodeo bovino?
- ¿Cómo evolucionó la producción de carne vacuna?
- ¿Qué cambios ocurrieron en el consumo interno?
- ¿Cómo evolucionaron las exportaciones de carne vacuna?
- ¿Existe relación entre el stock bovino, la producción y las exportaciones?
- ¿Cómo cambió el peso promedio de faena?
- ¿Qué tendencias importantes pueden identificarse en el sector?

---

# Tecnologías

Las herramientas utilizadas para el desarrollo del proyecto serán:

- Python
- PostgreSQL
- SQL
- Pandas
- NumPy
- Matplotlib
- Plotly
- Jupyter Notebook
- Git
- GitHub

---

# Metodología del Proyecto

## Etapa 1 - Investigación de fuentes de datos

Objetivo:
Identificar, analizar y seleccionar fuentes oficiales de información.

Actividades:

- Buscar organismos con información relevante.
- Evaluar disponibilidad y calidad de los datos.
- Definir variables necesarias para el análisis.
- Determinar el período de estudio.

Estado: Pendiente

---

## Etapa 2 - Diseño de la base de datos

Objetivo:
Crear una estructura organizada para almacenar la información recopilada.

Actividades:

- Definir tablas necesarias.
- Establecer relaciones entre entidades.
- Determinar claves primarias y campos.
- Diseñar el modelo relacional.

Estado: Pendiente

---

## Etapa 3 - Carga y preparación de datos

Objetivo:
Construir la base de datos y preparar la información para el análisis.

Actividades:

- Crear la base en PostgreSQL.
- Importar datos.
- Detectar errores e inconsistencias.
- Realizar procesos de limpieza.

Estado: Pendiente

---

## Etapa 4 - Análisis mediante SQL

Objetivo:
Utilizar consultas SQL para explorar la información almacenada.

Se trabajará con:

- Consultas básicas.
- Filtros.
- Agrupaciones.
- JOIN entre tablas.
- Funciones agregadas.
- CTE.
- Funciones de ventana.

Estado: Pendiente

---

## Etapa 5 - Análisis Exploratorio de Datos (EDA)

Objetivo:
Analizar los datos utilizando Python.

Se evaluará:

- Estructura de los datasets.
- Valores faltantes.
- Valores atípicos.
- Distribuciones.
- Tendencias históricas.
- Relaciones entre variables.

Estado: Pendiente

---

## Etapa 6 - Visualización y comunicación de resultados

Objetivo:
Crear gráficos que permitan interpretar los principales hallazgos.

Se desarrollarán:

- Gráficos temporales.
- Comparaciones históricas.
- Indicadores principales.
- Visualizaciones orientadas a la comunicación de resultados.

Estado: Pendiente

---

## Etapa 7 - Informe final

Objetivo:
Documentar los resultados obtenidos durante el análisis.

El informe incluirá:

- Metodología utilizada.
- Fuentes de datos.
- Análisis realizados.
- Principales descubrimientos.
- Conclusiones.

Estado: Pendiente

---

# Competencias demostradas

Este proyecto permitirá demostrar conocimientos en:

- Análisis de datos.
- SQL.
- Diseño de bases de datos.
- Integración de información.
- ETL.
- Python para análisis.
- Visualización de datos.
- Documentación técnica.
- Uso de Git y GitHub.

---

# Estructura prevista del repositorio

```text
analisis-ganaderia-argentina/

├── README.md
├── .gitignore
│
├── docs/
│   └── 01_propuesta_del_proyecto.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── database/
│   └── modelo_relacional.png
│
├── sql/
│   ├── creacion_tablas.sql
│   ├── carga_datos.sql
│   └── consultas.sql
│
├── notebooks/
│   ├── 01_exploracion.ipynb
│   ├── 02_eda.ipynb
│   └── 03_visualizaciones.ipynb
│
├── images/
│
└── requirements.txt