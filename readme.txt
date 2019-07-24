# SevOne Installer

## Installation Steps

```
Install python3.6, django=1.11, djangorestframeworks using following commands:

yum install python36
yum install python36-django
yum install python36-setuptools
yum install python36-devel
yum install python2-django

```

## Install ansible 2.8.1 (python3 required)
```
wget https://github.com/ansible/ansible/archive/v2.8.1.tar.gz

tar -xzvf v2.8.1.tar.gz
cd ansible-2.8.1
python3 setup.py install
```

## callback plugins
```
copy HttpClient.py, myriad.py and SevOneCallback.py to /root/ansible/callback_plugins.
```

## Run django project
```
cd sevone_installer
python manage.py runserver IP:PORT
```
