Este script realiza un escaneo de puertos en una dirección IP utilizando la librería python-nmap. Permite identificar puertos abiertos y conocer información relevante sobre los servicios en ejecución.

Requisitos

Antes de ejecutar el script, asegúrate de tener instalados los siguientes paquetes:

Python 3.x

python-nmap

nmap (instalado en el sistema)


Instalación de dependencias

Para instalar python-nmap, usa el siguiente comando:

pip install python-nmap

Además, debes asegurarte de que nmap esté instalado en tu sistema:

En Debian/Ubuntu:

sudo apt install nmap

En macOS (usando Homebrew):

brew install nmap

En Windows:
Descarga e instala nmap desde nmap.org y agrégalo al PATH si es necesario.

Uso

Ejecuta el script con el siguiente comando:

python scan.py

Por defecto, el script escaneará los puertos del 21 al 80 en la dirección IP 192.168.100.18. Puedes modificar estos valores en el código fuente si es necesario.

Nota:

Se requieren permisos de administrador para ciertos escaneos avanzados.

No abuses del escaneo de puertos en redes ajenas sin autorización.
