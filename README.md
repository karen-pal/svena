#Setup
Para ejecutar el proyecto primero vamos a necesitar dos cosas:

    * Python: (http://python.org)
    * Virtualenv (https://virtualenv.pypa.io/en/latest/)

Una vez instalado todo, vamos a crear un entorno virtual en nuestra carpeta de trabajo

    $ virtualenv -p python3 my-env
    $ source ./my-env/bin/activate
    (my-env) $

Instalar en la virtenv, dentro de la carpeta que tenga el archivo requirements.txt:
	(my-env) $ pip install djangocms-installer
	(my-env) $ pip install aldryn-newsblog
	(my-env) $ pip install -r requirements.txt

#Ejecutar
Para correr, dentro de la carpeta que tenga manage.py:

	(my-env) $ python3 manage.py runserver

