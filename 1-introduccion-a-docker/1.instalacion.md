
Instalación
-----------------

En este caso veremos como instalar Docker en Linux, es importante saber que se debe tener un sistema operativo de 64 bits, los pasos son los siguientes:

Acceder a [get.docker.com](get.docker.com)

Copiar el comando para ejecutar el script.

Pegar el comando y ejecutar el script de instalación de Docker.

Verificar si Docker esta instalado con los comando docker info o docker version

Crear un “Hello World” con Docker usando el comando docker hello-world

----------
Para agregar usuario que tenga permisos para ejecutar el comando docker, se debe agregar al usuario al grupo docker creado duirante lña instalacion:

- **usermod -aG docker padeq**

O puede crear un usuario nuevo llamado *docker*:

- **useradd -g docker docker**
