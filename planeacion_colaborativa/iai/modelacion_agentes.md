---
layout: page
title: ""
permalink: /iai/modelacion_agentes
---

<center><img src="/assets/logo_iai.png" alt="logo iai"></center>

Modelación Basada en Agentes
=============================

La Modelación Basada en Agentes (MBA) es una técnica que se utiliza para simular
cómo las conductas individuales determinan la evolución de un sistema. Consiste
en una colección de agentes, un conjunto de reglas de comportamiento y un
entorno o ambiente. Un agente constituye la unidad elemental e indivisible de un
sistema, por ejemplo, una persona, un grupo de personas, un hogar, o una
organización. Los agentes, por definición, tienen un propósito y responde
decidiendo o actuando conforme a las reglas que rigen su comportamiento. Éstas
diferencian a cada agente, definen las interrelaciones entre los agentes y el
ambiente, y establecen la secuencia de acciones con el tiempo. Las reglas se
activan bajo condiciones distintas. El comportamiento puede ser reactivo
(llamado cambio pasivo) o proactivo (llamado anticipatorio). Al actuar, cada
agente va modificando el ambiente hasta que se alcanza el estado de equilibrio y
se genera un patrón general de comportamiento que ya no cambia.

El comportamiento dinámico que implica toda MBA se genera al momento en que los
agentes hacen un barrido del ambiente y evalúan su situación. De esta forma, la
MBA involucra tres cuestiones esenciales. La primera es la cognición, que se
refiere a cómo los agentes perciben y aprenden acerca de los cambios en su
entorno. La cognición considera explícitamente cómo el cambio o adaptación del
comportamiento de un agente modifica la respuesta general de un sistema en su
conjunto. Ello conduce a la segunda cuestión que es la emergencia de patrones
geográficos que resultan del comportamiento homogéneo de los agentes en el
tiempo y el espacio. Así, dichos patrones presentan un orden que se repite en
las diferentes escalas, aunque puedan parecer como irregulares a primera vista.
La tercera cuestión destaca la importancia de concebir dichos patrones como
resultado de interacciones de redes de agentes y su entorno. Las interrelaciones
entre agentes pueden ser de cooperación o de conflicto. Además, los agentes
pueden aprender, adaptarse y mejorar sus decisiones con el tiempo. En el
contexto transdisciplinario, consecuentemente, la MBA se utiliza para dilucidar
qué estructuras sociales emergen a partir de acciones de agentes individuales y,
a su vez, cómo estas estructuras afectan las creencias, valores e intereses de
cada agente. Al combinarse con los sistemas de información geográfica, la
capacidad de la MBA se amplía hacia la representación del comportamiento de los
agentes en el tiempo y el espacio. De esta manera, es posible entender por qué y
cómo evolucionan patrones geográficos como la ocupación territorial, por
ejemplo.

![Modelacion basada en agentes](/assets/proyectos_apc/iai_fichas/modelacion_agentes.png)
<br>
**Figura 1.** _Representación esquemática de la MBA integrada al SIG-MMC_
<br>

Cómo se usó
-----------

En MEGADAPT, la MBA se emplea para analizar aquellos procesos socio-ecológicos
que inciden en la emergencia de riesgos socio-hidrológicos de la Zona
Metropolitana de la Ciudad de México. En concreto, la MBA se utiliza para
generar experimentos virtuales (que consisten en aplicar tratamientos a partes
aisladas de un sistema y observar qué ocurre). De esta manera, se busca aislar y
analizar los fenómenos sociales que determinan la vulnerabilidad a las
inundaciones, la escasez de agua y las afectaciones a la salud. En suma, los
experimentos virtuales esclarecen el papel de agente en el desencadenamiento de
los riesgos socio-hidrológicos específicos para cada grupo de la población
urbana.

Un aspecto innovador de MEGADAPT es la integración de la MBA y la SIG-MMC
(sistema de información geográfica y modelación multicriterio) para simular el
acoplamiento doble en el sistema socio-ecológico de la Zona Metropolitana de la
Ciudad de México. Como se ilustra en la figura 1, el modelo mental de una
autoridad hipotética se organiza en un modelo multicriterio (arriba a la
derecha) que integra las reglas de comportamiento. Estas se conectan a las capas
digitales del SIG (arriba a la izquierda). El primer acoplamiento consiste en el
uso de la MBA para sintetizar estos elementos y genera un primer patrón espacial
de vulnerabilidad. El segundo acoplamiento ocurre cuando este patrón cambia el
modelo multicriterio y, por ende, se modifican las reglas de comportamiento. Con
estas nuevas reglas, la MBA genera un segundo patrón espacial de vulnerabilidad
y así sucesivamente. En la figura, se ilustran tres salidas de la simulación
(abajo) que consisten en capas digital de la Ciudad de México que representan la
vulnerabilidad a riesgos socio-hidrológicos (gris = baja, amarillo = moderada;
naranja = alta) y los pesos de los criterios respectivos (figura de barras):
*(1)* en respuesta de la presión social, las autoridades ejecutan programas de
mantenimiento de infraestructura hidráulica para mantener la presión hidráulica
y disminuir la escasez de agua; *(2)* cuando se logran los objetivos del
mantenimiento, las acciones se dirigen a satisfacer la demanda de agua mediante
el incremento de la extracción, como respuesta a la presión social; *(3)* con el
tiempo, esta acción incrementa la subsidencia que exacerba las inundaciones y
las fallas de infraestructura.

Literatura relevante
--------------------

-   Cardoso, C., F., Bert, & G., Podestá. (2014). Modelos basados en agentes
    (MBA): definición, alcances y limitaciones <http://www.iai.int/wp-content/uploads/2014/03/Cardoso_et_al_Manual_ABM.pdf.>
-   García-Valdecasas, J. I. (2011). La simulación basada en agentes: una nueva
    forma de explorar fenómenos sociales. Reis 136:91-100
    doi:10.5477/cis/reis.136.91.
-   Heppenstall, A. J. J., Crooks, A. T. T., See, L. M. M., Batty, M. (Eds.).
    (2012). Agent based models of geographic systems. Springer Netherlands.
-   Railsback, S. F., & V., Grimm. (2012). Agent-based and individual-based
    modeling, a practical introduction. Princeton University Press, New Jersey.
