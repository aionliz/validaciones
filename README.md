paso previo para correr la app
Crear entorno virtual en Mac y windows

pip3 install pipenv Mac

pip install pipenv windows

Activar el entorno virtual 

pipenv shell


Instalar flask al proyecto 

pipenv install flask

pipenv install flask_app

pipenv install flask-bcrypt

pipenv install PyMySQL flask

Creación de archivo requirements

pipenv lock -m > requirements.txt

Correr un proyecto 

python server.py
