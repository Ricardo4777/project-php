## Requisitos

- **Docker**: Asegúrate de tener Docker instalado en tu sistema. Puedes [descargar Docker aquí](https://www.docker.com/get-started) si aún no lo tienes instalado.

## Pasos para ejecutar el proyecto

### 1. Construir la Imagen Docker

Desde la carpeta `LENGUAGE-PHP`, abre una terminal y ejecuta el siguiente comando para construir la imagen Docker:

```bash
docker build -t php-andy .


docker run -p 8080:80 php-andy
Este comando:

-p 8080:80: Mapea el puerto 80 dentro del contenedor al puerto 8080 en tu máquina, permitiéndote acceder a la aplicación en http://localhost:8080.
php-docker: Especifica la imagen a utilizar para crear el contenedor.
La aplicación debería estar disponible en http://localhost:8080 una vez que el contenedor esté en ejecución.