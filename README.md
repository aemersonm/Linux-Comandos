# Linux-Comandos @author Emerson Alvarado Mora

|   Comandos   |            Descripción                 |                     Ejemplos de Uso                     |
|----------|----------------------------------------|---------------------------------------------------------|
|  clear   | Limpia el contenido actual de la consola | Se digita "clear" y el contenido en consola se limpiará |
| ip addr  |  Se obtiene la dirección IP de la MV   | Se digita "ip addr" y se obtendrá inet IP_ADDRESS.      |
|sudo apt-get update | Instala las versiones más nuevas de todos los paquetes instalados en el sistema | Se digita "sudo apt-get update" y se iniciará el proceso de actualización de los paquetes.| 
| sudo pacman -Syuu | Comando para distribuciones basadas en Arch Linux, instala las versiones más nuevas de todos los paquetes instalados en el SO | Se digita "sudo pacman -Syuu" y se iniciará el proceso de actualización de los paquetes |
| sudo pacman -S apache | Instala Apache en distribuciones basadas en Arch | se digita el comando "sudo pacman -S apache" y se iniciará la instalación de Apache |
| sudo pacman -S neofetch | Instala Neofetch en distribuciones basadas en Arch | se digita el comando "sudo pacman -S neofetch" y se iniciará la instalación de Apache |
| uname -a | Muestra información general sobre el SO | Se digita el comando "uname -a" y en consola se mostrará la información general sobre el Sistema Operativo |
| mkdir | Crea una carpeta en un directorio específico | En el directorio donde se desea crear la carpeta, se digita el comando "mkdir utilidades" y la nueva carpeta se creará con el nombre "utilidades" |
| touch | Crea un archivo en una carpeta específica | En la carpeta donde se desea crear el archivo, se digita el comando "touch commands.txt" y el nuevo archivo se creará con el nombre "commands" |
| nano | Crea un archivo en una carpeta específica | En la carpeta donde se desea crear el archivo, se digita el comando "nano script.sh" y el nuevo archivo se creará con el nombre "script" |
| mv | Mueve una carpeta, archivo o directorio a una ubicación específica | Digitar el comando "mv /home/Desktop/script.sh" y el archivo script.sh se moverá al escritorio|
| cp | Copia una carpeta, archivo o directorio en una ubicación específica | Digitar el comando "cp /home/Desktop/script.sh" y el archivo script.sh se copiará al escritorio |
| rm | Elimina una carpeta, directorio o archivo | Digitar el comando "rm DIRECTORIO/CARPETA/ARCHIVO" |
| cd | Abreviatura de "Change Directory", se encarga de navegar por el directorio deseado | Se digita el comando "cd /home/ealvaradom997/utils" y en consola se navegará por el directorio ingresado y se mantendrá en la carpeta "utils". |
| ls | Muestra la lista del contenido del directorio deseado | Se digita el comando "ls Desktop" y aparecerá una lista de todos las carpetas y archivos almacenados en el  escritorio. |
| ls -l | Muestra la lista de contenido del directorio deseando incluyendo los permisos de lectura, escritura y ejecución de cada carpeta o archivo | Se digita el comando "ls -l Desktop" y se mostrará una lista de todas las carpetas y archivos almacenados en el escritorio con sus respectivos usuarios creadores y permisos de ejecucion, escritura y lectura |
| man | Muestra en consola el manual de otro comando | Se digita el comando "man cp" y mostrará el manual de uso del comando |
| useradd | Se encarga de agregar un usuario al SO | Se digita el comando "user add ealvaradom097" y el usuario ealvaradom097 será agregado al sistema |
| sudo su | Comando utilizado para acceder al usuario root dentro de la consola | Al digitar el comando "sudo su" se podrá acceder al usuario root y realizar acciones con permisos especiales |
| whoami | Comando utilizado en scripts de shell para validaciones de nombre de usuario que ejecuta el script | Se ingresa el comando "whoami" y en la salida se devolverá el nombre del usuario que está haciendo la ejecución |
| more | Se utiliza para visualizar el contenido de un archivo, pero NO se podrán realizar modificaciones | Se digita el comando "more matricula.txt" y se mostrará el contenido del archivo sin opción de modificación |
| tail -n | La salida de este comando muestra las últimas n cantidad de líneas de un archivo | Se digita el comando "tail -n 5 script.txt" y en la salida se mostrarán las últimas 5 líneas del archivo "script.txt" |
| head -n | La función de este comando es lo contrario al comando tail, ya que head -n muestra las primeras n cantidad de líneas de un archivo | Se digita el comando "head -n 2 script.txt" y en la salida se mostrarán las primeras 2 líneas del archivo "script.txt" |
| passwd | Se utiliza para cambiar la contraseña de un usuario del SO | Se digita el comando "sudo passwd ealvaradom097" y posteriormente aparecerá un espacio para ingresar la nueva contraseña para el usuario ealvaradom097 |
| history | Al utilizar este comando, de forma predeterminada se mostrará una lista de los últimos 500 comandos utilizados | Se digita el comando "history" y se mostrarán en consola los últimos 500 comandos utilizados |
| sudo apt install screenfetch | Instala screenfetch, programa encargado de recopilar información general del sistema y mostrarla en pantalla | Al digitar el comando "sudo apt install screenfetch" se iniciará el proceso de descarga del programa |
| ps | Muestra la lista de procesos que están siendo ejecutados | Se ejecuta el comando "ps" y posteriormente se mostrará en consola una lista de los procesos activos en la sesión |
|  |
