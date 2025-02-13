# Zabbix Docker Setup

Este proyecto utiliza **Docker** y **Docker Compose** para levantar un entorno de monitoreo con Zabbix. A continuación, se detallan los pasos para instalar, configurar y ejecutar Zabbix en tu máquina.

## Prerrequisitos

Antes de comenzar, asegúrate de tener instalados los siguientes programas:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Pasos para levantar Zabbix

### 1. Clonar o descargar el repositorio

Si no tienes el archivo `docker-compose.yml`, clona o descarga este repositorio.

```bash
git clone https://github.com/Gabriel3002-maker/zabbix.git
```
Ingrese al repositorio

```bash
cd zabbix
```
Ejecuta el comando para levantar los contendores podras acceder a zabbix 
en el puerto 8081.

```bash
docker-compose up -d
```

Acceder en 
```bash
http://localhost:8081
```



### 2.- Creedenciales

Las credenciales predeterminadas son:

Usuario: zabbix
Contraseña: zabbix
