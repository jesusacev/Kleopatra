Instalación y configuración de Software Kleopatra.
=========


- Se debe descargar GPG4win para windows.


- Procedemos a realizar la instalación a través del ejecutable, el cual incluirá kleopatra:


.. image:: ../imagenes/instalacion/Selección_070.png


.. image:: ../imagenes/instalacion/Selección_071.png


.. image:: ../imagenes/instalacion/Selección_072.png


.. image:: ../imagenes/instalacion/Selección_073.png


.. image:: ../imagenes/instalacion/Selección_074.png


.. image:: ../imagenes/instalacion/Selección_075.png



- Ya podemos ingresar al software Kleopatara:


.. image:: ../imagenes/instalacion/Selección_076.png


- Procedemos a crear nuestros par de claves pública y privada (la clave pública servirá para cifrar los archivos y la privada para descifralos):


- Le damos a la opción Archivo y luego Nuevo par de claves:


.. image:: ../imagenes/configuracion/Selección_070.png


- Seguidamente Crear un par de claves personales OpenPGP:


.. image:: ../imagenes/configuracion/Selección_071.png


- Colocamos el nombre del propietario de las claves y su correo:  


.. image:: ../imagenes/configuracion/Selección_072.png


- En configuraciones avanzadas podemos definir el material de clave y la fecha de expiración de las mismas:


.. image:: ../imagenes/configuracion/Selección_073.png


- Verificamos los parámetros de revisión y de estar bien procedemos a crear:


.. image:: ../imagenes/configuracion/Selección_074.png


- Nos solicitará la contraseña para la clave privada:


.. image:: ../imagenes/configuracion/Selección_075.png


- Seleccionamos la opción de Hacer copia de respaldo de su par de clave y las guardamos en un sitio seguro:


.. image:: ../imagenes/configuracion/Selección_076.png


.. image:: ../imagenes/configuracion/Selección_078.png


- Nos solicitará la contraseña ingresada anteriormente para poder exportar la clave privada:


.. image:: ../imagenes/configuracion/Selección_079.png


- Luego nos mostrará un mensaje que la clave fue exportada con éxito:


.. image:: ../imagenes/configuracion/Selección_080.png


- Y finalizamos la creación:


.. image:: ../imagenes/configuracion/Selección_081.png


- Como podemos ver el par de claves fueron creadas satisfactoriamente:


.. image:: ../imagenes/configuracion/Selección_082.png


- Para que alguien nos envíe un archivo cifrado debemos suministrarle nuestra clave pública, nunca nuestra clave privada. La clave privada es la que nos servirá para descifrar los archivos.


Obtener Clave Pública
+++++++

- Para obtener la llave pública primero seleccionamos las claves de la empresa, le damos a la opción Archivo y luego Exportar:


.. image:: ../imagenes/cliente/Selección_071.png


.. image:: ../imagenes/cliente/Selección_072.png


.. image:: ../imagenes/cliente/Selección_073.png



Obtener par de Claves Pública y Privada
++++++++

- Simplemente las obtenemos con el respaldo que hicimos de nuestro par de claves durante la creación. En caso de que no tengamos a disposición el respaldo, la clave pública la obtenemos como se explicó anteriormente y la clave privada la obtenemos de la siguiente manera:


	- Seleccionamos el certificado que queramos. Le damos a la opción Archivo y luego Exportar claves secretas:

	
	.. image:: ../imagenes/cliente1/Selección_070.png


	- Nos solicitará el nombre del archivo a donde queremos exportar la clave privada:


	.. image:: ../imagenes/cliente1/Selección_071.png


	- Nos solicitará la contraseña de la clave privada:


	.. image:: ../imagenes/cliente1/Selección_072.png


	- Nos mostrará un mensaje que la clave secreta fue exportada con éxito:


	.. image:: ../imagenes/cliente1/Selección_073.png


Comuncación Bidireccional
+++++++++

- En caso de que necesitemos la comunicación bidireccional con un cliente, debemos generar un nuevo par de claves pública y privada,tal cual como generamos las de la Empresa, y suministrarles dichas claves, obteniendolas como se explicó anteriormente.


- El cliente debe importar esas claves de la siguiente manera (si se tiene el respaldo se realizan estos pasos pero con dicho respaldo):

	
	- Le damos a la opción Archivos y luego importar:

	
	.. image:: ../imagenes/cliente1/Selección_074.png


	- Seleccionamos la llave privada de donde la tengamos, que incluye tambien la llave pública:


	.. image:: ../imagenes/cliente1/Selección_075.png


	- Nos muestra un mensaje de que se ha importado y si deseamos establecer el nivel de confianza:


	.. image:: ../imagenes/cliente1/Selección_076.png


	- Veremos el resultado de la importación:


	.. image:: ../imagenes/cliente1/Selección_077.png


	- Ya veremos el certificado cargado en Kleopatra:


	.. image:: ../imagenes/cliente1/Selección_078.png


Canales para transmitir un mensaje cifrado
+++++++++


Un mensaje cifrado se puede transmitir por cualquier medio que permita llegar al destinatario. Los más comunes son vía correo o scp.


Si se quiere realizar la copia de archivos a través de scp en un Sistema Operativo windows, se debe instalar y configurar el software Cygwin.


Instalación y configuración de Cygwin
+++++++


- A continuación mostramos el link para la instalación de Cygwin:


Instalación de Cygwin: `enlace`__.

__ https://github.com/jesusacev/Cygwin/blob/master/guia/instalacion.rst


- Seguidamente, realizamos la configuración de Openssh a través de este link:


Configuración de Openssh: `enlace`__.

__ https://github.com/jesusacev/Cygwin/blob/master/guia/configuracion.rst




