## Bitácora de comandos de Sistemas Operativos
##### Trabajo por: Diego Gómez Moreno

| Comando | Descripción |Ejemplo de uso |
| --- | --- | --- |
| `sudo ls` | Muestra la lista de carpetas en el directorio seleccionado. | `sudo ls /home` muestra todos los archivos de la carpeta home.
| `pwd` | Imprime en consola la ruta en la que estamos actualmente.| utilizar `pwd` muestra el output de en mi maquina de `/home/dgomezm`
|`cd /`| Cambia el directorio a la dirección asignada.| `cd /Desktop` nos redirige al directorio de escritorio.
|`nano`|Editor de texto version consola.| `nano archivo.txt` crea una archivo de texto con nombre 'archivo'.
|`ls -l`|Imprime los archivos en formato de lista.| `ls -l ~/Documents` muestra todos los archivos en lista del directorio Documents.
|`ls -a`|Imprime los archivos ocultos.|`ls -a /dgomezm` muestra todos los archivos, incluyendo los ocultos, del directorio dgomezm.
|`cat`|Imprime en la terminal el contenido del archivo.| `cat notas.txt` imprime el contenido del archivo de texto 'notas'.
|`mkdir`|Crea una carpeta nueva.| `mkdir Ulacit` crea una carpeta con nombre 'Ulacit'.
|`rm`| Borra un archivo.|`rm archivo.txt` borra el archivo con nombre de archivo.txt del sistema.
|`rm -R`|Borra una carpeta.|`rm -R Ulacit` borra la carpeta con nombre 'Ulacit'.
|`clear`|Borra todo el terminal.|`clear` deja la terminal en blanco.
|`rm -Rf`|Borra un archivo forzosamente.|`rm -Rf HelloWorld.sh` borra el archivo del sistema.
|`cd`|Lleva al directorio madre.|`cd` nos devuelve a la carpeta madre de la maquina.
|`top`|Muestra el estado de todos los procesos de la maquina.|`top` en la maquina muestra todos los processos con su ID.
|`htop`|Muestra el estado de los procesos de la maquina.|`htop` muestra los procesos de manera interactiva.
|`ps -auclx`|Terminal no interactiva, imprime en pantalla el estado de los procesos.|`ps -auclx` muestra todos los procesos con su ID. 
|`pstree`|Muestra todos los procesos en pantalla en forma de arbol.|`pstree` muestra todos los procesos en forma de arbol.
|`kill -9 'process id'`|Cierra una aplicacion o proceso activo.|`kill -9 12313` mata el proceso con ID '12313'.
|`ip a`|Muestra las direcciones IP del equipo en pantalla.|`ip a` muestra la IP del sistema. 
|`sudo apt update && sudo apt upgrade`|Actualizar el sistema.|`sudo apt update && sudo apt upgrade` descarga los archivos e instala la version mas nueva del sistema operativo.
|`root`|Acceder al usuario de administrador.|`root` nos pide el password, una vez ingresado, nos deja acceder al administrador del sistema. 
|`exit`|Salir del usuario de administrador.|`exit` nos saca del usuario root. 
|`whoami`|Muestra en pantalla que usuario esta siendo utilizado.|`whoami` muestra como output 'dgomezm', nombre del usuario que esta siendo utilizado.
|`sudo adduser`|Agrega un usuario al sistema.|`sudo adduser ULACIT` agrega un usuario con nombre de ULACIT al sistema.
|`sudo passwd`|Cambiar el password de dicho usuario.| `sudo passwd 1234` le asigna el password al usuario de ULACIT.
|`history`|Muestra el historial de todos los comandos utilizados.|`history` muestra todos los comandos utilizados anteriormente.
|`tail`|Muestra las ultimas diez lineas de un archivo.|`tail palabras.txt` muestra las ultimas diez lineas del archivo palabras.
|`sudo dmidecode --type 17 cat /proc/meminfo`|Muestra informacion en pantalla del tamaño de la memoria.|
|`free -h`|Muestra un desglose de la memoia y el swap.|
|`cat /proc/sys/vm/swappiness`|Muestra la cantidad de memoria que se destina a la RAM, es importante notar que va de 0 a 60.|
|`swapon`|Muestra la particiond de SWAP y el tamaño.|
|`sudo reboot`|Reinicia el equipo.|`sudo reboot` reinicia la maquina.
|`sudo mkdir /mnt/ram_disk sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk`|Crea una particion de la memoria RAM.|`sudo mkdir /mnt/ram_disk sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk` crea una particion de 1024mb en la memoria RAM.
|`du`|Muestra en pantalla el tamaño de un archivo.|`du uno.txt` muestra que el tamaño del archibo es 8.0K.
|`stat`|Muestra las fechas de modificacion de un archivo.|`stat /etc/resolv.conf` muestra las fechas de modificaciones del archivo resolv.conf.
|`file`|Muestra en pantalla el formato de un archivo.|`file archivo.txt` muestra que el formato del archivo es ASCII text.
|`chmod +r`|Le da permisos de lectura a un archivo.|`chmod +r archivo.txt` le da permisos de lectura al archivo.
|`chmod +w`|Le da permisos de escritura a un archivo.|`chmod +w programa.sh` le da permisos de escritura al archivo.
|`chmod +x`|Le da permisos de ejecucion a un archivo.|`chmod +x HelloWorld.sh`le da permisos de ejecucion al archivo.
|`chmod +rwx`|Le da todos los permisos a un archivo.|`chmod +rwx calculadora.sh` le da todos los permisos al archivo.
|`chown`|Usado para cambiar el propietario de un archivo.|`chown dgomezm archivo.txt` cambia el dueño del archivo.
|`df -h`|Muestra el espacio del disco usado.|`df -h` imprime el espacio usado en formato leible para el humano.
|`mount`|Utilizado para montaje de dispostivos.|`mkdir /media/usb-drive` y `sudo mount /dev/sdb1 /media/usb-drive` monta un USB al sistema.
|`gnome-disk-utility`|Muestra la particion del disco.|
|`ps -aux`|Muestra el proceso activo seleccionado.|`ps -aux 1203` muestra el proceso activo por ID de '1203'.
|`touch`|Utilizado para crear un archivo.|`touch archivo.txt` crea un archivo nuevo.
|`vim`|Editor de texto en consola.|`vim HelloWorld.sh` abre el archivo en el editor de texto vim.
|`service`|Permite inicializar y/o detener servicios.|`service mysql start` inicia MySQL.

**Comandos de Docker**
| Comando | Descripción |
| --- | --- |
|`build`|Permite al usuario crear su propia imagen de Docker. 
|`docker pull`|Sirve para descargar imagenes de un registro de Docker.
|`cat`|Combina varios archivos en uno, o crea uno nuevo.
|`search`|Inicia una busqueda recursiva en los directorios.
|`run`|Ejecuta un contenedor desde el ID de la imagen.

