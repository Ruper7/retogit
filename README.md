
# Introduccion a Github 
![](https://cdn.icon-icons.com/icons2/844/PNG/512/Github_icon-icons.com_67091.png)

## Tabla de Contenidos

1. [Crear un nuevo repositorio](#crear-un-nuevo-repositorio)
2. [Subir la carpeta src de java al repositorio](#subir-la-carpeta-src-de-java-al-repositorio)
3. [Crear una rama en el repositorio](#crear-una-rama-en-el-repositorio)
4. [Descargar el contenido de la rama al repositorio local](#descargar-el-contenido-de-la-rama-al-repositorio-local)
5. [Crea una clase nueva en java y realiza la actualización de la rama en el repositorio](#crea-una-clase-nueva-y-realiza-la-actualización-de-la-rama-en-el-repositorio)
6. [Guardar modificaciones realizadas en Java y subirlas al repositorio](#guardar-modificaciones-realizadas-en-java-y-subirlas-al-repositorio)
7. [Realizar comprobacion de los cambios](Realizar-comprobacion-de-los-cambios)
8. [Fusionar rama con el main del repositorio](#fusionar-rama-con-el-main-del-repositorio)

## Crear un nuevo repositorio

Hacemos clic en ***Repositories*** y esto nos llevará a una interfaz en la que tendremos que indicar el nombre del repositorio.
Podemos indicar si será *private* (nadie podrá ver dicha publicación) o *public* (quedará a la vista en GitHub) e incluimos un ***Readme*** para incluir información sobre el proyecto que se ha realizado.



![Imagen de Portada](imagenes/Imagen1.png)


## Subir la carpeta src de java al repositorio

Accedemos al repositorio y desplegamos la pestaña ***Add file***, hacemos clic en ***Upload file***.


![Imagen de Portada](imagenes/Imagen2.png)


Esto nos llevará a una nueva interfaz para subir la carpeta.

Tenemos dos maneras de incluir la carpeta src de java:
  - ***Choose your files***: podemos acceder a la ruta donde está la carpeta que queremos subir.
  - Arrastramos la carpeta al recuadro.
    

![Imagen de Portada](imagenes/nueva.jpg)



## Crear una rama en el repositorio

Dentro del repositorio hacemos clic en ***main***, escribimos el nombre de la nueva rama y de forma automática nos indica si queremos crearla mediante el mensaje ***Branch desarrolloPresona from main***. Hacemos clic y ya tendríamos creada la nueva rama.


![Imagen de Portada](imagenes/Imagen3.png)



## Descargar el contenido de la rama al repositorio local

Debemos instalar ***GitHub Desktop***. Url para la instalación (https://desktop.github.com/?ref_cta=download+desktop&ref_loc=installing+github+desktop&ref_page=docs).

Una vez instalado, abrimos el programa y seleccionamos ***File*** y clic en ***Clone***. De esta manera hemos conseguido clonar nuestra rama *main* a nuestro repositorio local.


![Imagen de Portada](imagenes/Imagen4.png)



## Crea una clase nueva en java y realiza la actualización de la rama en el repositorio

Creamos una nueva clase en la carpeta src de java.  
De forma automática, GitHub Desktop detectará el cambio que se ha realizado y nos lo reflejará con un recuadro en verde.  
Debemos dejar un comentario con las modificaciones que hemos realizado en el recuadro inferior de la izquierda. En mi caso he anotado *Nueva clase - Personas*.  
Realizamos un ***commit to main*** para que los cambios queden guardados.  
Finalmente realizamos un ***Push*** para que quede subido y actualizado en el repositorio.  


![Imagen de Portada](imagenes/Imagen5.png)



## Guardar modificaciones realizadas en Java y subirlas al repositorio

Escribimos dentro de la clase nueva que habíamos creado en java e inmediatamente, GitHub Desktop nos informará de la modificaciones que se ha realizado.  
Volvemos a dejar comentario en el recuadro inferior de la izquierda. En mi caso *Edición clase - Personas*.  
Nuevamente volvemos a realizar un ***commit to main*** para que los cambios queden guardados en el repositorio *main* y finalmente un ***Push*** para subirlo a repositorio.


![Imagen de Portada](imagenes/Imagen6.png)



## Realizar comprobacion de los cambios

Para comprobar todos los cambios que hemos realizado, entramos en GitHub, accedemos al repositorio creado y hacemos clic en la carpeta ***src*** de java.  
Dentro podemos encontrar los ficheros y clases que se habían creado y modificado.



![Imagen de Portada](imagenes/Imagen7.png)



## Fusionar rama con el main del repositorio

Vamos a subir una imagen a la rama que habíamos creado nueva con el nombre *desarrolloPersona*. Seguiremos los mismos pasos que seguimos al subir la carpeta src en la rama main.  
Una vez realicemos el ***commit***, accedemos nuevamente a la rama *desarrolloPersona* para confirmar que se ha subido correctamente como se puede ver en la imagen.



![Imagen de Portada](imagenes/Imagen8.png)



Nuevamente accedemos a GitHub Desktop, seleccionamos la rama *desarrolloPersona* y refrescamos para confirmar si se han realizado cambios. Nos confirmará que si se han realizado.
Podremos elegir entre dos opciones:
  - ***Previwe Pull***: previsualizar los cambios sin guardar los cambios.
  - ***Create Pull request***: guardará los cambios en la carpeta local de nuestro pc.

    

![Imagen de Portada](imagenes/Imagen9.png)



En la imagen podemos ver que se ha producido una nueva modificación, la subida de la imagen que hemos realizado.  
Una vez seleccionemos ***Create Pull request*** los cambios quedarán guardados en nuestra carpeta local del pc.



![Imagen de Portada](imagenes/Imagen10.png)



El cambio que he llevado a cabo es duplicar la imagen que hay en nuestra carpeta local del pc. Como muestra la imagen, ahora existen dos imágenes.



![Imagen de Portada](imagenes/nuvea1.JPG)



Una vez duplicada la imagen, al acceder a GitHub Desktop, aparecerá el símbolo *"+"* en verde indicando que se han realizado cambios.
Antes de hacer un ***commit***, dejamos título (en mi caso el texto duplico imagen) y descripción de la modificación realizada (en mi caso subo copia duplicada de imagen).


Realizamos ***Pusch origin*** para subir los cambios en la rama que hemos seleccionado que en nuestro caso será *desarrolloPersonal*.



![Imagen de Portada](imagenes/Imagen11.png)



Comprobamos que los cambios se han realizado correctamente en la rama que hemos indicado y no en el main.

***RAMA main***
Podemos comprobar que las imágenes no están subidas en el main.

![Imagen de Portada](imagenes/Imagen12.png)


***RAMA desarrolloPersona****
Confirmamos que las dos imágenes están en la rama desarrolloPersona.

![Imagen de Portada](imagenes/Imagen13.png)



Finalmente vamos a realizar la fusión de las dos carpetas haciendo clic en ***Compare&pull request***. Se puede ver en la pantalla anterior un aviso en amarillo.   
Esta fusión clonará lo que tiene la rama *desarrolloPersona* a la rama *main*.  
La rama *main* obtendrá lo nuevo de la rama *desarrolloPersona* y mantendrá lo que tenía hasta el momento.

Una vez hagamos clic en *Compare&pull request*, nos llevará a una interfaz en la que dejaremos comentario de lo que hemos realizado y nuevamente hacemos clic en ***Create pull request*** para traer los documentos del local al servidor.



![Imagen de Portada](imagenes/nueva2.jpg)



Si todo está correcto que será confirmado con el circulo en verde, finalizamos con ***Merge pull request***(fusionar). 



![Imagen de Portada](imagenes/nueva3.jpg)



***RAMA main***
En la siguiente imagen comprobamos que están las imágenes que anteriormente no existían en esta rama.

![Imagen de Portada](imagenes/Imagen14.png)
