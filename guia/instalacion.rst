Instalación y configuración de Software Kleopatra.
=========


- Se debe descargar GPG4 para windows.


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


- Nos solicitrá la contraseña para la clave privada:


.. image:: ../imagenes/configuracion/Selección_075.png


- Seleccionamos la opción de Hacer copia de respaldo de su par de clave y las guardamos a donde mejor nos parezca:


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


- En caso de que necesitemos la comunicación bidireccional con un cliente debemos generar un nuevo par de llaves pública y privada y suministrarselas.


- Prcocederemos a crear el par de claves para un cliente de la misma manera en que creamos las claves para la Empresa.


- El respaldo que hicimos de nuestro par de claves del cliente se lo enviarémos al respectivo cliente, para que pueda descifrar los archivos que le enviemos con su clave privada. De igual manera le enviaremos sólo la llave pública de la empresa para que pueda cifrar archivos que nos vaya a enviar.


- Para obtener la llave pública primero seleccionamos el de la clave que deseamos. Le damos a la opción Archivo y luego Exportar:


.. image:: ../imagenes/cliente/Selección_071.png


.. image:: ../imagenes/cliente/Selección_072.png


.. image:: ../imagenes/cliente/Selección_071.png


- Luego debemos proceder a instalar Cygwin para poder realizar una copia scp desde el sistema operativo Windows. Guiarse con este link:











