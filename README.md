# Práctica 3. Crea un site empleando Bootstrap


### Página principal: ``index.html``

La página web consta de 4 sub-páginas todas ellas interconectadas.t

La página principal tiene 4 secciones. La primera contiene un header, la cabecera, una seccion de marcas y un footer.
- En la cabecera tengo el logo de inditex, y un menu con Home(index.html), 
Marcas(index.html#marcas), Contacto(contacto.html), empleo(empleo.html)
y Inversores(inversores.html). Esta diseñado como una lista para que cuando tenga
resulacion estrecha como la de un movil no haya problemas, y se ponga
como una lista despegable.
- En el primer container tenemos una imagen directiva de Inditex, y dos links.
El primero "Como trabajamos" que esta referido a "empleo.html#trabajo" una seccion de empleo donde se explica
la etica y formula de trabajo. El segundo nos lleva a video.html, un video de presentacion de la compañia.
- En el segundo container he recopilado las marcas, cada una en un card donde viene el logo, una explicacion y un link
a la web oficial. Las cards se adaptan genial a los diferentes tamaños de pantalla.

#### Sub-página 1: ``video.html``
Como no tengo conocimientos aun de JS, he puesto el video cubriendo todo el background, manteniendo el menu de arriba.

#### Sub-página 2: ``contact.html``
Dentro de un card meto un formulario sencillo. Con el fondo gradiente y la card centrada queda muy bien.
#### Sub-página 3: ``empleo.html``
Aqui uso un card dark, y en el body meto un formulario de una linea. Gracias a la logica de columnas queda muy bien.
En el siguiente container tengo un formulario para mandar el cv en una card.
Despues tengo varios container dentro de la id trabajo, donde explico la dinamica de trabajo de inditex.
#### Sub-página 4: ``inversores.html``
En el primer container pongo datos financieros dentro de una tabla. Para que quede bien lo meto tambien la informacion en una card.
En el segundo hago la misma dinamica, pero pongo links de descarga de informes anuales.
Y por ultimo he puesto un script de una grafica del precio de la accion. Y por ultimo acompaño con numeros de contacto para accionistas e inversores.

#### carpeta informes: ``/informes``
En esta carpeta hay 6 informes anuales de los resultados de Inditex, esta carpeta es usada por la subpagina inversores.html que incluye informacion para inversores.

### DATO A TENER EN CUENTA: NO HE USADO TEMPLATES, TODO A MANO.