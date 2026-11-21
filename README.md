# Influencia del nivel educativo sobre el reciclaje en España

## Descripción del proyecto

Este proyecto estudia la relación entre el nivel educativo de la población y la cantidad de residuos recogidos selectivamente por persona en las comunidades autónomas españolas durante el año 2023.

El objetivo es explorar si existe una asociación entre el nivel educativo y el comportamiento medioambiental, utilizando técnicas de análisis exploratorio y visualización de datos.

Este análisis forma parte de un proyecto universitario más amplio sobre la influencia de la educación y la ideología política en el reciclaje en España.

## Objetivos

- Analizar la posible relación entre el nivel educativo y la recogida selectiva de residuos.
- Comparar los datos entre comunidades autónomas.
- Estudiar la correlación entre el porcentaje de población con educación alta y baja y los residuos recogidos por persona.
- Identificar patrones mediante representaciones gráficas.

## Tecnologías utilizadas

- **Python:** lenguaje de programación utilizado para el análisis.
- **Pandas:** manipulación, limpieza e integración de datos.
- **Matplotlib:** visualización de resultados.
- **Seaborn:** creación de gráficos estadísticos.
- **Jupyter Notebook:** desarrollo del análisis.

## Datos utilizados

Se han empleado conjuntos de datos procedentes de diferentes fuentes:

- Datos sobre el nivel educativo de la población por comunidades autónomas.
- Datos sobre la recogida selectiva de residuos durante 2023.

Las variables principales del análisis son:

- Porcentaje de población con nivel educativo alto.
- Porcentaje de población con nivel educativo bajo.
- Kilogramos de residuos recogidos por persona.

## Metodología

El análisis se ha desarrollado mediante las siguientes etapas:

**1. Importación de datos**

Lectura de los conjuntos de datos mediante Pandas.

**2. Limpieza y preparación**

Normalización de los nombres de las comunidades autónomas para facilitar la integración de las diferentes fuentes de información.

**3. Integración de datos**

Unión de los conjuntos de datos mediante operaciones `merge()`, utilizando las comunidades autónomas como clave de correspondencia.

**4. Análisis exploratorio**

Estudio de la relación entre el nivel educativo y la cantidad de residuos recogidos por persona.

**5. Análisis estadístico**

Cálculo del coeficiente de correlación para explorar la asociación entre las variables.

**6. Visualización**

Representación de los resultados mediante diagramas de dispersión y líneas de regresión.

## Resultados

El proyecto original identificó una correlación positiva de intensidad media entre el nivel educativo y la cantidad de residuos recogidos por persona.

También se observaron diferencias entre comunidades autónomas, lo que apunta a que el comportamiento medioambiental puede estar relacionado con distintos factores sociales y territoriales.

## Estructura del repositorio

- `notebooks/`: cuadernos Jupyter con el desarrollo del análisis.
- `data/`: conjuntos de datos utilizados.
- `images/`: visualizaciones y gráficos obtenidos.
- `memoria/`: documentación del proyecto universitario.

## Contexto académico

Proyecto desarrollado en el marco de la asignatura Proyecto I del Grado en Ciencia de Datos de la Universitat Politècnica de València (UPV), durante el curso 2024-2025.
