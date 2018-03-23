
Contenedores y VMs
--------------------

Docker trabaja con algo que se llama “contenedores de Linux” estos son un conjunto de tecnologías que juntas forman un contenedor (de Docker), este conjunto de tecnologías se llaman:

**Namespaces**: Permita a la aplicación que corre en un contenedor de Docker tener una vista de los recursos del sistema operativo.

**Cgroups**: Permiten limitar y medir los recursos que se encuentran disponibles en el sistema operativo.

**Chroot**: Permite tener en el contenedor una vista de un filesystem para el mismo, es decir, crea su propio entorno de ejecución con su propio root y home. es decirle al contenedor que va a ver solo ese filesystem y no va a poder ver nada mas.

Algunas de las características más notables de un contenedor son:

Los contenedores son más livianos (ya que trabajan directamente sobre el Kernel) que las maquinas virtuales.
No es necesario instalar un sistema operativo por contenedor.
Utiliza el sistema operativo de la maquina, no tiene un hypervisor.
Mayor cantidad de contenedores por equipo físico.
Es un proceso mas del SO.
Menor uso de los recursos de la máquina.
Mejor portabilidad.

Nos permite armar la imagen en un entorno y llevarlo a otro mas rapidamente que una vm.


![docker-vs-vm](https://github.com/4lbertoDelgado/platzi-docker/blob/master/img/docker-vs-virtual-machines.png?raw=true)
