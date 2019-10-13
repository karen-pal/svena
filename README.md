
#Setup
Para ejecutar el proyecto primero vamos a necesitar dos cosas:

    * Python: (http://python.org)
    * Virtualenv (https://virtualenv.pypa.io/en/latest/)

Una vez instalado todo, vamos a crear un entorno virtual en nuestra carpeta de trabajo

    $ virtualenv -p python3 my-env
    $ source ./my-env/bin/activate
    (my-env) $

Instalar en la virtenv:
	(my-env) $ pip install djangocms-installer

#Ejecutar
Para correr, dentro de la carpeta mysite:

	(my-env) $ python3 manage.py runserver

