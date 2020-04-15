# py-django-api-rest
Ejemplo de api rest creada con django rest framework

## Uso

Clona el repositorio y luego de ello debes realizar la instalación de dependencias. Yo uso pipenv así que te dejaré el comando que uso con dicho gestor:

	pipenv install

Luego de esto, deberás generar las migraciones de base de datos:

	cd mysite
	python manage.py migrate

Crea un usuario administrador con: 

	python manage.py createsuperuser

Enciende el servidor: 

	python manage.py runserver


Revisa tu localhost en el puerto 8000, allí está tu api rest.



### Información adicional

cristian.o.rincon.b@gmail.com
