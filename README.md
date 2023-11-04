# Configuración básica de Heroku y FastAPI

## Lista de Archivos necesarios

Archivos de configuración necesarios para ejecutar la API en Heroku

|No.|Archivo|Descripción|
|--|--|--|
|1.|.gitignore|Archivos y directorios que no se suben al repositorio|
|2.|requirements.txt|Librerias necesarias para ejecutar la api|
|3.|runtime.txt|Versión de Python que se usara en Heroku|
|4.|Procfile|Configuración de Heroku para ejecutar la api|
|5.|main.py|Hola mundo en FastAPI|
|6.|README.md|Documento de referencia|

## Run API

Comando para ejecutar la API de forma local

```bash
gunicorn -k uvicorn.workers.UvicornWorker --bind 0.0.0.0:8000 main:app
```
