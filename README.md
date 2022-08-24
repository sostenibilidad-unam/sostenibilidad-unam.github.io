# Página Web con perfiles personales y viñetas del trabajo que ocurre en el Laboratorio Nacional de Ciencias de la Sostenibilidad, UNAM

http://lancis.ecologia.unam.mx


# Guía de edición

Se puede agregar y editar contenidos acá:

<https://github.com/sostenibilidad-unam/sostenibilidad-unam.github.io/tree/master/content>

Todos los contenidos deben usar [Markdown](https://duckduckgo.com/?q=gu%C3%ADa+de+markdown&ia=web) o [reStructuredText](https://guia-de-restructuredtext.readthedocs.io/es/latest/ch_primeros_pasos.html). Esto implica que se puede mezclar HTML de ser necesario, por ejemplo para empotrar un video.

Para correr un servidor local y probar las modificaciones sin tener que esperar a que se actualice la página, sigue estás instrucciones.

0. clona el repositorio
    ```git clone git@github.com:sostenibilidad-unam/sostenibilidad-unam.github.io.git```
1. haz un entorno virtual de python
    ```virtualenv -p python3 venv3```
2. activa el entoro virtual
    ```source venv3/bin/activate```
3. instala los requerimientos 
    ```pip install -r requirements.txt```
4. instala nodejs
    ```https://github.com/nodejs/help/wiki/Installation```
5. instala tailwind
    ```npm install tailwindcss```
6. corre el servidor de tailwind
    ```make twserver```
7. corre el servidor de desarrollo
    ```make devserver```

Para ediciones posteriores, yo con todo instalado:

1. activa el entoro virtual
    ```source venv3/bin/activate```
2. corre el servidor de tailwind
    ```make twserver```
3. corre el servidor de desarrollo
    ```make devserver```  


## Viñetas

Van en el directorio "Nuestro trabajo". Lo más fácil es basarse en previas viñetas para crear nuevas.

Las viñetas se decoran con imágenes que deben tener proporción 4:3, y subirse a este directorio:

<https://github.com/sostenibilidad-unam/sostenibilidad-unam.github.io/tree/master/content/images/portadas>

## Personal

Páginas para "perfil LANCIS".

