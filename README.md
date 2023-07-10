# Blog de reseñas de películas y series

Este es un proyecto de blog que permite a los usuarios registrados publicar reseñas de películas y series. Los usuarios también pueden ver las reseñas y realizar acciones como iniciar sesión, registrarse, actualizar y eliminar sus propias publicaciones.

![image](https://github.com/RodoPellegrini/Rodo-Market/assets/135058071/020c7d0b-05a9-4da2-90fa-c4f667999dd4)



## Requisitos

- Python 3.x
- Django
- Django registration

## Instalación

1. Clona o descarga este repositorio en tu máquina local.
2. Abre una terminal y navega hasta el directorio del proyecto.

### Entorno virtual (opcional)

Si deseas, puedes crear un entorno virtual para este proyecto:

python3 -m venv myenv source myenv/bin/activate


### Instalar dependencias

3. Instala todas las dependencias del proyecto ejecutando el siguiente comando:

pip install -r requirements.txt


## Configuración

4. En el archivo `settings.py`, asegúrate de configurar la base de datos de acuerdo a tus necesidades.

5. Ejecuta las migraciones para crear las tablas de la base de datos:

python manage.py migrate


6. Crea un superusuario:

python manage.py createsuperuser


## Uso

7. Inicia el servidor de desarrollo:

python manage.py runserver


8. Accede a la aplicación en tu navegador web visitando `http://localhost:8000`.

9. Para acceder al panel de administración, ve a `http://localhost:8000/admin` e inicia sesión con la cuenta de superusuario creada en el paso anterior.

## Características y funcionalidades

- Página de inicio que muestra todas las reseñas publicadas por los usuarios registrados.
- Páginas de "Acerca de" y "Contacto" para proporcionar información adicional y permitir a los usuarios ponerse en contacto.
- Panel de control para los usuarios autenticados donde pueden administrar sus publicaciones.
- Formularios de registro, inicio de sesión y publicación de reseñas.

## Contribuciones

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Crea un fork del repositorio en GitHub.
2. Clona tu fork en tu máquina local.
3. Crea una rama para tus cambios:
git checkout -b feature/nueva-funcionalidad

4. Realiza los cambios deseados y realiza commits con mensajes descriptivos.
5. Empuja los cambios a tu repositorio remoto:
git push origin feature/nueva-funcionalidad

6. Abre una solicitud de extracción en GitHub.

¡Gracias por tu contribución!
