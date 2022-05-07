# Ejecutando contenedores
## Ejemplo 1
### 1. Mediante el comando *docker pull ubuntu:18.04* descargaremos de manera previa una imagen de ubuntu

[![imagen-2022-05-07-232433764.png](https://i.postimg.cc/fLfvpq3y/imagen-2022-05-07-232433764.png)](https://postimg.cc/hzhx7r1R)

### 2. Mediante el comando *docker run -it ubuntu:18.04 /bin/bash* crearemos un contenedor de ubuntu:18.04 y tener acceso a un shell en él

[![Captura-de-pantalla-2022-05-07-233123.png](https://i.postimg.cc/6pYS80tD/Captura-de-pantalla-2022-05-07-233123.png)](https://postimg.cc/XrBxh9Z8)

## Ejemplo 2
### Utilizaremos el comando *docker run ubuntu:18.04 ls /* para crear el contenedor y posteriormente que el contenedor pase a estar parado

[![imagen-2022-05-07-235512958.png](https://i.postimg.cc/52wBrkQz/imagen-2022-05-07-235512958.png)](https://postimg.cc/w1jRy2Vx)

## Ejemplo 4
### 1. Utilizaremos el comando *docker run -it -w /etc debian:9 ls* para crear un contenedor de debian 9 y mostrar el contenido de una carpeta establecida con el parámetro -w (Se nos instalara automaticamente la imagen de Debian)

[![imagen-2022-05-08-000819978.png](https://i.postimg.cc/KzJyx24g/imagen-2022-05-08-000819978.png)](https://postimg.cc/Q99zJvQX)

### 2. Utilizaremos el comando *docker ps* para mostrar los contenedores que se estan ejecutando

[![imagen-2022-05-08-001033850.png](https://i.postimg.cc/hvfNnQHH/imagen-2022-05-08-001033850.png)](https://postimg.cc/sGCT9xfc)

### 3. Utilizaremos el comando *docker ps -a* para mostrar todos los contenedores creados que se estan ejecutando o estan parados

[![imagen-2022-05-08-001302851.png](https://i.postimg.cc/vBcdYKnq/imagen-2022-05-08-001302851.png)](https://postimg.cc/VrQh4DDn)
