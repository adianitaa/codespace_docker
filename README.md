# Introducción a Docker

Docker es una plataforma abierta para desarrollar, enviar y ejecutar aplicaciones. Permite empaquetar una aplicación y sus dependencias en un contenedor, garantizando que funcione de manera consistente en cualquier entorno.

## ¿Qué es Docker?

Docker es una herramienta que utiliza contenedores para ejecutar aplicaciones de manera aislada. Los contenedores son ligeros, portátiles y consistentes, lo que permite que una aplicación funcione en cualquier entorno (ya sea en tu máquina local, en un servidor de producción o en la nube) sin importar las configuraciones del sistema operativo o las dependencias.

## Beneficios de usar Docker

- **Portabilidad**: Puedes crear y ejecutar contenedores en cualquier lugar.
- **Aislamiento**: Cada contenedor es independiente, lo que significa que no afectan a otros contenedores ni al sistema operativo.
- **Eficiencia**: Docker utiliza recursos de manera eficiente al compartir el kernel del sistema operativo entre contenedores, lo que lo hace más ligero que las máquinas virtuales.
- **Consistencia**: Los contenedores garantizan que la aplicación se ejecute de la misma manera en desarrollo, pruebas y producción.

## Conceptos clave

### 1. **Contenedor**
Un contenedor es una unidad ligera, autónoma y ejecutable que incluye todo lo necesario para ejecutar una aplicación: código, entorno de ejecución, bibliotecas, variables de entorno y archivos de configuración.

### 2. **Imagen**
Una imagen es una plantilla de solo lectura que define lo que está dentro de un contenedor. Docker utiliza imágenes para crear contenedores. Las imágenes son versiones congeladas de aplicaciones.

### 3. **Dockerfile**
El `Dockerfile` es un archivo de texto que contiene todas las instrucciones necesarias para crear una imagen. Con él, puedes automatizar el proceso de construcción de contenedores.

### 4. **Docker Hub**
Docker Hub es el repositorio en línea donde puedes almacenar y compartir imágenes de Docker. Puedes encontrar imágenes oficiales de Docker para muchas aplicaciones comunes (como bases de datos, servidores web, etc.).

## Primeros Pasos con Docker

### 1. **Instalar Docker**

#### Windows:
- Descarga Docker Desktop para Windows desde [aquí](https://www.docker.com/products/docker-desktop).
- Sigue las instrucciones de instalación.
  
#### macOS:
- Descarga Docker Desktop para macOS desde [aquí](https://www.docker.com/products/docker-desktop).
- Sigue las instrucciones de instalación.

#### Linux:
- En Linux, puedes instalar Docker siguiendo las instrucciones oficiales para tu distribución: [Instrucciones de instalación](https://docs.docker.com/engine/install/).

### 2. **Verificar la instalación**
Una vez instalado Docker, abre una terminal o PowerShell y ejecuta:
```bash
docker --version
