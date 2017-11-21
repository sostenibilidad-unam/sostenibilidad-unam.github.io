---
layout: page
title: ""
permalink: /iai/modelacion_hidrologica
---

<center><img src="/assets/logo_iai.png" alt="logo iai"></center>

Modelación hidrológica
======================

La modelación hidrológica es una herramienta fundamental en la gestión
sostenible de cuencas tanto urbanas como rurales (una cuenca es un territorio
cuyas aguas afluyen todas a un mismo río, lago o mar). Por lo general, la
modelación hidrológica involucra la identificación de subcuencas o unidades de
respuesta hidrológica. Esto se hace con la ayuda de los sistemas de información
geográfica. Típicamente, las fases del ciclo hidrológico (esto es,
precipitación, infiltración, escorrentía y agua subterránea) se caracterizan
para cada una de estas unidades y con ello se generan los datos de entrada de
modelos dinámicos de simulación. Éstos se utilizan para simular la respuesta de
los procesos hidrológicos a cambios en las condiciones ambientales, por ejemplo,
el incremento de la precipitación y la escorrentía, junto con la disminución de
la infiltración a causa del crecimiento urbano. Los resultados típicamente se
utilizan en la planeación y manejo de las obras hidráulicas, así como en el
diseño de protocolos de protección civil.

![Ciclo hidrologico](/assets/proyectos_apc/iai_fichas/ciclo_hidrologico.png)
<br>
**Figura 1.** *Ciclo hidrológico*
<br>

Cómo se usó
-----------

Con el paso de la historia, la Cuenca del Valle de México pasó de ser de tipo
endorreico (que originalmente afluía al antiguo sistema de lagos de Chalco,
Xochimilco, Texcoco, Zumpango y Cuautitlán) a una de tipo artificialmente
exorreico (que ahora afluye al Río Pánuco gracias a las grandes obras de
drenaje). Por este motivo, la modelación hidrológica de cuencas de MEGADAPT
simula el comportamiento de un sistema regional de cuencas artificialmente
exorreica, pero que tiende a comportarse como una cuenca naturalmente
endorreica. Para ello, se distinguen las cuencas rurales de las cuencas urbanas
y semiurbanas, y se analizan los procesos de precipitación y evapotranspiración,
el escurrimiento superficial, y el escurrimiento vertical y horizontal de los
acuíferos. La modelación es de tipo distribuida (analiza por separado los
diferentes componentes del sistema), integrada (reúne los diferentes análisis en
un sistema de flujos de agua superficial y agua subterránea) y continua (a
través del tiempo).

Con respecto al agua superficial, se utiliza un modelo de escurrimiento
superficial acoplado a modelos de terreno. Los datos de entrada al modelo
incluyen diferentes escenarios de lluvia y cobertura del suelo. Para las cuencas
urbanas, también se consideran las capacidades de la red de drenaje que
transporta las aguas residuales y las pluviales. De esta forma, es posible
estimar en qué grado se mezclan las aguas pluviales con las residuales. Así, el
modelo calcula la vulnerabilidad a inundaciones con respecto al escurrimiento
pluvial que no puede ser transportado por dicha red. Adicio­nalmente, se
incorpora al modelo la subsidencia (o hundimiento diferencial) de la zona urbana
para generar mapas de inundación de aguas pluviales-residuales con distintos
escenarios de extracción de agua de los acuíferos.

Al respecto, el modelo de agua subterránea calcula el volumen y la velocidad con
la que los acuíferos de la región liberan o almacenan agua. Los datos que se
utilizan son el volumen por recarga vertical natural, el volumen por recarga
inducida, los volúmenes totales que ingresan y salen por flujo lateral
subterráneo, el volumen vertical desde el acuitardo superior lacustre, el
volumen vertical neto intercambiado con acuíferos inferiores, la descarga por
flujo base, la descarga por manantiales y el volumen extraído por bombeo.

Al conjuntarse los dos modelos anteriores, se logra una aproximación de la
exposición a riesgos por inundaciones en cada unidad de respuesta hidrológica en
la que se subdivide la Zona Metropolitana de la Ciudad de México para propósitos
de análisis (Fig. 2).

![Modelo inundaciones](/assets/proyectos_apc/iai_fichas/modelo_inundaciones.png)
<br>
**Figura 2.** _Resultado de Modelo de Inundaciones_
<br>

Literatura relevante
--------------------

-   Brooks, K. N., P. F., Ffolliott, H. M., Gregersen, & J. L., Thames. (1992).
    Hydrology and the management of watersheds. EUA. Iowa State University
    Press/Ames.
-   Chow, V. T. (Ed.). (1964). Handbook of applied hydrology. A compendium of
    water-resources technology. EUA. McGraw-Hill.
