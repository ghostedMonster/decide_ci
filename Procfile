% prepara el repositorio para su despliegue.
release: sh -c 'cd decide && python manage.py migrate'
% especifica el comando para lanzar Decideasdf
web: sh -c 'cd decide && gunicorn --graceful-timeout=900 --timeout 900 decide.wsgi --log-file -'
