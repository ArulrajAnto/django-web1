ENV setup

yum install centos-release-scl
yum install rh-python36
scl enable rh-python36 bash
python --version


Ref Doc

https://tutorial.djangogirls.org/en/


mkdir djangogirls
cd djangogirls/
virtualenv --python=python3.6 myvenv
source myvenv/bin/activate



django-admin startproject mysite .



python -m pip install --upgrade pip
pip install mysqlclient
pip install mysql-connector-python
pip install Django~=2.0.6


vim mysite/settings.py

ALLOWED_HOSTS = ['52.77.251.182']

python manage.py runserver 0.0.0.0:8000
