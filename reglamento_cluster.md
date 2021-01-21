---
layout: page
title: Reglamento del Cluster de Supercómputo en el LANCIS
bigimg: /assets/cluster_banner.jpg
permalink: /cluster/reglamento/
---

Enero de 2021

## 1 Introducción

La supercomputadora del Laboratorio Nacional de Ciencias de la 
Sostenibilidad del Instituto de Ecología es un recurso 
compartido. Tiene la capacidad atender a decenas de personas al mismo tiempo, 
por lo que es necesario observar algunas reglas para la convivencia armoniosa.

### 1.1 Infraestructura

La supercomputadora está constituida de decenas de computadoras 
interconectadas y configuradas para cooperar entre sí como si 
fueran una sóla. El instrumento entero se usa desde el nodo central, afectuosamente 
llamado "[Patung](https://duckduckgo.com/?q=patung+katsina&t=canonical&iar=images&iax=images&ia=images)". 
Es un equipo dedicado a mantener sesiones interactivas y despachar tareas a 
los nodos de cómputo.


## 2 Trabajos de cómputo

### 2.1 Instalación y configuración de software

Está permitido instalar el software que necesite para analizar sus datos directamente en su *home*.
Esta política permite una buena medida de autogestión por parte de todas.

Procure no re-instalar programas que sus colegas probablemente ya usan. Si usted colabora con
otras personas que usan el cluster, hable con ellas, tal vez se ahorre tiempo y esfuerzos.

La inmensa mayoría de los programas que se pueden ejecutar en nuestro cluster se pueden instalar en directorios personales. Pero a veces, algunos programas requieren permisos de administrador para instalarse en directorios
especiales del sistema. En esos casos hay que solicitar la instalación al administrador.

#### 2.1.1 Licencias de software

Las capacidades de usar, estudiar, modificar y redistribuir programas
son más adecuadas al proceso de investigación científica. Use software libre
siempre que pueda.

Procure no usar software privativo. Si tiene planes de usar software privativo, a pesar
de que conduzca a cuestionable ciencia no-reproducible, usted es responsable
por las licencias y otros permisos necesarios.

### 2.2 Fila de ejecución

Se ha instalado y configurado [HT-Condor](http://htcondor.org). Este sistema permite 
compartir la infraestructura brindando un acceso 
ordenado al conjunto entero de recursos. Es una cola en
la que las tareas de cómputo deben formarse para su 
ejecución.

Está prohibido ejecutar trabajos de cómputo sin usar HT-Condor. 

Está permitido editar y manipular archivos, también se permite ejecutar pruebas
breves de los jobs. Pero correr tareas de cómputo directamente en Patung tiene efectos
negativos para todas, de modo que esos procesos serán eliminados
sin aviso. Además no conviene, usar Condor es la única manera que garantiza la cantidad máxima
de recursos de cómputo.

## 3. Almacenamiento

El espacio en disco es un recurso limitado.

La supercomputadora cuenta con espacio para almacenar datos a la 
entrada, a la salida, y en condiciones intermedias de su 
procesamiento. Sin embargo ha sido diseñada para optimizar su 
capacidad de procesamiento, y no para tener una gran capacidad de 
almacenamiento. 

Por esta razón está prohibido el uso de la supercomputadora como 
servidor de almacenamiento a largo plazo. Se requiere que todas
sean juiciosas acerca de qué datos mantener en la 
supercomputadora, i.e. aquellos con los que estén trabajando.

Si usted ya procesó sus archivos, descárguelos y bórrelos. Si los necesita 
en un plazo mediano: comprímalos. 

Use el comando

```
df -h
```
para obtener un reporte de la cantidad de espacio libre. Debe estar siempre
debajo del 80% en todas las particiones que empiezan con /srv*. Por favor
sea proactiva acerca de mantener el uso de nuestros discos debajo de ese umbral.

### 3.1. Política de respaldos

Por lo limitado del espacio de almacenamiento, no hay ninguna provisión para hacer respaldos
de los archivos en los discos de la supercomputadora.
Es su responsabilidad mantener respaldos de sus archivos. Recuerde este mantra: "si mis
archivos no están almacenados en tres lugares distribuidos geográficamente, es casi
como si no existieran". Usar tres discos duros externos es relativamente barato y seguro.

No existe una mesa de ayuda. El soporte se brinda por correo electrónico,
escribiendo a la lista de usuarios o directamente al administrador.
Perdón por el párrafo fuera de contexto, es una medida jocosa para
verificar que los solicitantes lean el reglamento.


## 4. Nivel de Servicio

Este cluster está optimizado para alto rendimiento, no para
alta disponibilidad. Por ejemlpo: no tiene alimentación eléctrica redundante,
no está conectado a redes independientes, no tiene discos de reserva en espera.

Si bien lo cuidamos con diligencia, en ciertas circunstancias y
para ciertas tareas de mantenimiento se hace necesario reiniciarlo 
o apagarlo. Pasa poco, casi siempre de manera planificada,
y nunca han sido más de 6 horas al año.

Aún así, al usar este equipo usted debe ajustar sus expectativas, es probable
que no funcionará las 8,760 horas del año, cada año. 


## 5. Agradecimientos

La supercomputadora del LANCIS es el resultado del apoyo financiero del proyecto
de Laboratorios Nacionales de Conacyt y otros proyectos. Para justificar su uso continuado es 
reglamentario agradecer y notificar a la unidad de Supercómputo del LANCIS-Instituto de 
Ecología en aquellas publicaciones que hayan requerido el uso de la supercomputadora.
