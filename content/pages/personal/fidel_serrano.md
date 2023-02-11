---
title: M. en G. Fidel Serrano Candela
layout: page
url: /personal/fidel_serrano
save_as: personal/fidel_serrano/index.html
---


<img src="/images/serranoycandela/izta.jpg" width="300px">

- Técnico Académico en Análisis Espacial y Geovisualización; Laboratorio Nacional de Ciencias de la Sostenibiliad (LANCIS); Instituto de Ecología, Universidad Nacional Autónoma de México (UNAM). email: serranoycandela@iecologia.unam.mx

- Candidato a Doctor, Posgrado en Ciencias de la Sostenibilidad, UNAM


## Semblanza

Físico por la Facultad de ciencias, UNAM, Maestro en Geomática por el Centro de Investigación en Ciencias de Información Geoespacial y candidato a doctor en Ciencias de la Sostenibilidad por la UNAM.

Especialista en sistemas de información geográfica y cómputo científico. Ha desarrollado diversas herramientas computacionales en Java, Python, Python-QGIS, R, GRASS y Netlogo. En la actualidad se enfoca en la creación de objetos de frontera que sirvan de puente entre científicos, sociedad civil y entidades de la administración pública. En particular, en temas asociados instrumentos de la política ambiental, como el ordenamiento ecológico, bitácora ambiental, al análisis de vulnerabilidad y riesgo, y la evaluación del impacto ambiental. Así como en el modelaje de sistemas sociambientales acoplados mediante modelos basados en agentes, autómatas celulares y modelos de decisión multicriterio. Enfocando estos esfuerzos de modelación en sistemas sociambientales claves para la sostenibilidad como la gestión del agua en el Valle de México.


## Cómputo científico

- Desarrollo de Software: Python, Java, R, Netlogo, Qt
- Bases de datos: MySQL, sqlite, Postgres
- Supercómputo: Condor
- Control de versiones: Git


## Análisis espacial y Geovisualización

- Manejo de software especializado en sistemas de información geográfica:
  QGIS, GRASS, ArcMap, GeoServer, Postgres-PostGIS
- Desarrollo de aplicaciones geográficas en web: OpenLayers, Leaflet
- Desarrollo de modulos y extensiones para: QGIS, GRASS, ArcMap


## Artefactos computacionales

Todos los artefactos computacionales están en un repositorio público con control de versiones, para asegurar su resguardo y promover el trabajo colaborativo.


### Prototipo para el monitoreo de la gestión del Programa de Ordenamiento Ecológico Territorial del Estado de Yucatán.

Es una interfaz de geovisualización que despliega los datos que serán recopilados de forma dinámica de la plataforma de trámites del gobierno de Yucatán donde se albergan los datos de los proyectos que requieren autorización en materia ambiental.

[<img src="/images/serranoycandela/monitoreo_yucatan.png" width="600px">](https://gitlab.com/serranoycandela/monitoreo_yucatan)


[Repositorio en GitHub](https://gitlab.com/serranoycandela/monitoreo_yucatan)

[Sitio web](http://monitoreo.lee.mx)

### Geo Value Functions in QGIS

Este es un plugin de QGIS que permite transformar datos geográficos vectoriales o raster en capas con un significado, es una herramienta para extraer conocimiento espacial implícito de expertos en un tema. Es útil en el contexto de la creación de índices compuestos de varios criterios (por ejemplo, índices de vulnerabilidad), así como en la combinación del análisis multicriterio de decisiones con sistemas de información geográfica (GIS-MCDA).  

[<img src="/images/serranoycandela/gvf_qgis4.PNG" width="100%">](https://plugins.qgis.org/plugins/geo_value_functions/) [<img src="/images/serranoycandela/gvf_qgis3.PNG" width="100%">](https://plugins.qgis.org/plugins/geo_value_functions/)

[Repositorio en GitHub](https://github.com/serranoycandela/geo_value_functions)

[En la página de plugins de QGIS](https://plugins.qgis.org/plugins/geo_value_functions/)

### Parallel Coordinates Maps

Esta es una aplicación web que permite filtrar interactivamante datos vectoriales con multiples dimenciones. Lo anterior se logra a traves del uso de la biblioteca de d3 para gráficas de coordenadas paralelas [d3.parcoords.js](https://www.d3-graph-gallery.com/parallel), en conjunción con OpenLayers para desplegar dinamicamente la imformación geográfica. Se puede subir un shapefile para generar nuevos mapas intercativos, pero el shapefile debe estar en coordenadas geográficas y tener un campo "id" de tipo texto con valores enteros consecutivos. Esta aplicación web es producto de la colaboración con Rodrigo García Herrera.

[<img src="/images/serranoycandela/palallelcoordinates.PNG" width="600px">](http://pc.magrat.mine.nu/parallel_coordinates_maps/5c4e14c30a705b3386bbe6318846ed53)

[Repositorio en GitHub](https://github.com/sostenibilidad-unam/parallel_coordinates_maps)

[Sitio web](http://pc.magrat.mine.nu/parallel_coordinates_maps/5c4e14c30a705b3386bbe6318846ed53)


### Hieroglyph + Parallel Coordinates

Esta es una aplicación web que despliega indeces jerárquicos con expresión territorial mediante la combinación de glifos circulares y concéntricos con mapa y gráfica de coordenadas paralelas.

[<img src="/images/serranoycandela/pc_hieroglyph.png" width="600px">](https://github.com/sostenibilidad-unam/pc_hieroglyph)

[Repositorio en GitHub](https://github.com/sostenibilidad-unam/pc_hieroglyph)

[Sitio web](http://pch.apps.lancis.ecologia.unam.mx/pc_glyph/example1)

### Geo Value Functions en la web

Esta es una aplicación web que permite transformar datos geográficos vectoriales en capas con un significado, es una herramienta para extraer conocimiento espacial implícito de expertos en un tema. Es útil en el contexto de la creación de índices compuestos de varios criterios (por ejemplo, índices de vulnerabilidad), así como en la combinación del analisis multicriterio de decisiones con sistemas de información geográfica (GIS-MCDA). Esta aplicación web es producto de la colaboración con Rodrigo García Herrera.

[<img src="/images/serranoycandela/geo_value_functions_web_1.PNG" width="370px">](http://gvf.magrat.mine.nu/setup/) [<img src="/images/serranoycandela/geo_value_functions_web_2.PNG" width="370px">](http://gvf.magrat.mine.nu/setup/)

[Repositorio en GitHub](https://github.com/sostenibilidad-unam/geo-value-function)

[Sitio web](http://gvf.magrat.mine.nu/setup/)

### Captación de agua de lluvia

"El presente estudio, es una propuesta única a nivel metodológico y analítico porque discute el
potencial de implementación de los SCALL, visualizados como un conjunto de prácticas que
tienden a construir un manejo sustentable del agua a través de tecnología descentralizada.
La principal fortaleza de éste es la escala y variabilidad espacial de los parámetros climatológicos,
hidrológicos y sociales integrados. Así, se consideraron los niveles de desarrollo social y
se visualizaron los efectos de los SCALL sobre la disminución de la precariedad hídrica, en una
escala de trabajo que incluye toda la variabilidad ambiental y social de la CDMX. Las variables
asociadas a la precariedad hídrica retomadas en este estudio y su integración a nivel espacial,
hacen del presente ejercicio metodológico un trabajo que puede sentar las bases para futuros
estudios relacionados con la captación de agua de lluvia."

[<img src="/images/serranoycandela/islaurbana.png" width="370px">](/images/serranoycandela/cosecha_lluvia.pdf) [<img src="/images/serranoycandela/islaurbana2.png" width="370px">](/images/serranoycandela/Captacion-de-agua-en-la-CDMX_09082020_final_web.pdf)

[Pdf](/images/serranoycandela/Captacion-de-agua-en-la-CDMX_09082020_final_web.pdf)



## Interes Académicos

- Modelación de sistemas socio-eclógicos acoplados.
- Transición hacia la movilidad no carbonizada.
- Objetos de frontera para potenciar el cambio social.
- El vínculo entre la forma de las ciudades y la sostenibilidad urbana.

Titulo de investigación: "Configuración geoespacial del uso de suelo y la transición a la sostenibilidad en la Cuenca del Valle de México”


## En la red

[Perfil de GitHub](https://github.com/serranoycandela)

[Perfil de ResearchGate](https://www.researchgate.net/profile/Fidel_Serrano-Candela)

[Perfil de linkedin](https://www.linkedin.com/in/fidel-serrano-candela-b26450183/)

## Publicaciones

-	Bojórquez-Tapia, L.A., Janssen, M.A., Eakin, H., Baeza, A., Serrano-Candela, F., Gómez-Priego, P. & Miquelajauregui, Y. Spatially explicit simulation of two-way coupling of complex socio-environmental systems: Sociohydrological
risk and decision making in Mexico City. Socio-Environmental Systems Modelling, vol. 1, 16129, 2019, doi:10.18174/sesmo.2019a16129


-	Ran Goldblatt, Michelle F. Stuhlmacher, Beth Tellman, Nicholas Clinton, Gordon Hanson, Matei Georgescu, Chuyuan Wang, Fidel Serrano-Candela, Amit K. Khandelwal, Wan-Hwa 7 Cheng, Robert C. Balling, Jr. (2018)“Using Landsat and Nighttime Lights to Map Urban Land Cover:  A Novel Approach for Supervised Pixel-Based Image Classification”. Publicado en Remote Sensing of the Environment Journal, ELSEVIER

-	Andrés Baeza-Castro, Alejandra Estrada-Barón, Fidel Serrano-Candela, Luis A. Bojórquez, Hallie Eakin, Ana E. Escalante (2018). Biophysical, infrastructural and social heterogeneities explain spatial distribution of waterborne gastrointestinal disease burden in Mexico City. Publicado en Environmental Research Letters Journal.


-	Martinez, E; Chapela, J; Caudillo, C; Tapia, R; Ledesma, M; Serrano, F. (2013) “Construction of a web-based crime Geointelligence platform for Mexico City Public Safety” dentro del libro – “Crime Modeling and Mapping Using Geospatial Technologies” de la serie “Geotechnologies and the Environment” Volume 8, pp 415-439, Springer Netherlands

-	Tapia, R; Serrano, F. (2013) “Cartogramas: la distorsión de mapas y su historia”,  Ciencia y Desarrollo. Investigación en Geomática, Vol. 39, No. 267, Septiembre-Octubre, México

-	Santillana, M; Serrano, F. “Calibration and validation of a CA based model using an evolutionary algorithm for urban development simulation. A case study in Mexico City”. Proceedings of the Ninth International Conference on Computers in Urban Planning and Urban Management (CUPUM 2005). University College London, London, UK. 6/2005.

## Agradecimientos

1.	Alejandra Hernández-Terán, Ana Wegier, Mariana Benítez, Rafael Lira
and Ana E. Escalante; Domesticated, Genetically Engineered, and Wild
Plant Relatives Exhibit Unintended Phenotypic Differences: A
Comparative Meta-Analysis Profiling Rice, Canola Maize, Sunflower,
Pumpkin; Frontiers in Plant Science

2.	Tellman, B., Bausch, J. C., Eakin, H., Anderies, J. M., Mazari-Hiriart, M., Manuel-Navarrete, D., & Redman, C. L. (2018). Adaptive pathways and coupled infrastructure: seven centuries of adaptation to water risk and the production of vulnerability in Mexico City. Ecology and Society, 23(1), art1. https://doi.org/10.5751/ES-09712-230101

3.	Eakin, H., R. Shelton, J. Siqueiros-Garcia, L. Charli-Joseph, and D. Manuel-Navarrete. 2019. Loss and social-ecological transformation: pathways of change in Xochimilco, Mexico. Ecology and Society 24(3):15. https://doi.org/10.5751/ES-11030-240315


4.	Mapping and Modeling Illicit and Clandestine Drivers of Land Use Change:
Urban Expansion in Mexico City and Deforestation in Central America by Elizabeth Tellman; Tesis Doctoral Arizona State University 2019; https://repository.asu.edu/items/53734

5.	An integrated model of stand dynamics, soil carbon and fire regime:
Applications to boreal ecosystem response to climate change. Yosune Miquelajauregui Graf
Universidad de Laval, Canada; Tesis Doctoral

6.	El manejo de residuos en un humedal en la frontera urbana:
El caso de San Gregorio Atlapulco, Xochimilco (Primer graduada en el
Posgrado en Ciencias de la Sostenibilidad María Beatriz Ruizpalacios
Remus)

7.	Erika Luna Pérez. 2019. El efecto del crecimiento urbano sobre el clima local de la ZMCM y sus implicaciones socio-ambientales. Tesis para obtener el título de Licenciada en Ciencias de la Tierra. TUTORA: Dra. Yosune Miquelajauregui Graf

8.  Tesis de Maestría en Ciencias de la Sostenibilidad de Karla Adriana Peña Sanabria: “CATEGORIZACIÓN DE ESTRATEGIAS DE PRODUCTIVIDAD AGRÍCOLA: EL CASO DEL CAFÉ EN MÉXICO”; Posgrado en Sostenibilidad, UNAM; Tutora principal Dra. Ana Elena Escalante Hernández; http://132.248.9.195/ptd2020/enero/0799366/Index.html

## Participación en proyectos

1.	“The Dynamics of Multi-Scalar Adaptation in Megacities: Autonomus action, institutional change and social-hydrological risk in Mexico city (Adaptación Dinámica Multi-Escalar en Megalopolis: Acción Autónoma, Cambio Institucional y Riesgo Socio-Hidrológico en la Ciudad de México) MEGADAPT” (Responsable Dra. Hallie Eakin, ASU).

2.	"Análisis integrado de sistemas socioambientales acoplados: desarrollo de capacidades para la evaluación de la vulnerabilidad costera" (Responsable Dr. Luis A. Bojórquez Tapia).

3.	"Sistema de conocimiento para la gestión del Ordenamiento Ecológico del Territorio del estado de Yucatán" (Responsable Dr. Luis A. Bojórquez Tapia).

4.	"Diagnóstico Ambiental y propuesta de Remediación-Reparación-Compensación en la Cuenca del Río Sonora afectada por el derrame del represo 'Tinajas 1' de la Mina Buenavista del Cobre, Cananea, Sonora." (Responsable Dr. Luis A. Bojórquez Tapia).

5.  "Desarrollo de una línea base de resiliencia para la Ciudad de México y diseño de los estándares de generación de indicadores de resiliencia por medio de la implementación de prototipos que servirán de modelo para el resto de las dependencias del Gobierno de la Ciudad de México", con la Dirección General de Resiliencia que forma parte de la Secretaría de Gestión Integral de Riesgos y Protección Civil de la CDMX (Responsable Dr. Luis A. Bojórquez Tapia).

6.  "Captación de lluvia en la CDMX: Un análisis de las desigualdades espaciales"; Isla Urbana, OXFAM, LANCIS, CESOP, ASU, Nodo Metropolitano; (Responsable Dra. Beth Tellman).
