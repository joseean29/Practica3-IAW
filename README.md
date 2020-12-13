# Practica3-IAW
En esta práctica deberá automatizar la instalación y configuración de una aplicación web LAMP en dos máquinas virtuales EC2 de Amazon Web Services (AWS), con la última versión de Ubuntu Server. En una de las máquinas deberá instalar Apache HTTP Server y los módulos necesarios de PHP y en la otra máquina deberá instalar MySQL Server.

Ahora vamos a tener la pila LAMP repartida en dos máquinas virtuales, una se encargará de gestionar las peticiones web y la otra de gestionar la base de datos.

Una vez que hayas comprobado que todos los servicios de la pila LAMP están funcionando correctamente en las dos máquinas, instala y configura la aplicación propuesta.

Ten en cuenta que tendrás que modificar la configuración de MySQL Server para que permita conexiones remotas y también tendrás que revisar los privilegios del usuario que se conecta a la base de datos de la aplicación.

La arquitectura estará formada por:

    Una capa de front-end, formada por un servidor web con Apache HTTP Server.
    Una capa de back-end, formada por un servidor MySQL.
