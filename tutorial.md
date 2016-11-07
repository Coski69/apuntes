## Tutorial Debian

Tutorial sobre Debian.

### Boot Repair

http://www.matthiaskauer.com/2015/03/install-boot-repair-on-debian-from-ubuntu-ppa/

### Activar sudo:
´´´sh
su
apt-get install sudo
sudo adduser nombre_usuario sudo
´´´

### Actualizar Debian
´´´ sh
sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade && sudo apt-get autoremove
´´´

### Instalar instatador grafico de paquetes Debian.

´´´sh
sudo apt-get install gdebi
´´´

### Instalar mis aplicaciones favoritas

´´´sh
sudo apt-get install htop
sudo apt-get install libreoffice
sudo apt-get install transmission-gtk
´´´

equivalente a:
´´´sh
sudo apt-get install htop libreoffice transmission-gtk
´´´

### Ejecutar Scripts

´´´sh 
bash nombre_script.sh
´´´




