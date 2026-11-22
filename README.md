# Relación entre el nivel educativo y la recogida selectiva de residuos en España

## Descripción del proyecto

Este proyecto estudia la relación entre el nivel educativo de la población y la cantidad de residuos recogidos selectivamente por persona en las comunidades y ciudades autónomas españolas durante el año 2023.

El objetivo es explorar si existe una asociación entre el nivel educativo y la recogida selectiva de residuos, mediante técnicas de análisis exploratorio, estadística descriptiva y visualización de datos.

Este análisis forma parte de un proyecto universitario más amplio sobre la relación entre la educación, la ideología política y el reciclaje en España.

## Objetivos

- Analizar la posible relación entre el nivel educativo de la población y la recogida selectiva de residuos.
- Comparar los datos entre comunidades y ciudades autónomas.
- Estudiar la correlación entre el porcentaje de población con niveles educativos altos y bajos y la cantidad de residuos recogidos por persona.
- Identificar posibles patrones mediante representaciones gráficas.

## Tecnologías utilizadas

- **Python:** lenguaje de programación utilizado para el análisis.
- **Pandas:** manipulación, limpieza e integración de datos.
- **Matplotlib:** visualización de resultados.
- **Seaborn:** elaboración de gráficos estadísticos.
- **Jupyter Notebook:** entorno utilizado para desarrollar el análisis.

## Datos utilizados

El proyecto universitario original empleó conjuntos de datos procedentes de diferentes fuentes:

- **Ecoembes [3]:** mediante técnicas de *web scraping* se obtuvieron datos sobre las cantidades de envases de plástico y papel y cartón recogidas en los municipios españoles, así como información sobre el número de contenedores amarillos y azules.
- **Ministerio de Política Territorial y Memoria Democrática [6]:** se recopilaron datos sobre los alcaldes de los municipios españoles y su partido político durante la legislatura 2019-2023.
- **Ecovidrio [4]:** se obtuvieron datos sobre la cantidad de vidrio recogido en las comunidades y ciudades autónomas.
- **Instituto Nacional de Estadística (INE) [5, 7]:** se utilizaron estadísticas relacionadas con la recogida y tratamiento de residuos y con el nivel educativo de la población, desglosadas por comunidades autónomas.

**Alcance de este repositorio:** aunque el proyecto universitario original contempla información educativa, política y medioambiental, este repositorio se centra específicamente en el análisis de la relación entre el nivel educativo y la cantidad de residuos recogidos por persona. Por tanto, no incluye todos los análisis desarrollados en el proyecto original.

Las principales variables utilizadas en este análisis son:

- Porcentaje de población con nivel educativo alto.
- Porcentaje de población con nivel educativo bajo.
- Kilogramos de residuos recogidos por persona.

## Metodología

El análisis se ha desarrollado mediante las siguientes etapas:

**1. Importación de datos**

Lectura de los conjuntos de datos mediante Pandas.

**2. Limpieza y preparación de los datos**

Revisión de los conjuntos de datos y normalización de los nombres de las comunidades y ciudades autónomas para facilitar su integración.

**3. Integración de datos**

Unión de los conjuntos de datos mediante operaciones `merge()`, utilizando los nombres normalizados de los territorios como clave de correspondencia.

**4. Análisis exploratorio**

Exploración de la relación entre el nivel educativo de la población y la cantidad de residuos recogidos por persona.

**5. Análisis estadístico**

Cálculo del coeficiente de correlación de Pearson para estudiar la dirección y la intensidad de la asociación lineal entre las variables.

**6. Visualización**

Representación de los resultados mediante diagramas de dispersión y líneas de regresión.

## Resultados

Se ha analizado la relación entre el nivel educativo de la población y la cantidad de residuos recogidos por persona en las comunidades y ciudades autónomas españolas durante 2023.

Para ello, se han estudiado dos indicadores: el porcentaje de población con nivel educativo alto y el porcentaje de población con nivel educativo bajo. Se han utilizado diagramas de dispersión y el coeficiente de correlación de Pearson para estudiar la relación lineal entre cada indicador y la cantidad de residuos recogidos por habitante.

Los resultados obtenidos muestran:

- **Educación alta:** se obtiene un coeficiente de correlación de Pearson de **0,419**, lo que indica una asociación lineal positiva moderada entre el porcentaje de población con estudios superiores y la cantidad de residuos recogidos por persona. En general, los territorios con mayor porcentaje de población con educación superior tienden a presentar una mayor recogida de residuos por habitante.
  <img width="994" height="655" alt="image" src="https://github.com/user-attachments/assets/4ba47811-b975-4cf5-83d8-8211b161b74a" />


- **Educación baja:** se obtiene un coeficiente de correlación de Pearson de **−0,524**, lo que refleja una asociación lineal negativa moderada entre el porcentaje de población con niveles educativos bajos y la cantidad de residuos recogidos por persona. En general, los territorios con mayor porcentaje de población con niveles educativos bajos tienden a presentar una menor recogida de residuos por habitante.
  <img width="1000" height="643" alt="image" src="https://github.com/user-attachments/assets/7d136bfe-aa18-4e3d-9d93-515e116f64e5" />





En ambos análisis se han emparejado correctamente los datos correspondientes a **19 comunidades y ciudades autónomas**.

Estos resultados reflejan asociaciones estadísticas, pero no permiten establecer relaciones de causalidad entre el nivel educativo y la recogida selectiva de residuos.

## Conclusiones

Los resultados muestran una asociación entre el nivel educativo de la población y la cantidad de residuos recogidos por persona. En concreto, se observa una correlación positiva moderada con la educación alta y una correlación negativa moderada con la educación baja.

Estos resultados sugieren que los territorios con mayores porcentajes de población con estudios superiores tienden a registrar mayores cantidades de residuos recogidos por habitante. Por el contrario, aquellos con mayores porcentajes de población con niveles educativos bajos tienden a presentar menores cantidades.

No obstante, estos resultados deben interpretarse con cautela. La correlación no implica causalidad y existen otros factores que pueden influir en la recogida selectiva de residuos, como las características socioeconómicas de la población, la concienciación ambiental o la disponibilidad de infraestructuras de reciclaje.

Además, al tratarse de un análisis realizado a nivel territorial, no es posible extrapolar directamente estas asociaciones al comportamiento individual de las personas.

## Estructura del repositorio

- `notebooks/`: cuadernos Jupyter con el desarrollo del análisis.
- `data/`: conjuntos de datos utilizados.
- `images/`: visualizaciones y gráficos obtenidos.
- `memoria/`: documentación del proyecto universitario.

## Contexto académico

Proyecto desarrollado en el marco de la asignatura Proyecto I del Grado en Ciencia de Datos de la Universitat Politècnica de València (UPV), durante el curso académico 2024-2025.

## Referencias bibliográficas

1. Corrado, L., Fazio, A., & Pelloni, A. (2022). Pro-environmental attitudes, local environmental conditions and recycling behavior. *Journal of Cleaner Production, 362*, 132399. [https://doi.org/10.1016/j.jclepro.2022.132399](https://doi.org/10.1016/j.jclepro.2022.132399)

2. Oke, A. (2015). Workplace Waste Recycling Behaviour: A Meta-Analytical Review. *Sustainability, 7*(6), 7175–7194. [https://doi.org/10.3390/su7067175](https://doi.org/10.3390/su7067175)

3. Ecoembes. (s. f.). *Barómetro de reciclaje en España*. Recuperado el 22 de abril de 2025, de [https://www.ecoembes.com/es/el-proceso-de-reciclaje/datos-de-reciclaje-de-envases-domestico-en-espana/recogida-selectiva-de-envases-domesticos/barometro](https://www.ecoembes.com/es/el-proceso-de-reciclaje/datos-de-reciclaje-de-envases-domestico-en-espana/recogida-selectiva-de-envases-domesticos/barometro)

4. Ecovidrio. (s. f.). *Datos de reciclaje en España*. Recuperado el 19 de febrero de 2025, de [https://www.ecovidrio.es/reciclaje/datos-reciclaje](https://www.ecovidrio.es/reciclaje/datos-reciclaje)

5. Instituto Nacional de Estadística (INE). (s. f.). *Estadística sobre recogida y tratamiento de residuos*. Recuperado el 13 de febrero de 2025, de [https://ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736176844&menu=ultiDatos&idp=1254735976612](https://ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C\&cid=1254736176844\&menu=ultiDatos\&idp=1254735976612)

6. Ministerio de Política Territorial y Memoria Democrática. (s. f.). *Alcaldes y Concejales*. Recuperado el 13 de febrero de 2025, de [https://mpt.gob.es/portal/politica-territorial/local/sistema_de_informacion_local\_-SIL/alcaldes_y_concejales.html](https://mpt.gob.es/portal/politica-territorial/local/sistema_de_informacion_local_-SIL/alcaldes_y_concejales.html)

7. Instituto Nacional de Estadística (INE). (s. f.). Nivel de formación alcanzado por la población total (de 16 a 64 años) por nivel de educación CCAA y periodo. INE. Recuperado el 10 de abril de 2025, de [https://www.ine.es/jaxi/Tabla.htm?path=/t00/ICV/dim4/l0/&file=41101.px](https://www.ine.es/jaxi/Tabla.htm?path=/t00/ICV/dim4/l0/\&file=41101.px) &L=0.
