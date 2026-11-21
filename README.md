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

- **Ecoembes [3]:** mediante técnicas de *web scraping* se obtuvieron datos sobre las cantidades de plástico y cartón recogidas en los municipios de España, así como el número de contenedores amarillos y azules disponibles en cada municipio.
- **Ministerio de Política Territorial y Memoria Democrática [6]:** se recopilaron datos sobre los alcaldes de los municipios españoles y su partido político durante la legislatura 2019-2023.
- **Ecovidrio [4]:** se descargaron datos sobre la cantidad de vidrio recogido en cada comunidad y ciudad autónoma.
- **Instituto Nacional de Estadística (INE) [7]:** se utilizaron datos relativos al nivel educativo de la población, desglosados por comunidades autónomas.

Estos conjuntos de datos permitieron combinar información de carácter educativo, político y medioambiental para estudiar posibles relaciones entre estas variables.

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

## Referencias bibliográficas

1. Corrado, L., Fazio, A., & Pelloni, A. (2022). Pro-environmental attitudes, local environmental conditions and recycling behavior. *Journal of Cleaner Production, 362*, 132399. https://doi.org/10.1016/j.jclepro.2022.132399

2. Oke, A. (2015). Workplace Waste Recycling Behaviour: A Meta-Analytical Review. *Sustainability, 7*(6), 7175–7194. https://doi.org/10.3390/su7067175

3. Ecoembes. (s. f.). *Barómetro de reciclaje en España*. Recuperado el 22 de abril de 2025, de https://www.ecoembes.com/es/el-proceso-de-reciclaje/datos-de-reciclaje-de-envases-domestico-en-espana/recogida-selectiva-de-envases-domesticos/barometro

4. Ecovidrio. (s. f.). *Datos de reciclaje en España*. Recuperado el 19 de febrero de 2025, de https://www.ecovidrio.es/reciclaje/datos-reciclaje

5. Instituto Nacional de Estadística (INE). (s. f.). *Estadística sobre recogida y tratamiento de residuos*. Recuperado el 13 de febrero de 2025, de https://ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736176844&menu=ultiDatos&idp=1254735976612

6. Ministerio de Política Territorial y Memoria Democrática. (s. f.). *Alcaldes y Concejales*. Recuperado el 13 de febrero de 2025, de https://mpt.gob.es/portal/politica-territorial/local/sistema_de_informacion_local_-SIL/alcaldes_y_concejales.html

7. Instituto Nacional de Estadística (INE). (s. f.). *Nivel de formación alcanzado por la población total (de 16 a 64 años) por nivel de educación, CCAA y periodo*. Recuperado el 10 de abril de 2025, de https://www.ine.es/jaxi/Tabla.htm?path=/t00/ICV/dim4/l0/&file=41101.px&L=0
