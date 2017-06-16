# Linux server configuration project

The main scope is to create a linux server, on [Amazon Lightsail](lightsail.aws.amazon.com), with ssh access through key pair and not through password authentication.

## Server Data
### SSH access
* IP: 35.156.152.231
* port: 2200
* user: grader

### Catalog App
* url: http://snicholas.ddns.net
### Port opened via UFW
* 22
* 80/tcp
* 2200/tcp
* 123/tcp
* 123

## Server packages:
After have update the packages list via `sudo apt-get install update` and having updated the system with `sudo apt-get upgrade' the following packages have been installed:
* apache2 
* libapache2-mod-wsgi
* postgresql
* python-psycopg2
* python-flask
* python-sqlalchemy
* python-pip
* ntp

Python module installed via pip `sudo pip install <module_name>` :

* flask
* sqlalchemy
* requests
* oauth2client
