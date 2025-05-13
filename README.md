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
