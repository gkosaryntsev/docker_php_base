�������� ��������� ��� ���������� �� Windows

������������� Docker Toolbox 
https://www.docker.com/products/docker-toolbox


������ �� Windows:
����� � ������ docker-compose.yml ������ ���������� ������ ���������� ������������ (��������, C:\Users\vasya\dockerexample), ������ ��� ����� volumes � docker �� ����� ��������.

������� ������� �����
������� � ����������
cd /c/Users/vasya/dockerexample
���������
/bin/sh build.sh

docker-compose up -d

��� ������� � ��������
� ������� �������
docker-machine ip
�������� IP
� � ����� IP ���������� ���� 9000, ��������:
http://192.168.99.100:9000/

�������� ��������
������� � ��������� � php: 
docker exec -it ex7-php-fpm /bin/bash

������� � ���������� � ��������
cd /var/www/ex7/web

composer install

����������� symfony:
composer create-project symfony/framework-standard-edition my_project_name

Some parameters are missing. Please provide them.
database_host (127.0.0.1): ex7-postgres
database_port (null): 5432
database_name (symfony): dbname
database_user (root): root
database_password (null): root
mailer_transport (smtp):
mailer_host (127.0.0.1):
mailer_user (null):
mailer_password (null):
secret (ThisTokenIsNotSoSecretChangeIt): lkjsdfklsdjal;sdfdl^[[D^H^H

