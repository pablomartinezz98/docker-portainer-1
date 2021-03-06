<img src="./imagenes/MI-LICENCIA88x31.png" style="float: left; margin-right: 10px;" />

# Docker Portainer
![logo portainer](imagenes/portainer.png)
## Descripción
El proyecto consiste en estudiar la herramienta Portainer, que nos permite el despliegue de contenedores utilizando una interfaz gráfica.
## Índice
### 1.- Introducción
Docker [Portainer](https://www.portainer.io) es una herramienta gráfica que nos permite trabajar con docker desde lo que podríamos llamar una especie de "Back-End", el cual accederemos desde el navegador web, es una alternativa simple y sencilla para aquellos que no quieran utilizar magnífica CLI. Aquellos que hayáis trabajado con un CMS de administración como [Webmin](https://www.webmin.com) veréis muchas similitudes en su interfaz, la implementación es bastante sencilla ya que lo lanzaremos como si de un contenedor más se tratase.
### 2.- Instalación
Al bajarnos la imagen de DockerHub tendremos que especificar tambien el usuario ya que no es una imagen oficial de docker

![pull de la imagen](imagenes/poolDeLaImagen.png)

`docker pull portainer/portainer`

Levantamos la imagen con docker run...

`docker run -d --name portainer -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer`

![pull de la imagen](imagenes/poolDeLaImagen.png)

Comprobamos que esta corriendo la imagen...
### 3.- Acceso
.... 
### 4.- Descripción del panel de control.
....
### 5.- Despliegue de un contenedor httpd con una paǵina personalizada y mapeado por el puerto 8082.
.....
## Referencias
- <https://markdown.es>
- <https://www.portainer.io>
- <https://www.danielmartingonzalez.com>
- <https://hub.docker.com>
- <https://victorhckinthefreeworld.com>
- <https://alexpro.sytes.net>
- <https://www.statdeveloper.com/>
## Conclusión
....