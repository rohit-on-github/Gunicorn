# Gunicorn

Scripts from learning Gunicorn

#### gunicorn_env

Constains the environment for the Gunicorn in Django Project

#### Gunicorn_Demo

Django project in which gunicorn will be integrate

#### Running Command

gunicorn --version
pip install gunicorn
gunicorn gunicorn_demo.wsgi:application
DJANGO_SETTINGS_MODULE=config.settings gunicorn config.wsgi
cd /etc/systemd/system
sudo ln -s /Gunicorn_Demo/systemd/Gunicorn_Demo.service #Path to the service
ls -l Gunicorn_Demo.service
sudo systemctl start Gunicorn_Demo
sudo systemctl status Gunicorn_Demo
