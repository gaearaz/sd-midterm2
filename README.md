# Examen 1 - Sistemas Distribuidos

## Integrantes
- Juan David Bolaños - A00077464
- Andrés Zapata - A00077512

## 0. Sobre el proyecto

Este proyecto consta de una aplicación en python que levanta una API Rest cuya documentación tiene conformidad con el estándar OpenAPI, esta API cuenta con diferentes servicios que permiten la gestión de una base de datos de usuarios alojada en un cluster de MongoDB a través de peticiones HTTP.

A continuación se muestra la base de datos y la colección a la que se conectan los servicios de la API

![Alt text](images/atlas.png"App running")

## 1. Preparación proyecto

Este proyecto requiere instalar python 3.7 junto a su manejador de paquetes pip, una vez se tiene instalado correr los siguientes comandos para instalar las librerías necesarias, las cuales se encuentran en el archivo *requirements.txt*, y para ejecutar la aplicación en localhost por el puerto 5000

~~~
    python3 -m pip install -r requirements.txt
    python3 -m pip install pymongo[srv]
    python3 src/handlers.py
~~~

Una vez ejectuado esos comandos se espera ver lo siguiente:

![Alt text](images/python_run.png?raw=true "App running")


