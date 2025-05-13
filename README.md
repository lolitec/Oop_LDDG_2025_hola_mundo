# Ejemplos de Programación Orientada a Objetos
## 1. Crear el archivo **.gitignore** para configurar los archivos que no se sincronizaran con el repositorio

````shell
*.pyc
_pychache_/
.venv/
````
## 2. Crear el **virtual environment**

Se crea el ambiente virtual de trabajo de python

````shell
python3 -m venv .venv
````

## 3. Iniciar el **virtual environment**

Se activa el **virtual environment** para instalar las librerias necesarias para el proyecto

````shell
source .venv/bin/activate
````

## 4. Actualizar **pip** dentro del **virtual environment**

Se actualiza la versión instalada de **pip** para poder descargar las ultimas versiones de las librerías.

````shell
pip install --upgrade pip
````

## 5. Verificar las librerías instaladas

Se verifica que librerías y versiones se tienen instaladas.

````shell
pip freeze
````

## 6. Instalar librerías

Se instalan las librerías que se van a ocupar en el proyecto.

````shell
pip install web.py
````
## 7. Crear el archivo **requirements.txt**

Se crea el archivo **requirements.txt** con las librerías y el número de versión utilizadas.

````shell
pip freeze > requirements.txt
````

## 8. Crear el archivo **runtime.txt**

Se crea el archivo **runtime.txt** con la versión de Python3 que se esta utilizando en el proyecto.

````shell
python3 -V > runtime.txt
````

## 9. Indexar los archivos creados con **git**

Se indexan los archivos y cambios realizados en el proyecto

````shell
git add .
````

## 10. Generar un **commit**

Se realiza un **commit** con un texto que describa los cambios realizados en el proyecto.

````shell
git commit -m "CREATED configuracion basica"
````

## 11. Realizar un **push**

Se realiza un **push** para subir los cambios realizados al repositorio de **Github**

````shell
git push -u origin main
````