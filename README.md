# version

# Ubuntu 20.04.5 LTS

# Python 3.8.10
```sh
> python3 -V
Python 3.8.10

> which python3
/usr/bin/python3

> ls /usr/bin/ | grep python
python3
python3-futurize
python3-pasteurize
python3.8
```

# Mysql 8.0.31
password : vitasoft1234
https://dev.mysql.com/downloads/mysql/
파일설치 
```sh
sudo apt-get update
sudo apt-get install mysql-server
sudo systemctl start mysql

# mysql 접속
mysql -u root

# 비밀번호와 함께 mysql에 접속하는 명령어
# -u(계정 접근), -p(비밀번호)
mysql -u root -p

sudo mysql -u root -p

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '비밀번호입력';
```
```sh
# 디비접속
sudo mysql -u root -p;
>vitasoft1234
```



# php 7.4
```sh
sudo apt update
sudo apt-get install php

#/var/www/html/info.php 파일을 생성해줍니다.

cd /var/www/html/
sudo touch info.php
sudo vi info.php
```
info.php
```php
<?php phpinfo(); ?> 

:wq
```
# Anaconda
```sh
$ sudo gedit ~/.bashrc
export PATH=~/anaconda3/bin:~/anaconda3/condabin:$PATH
$ source ~/.bashrc

# (base) 안보이게 하는거
# conda config --set auto_activate_base False

conda init
conda activate 
```


# conda + Django 4.0.4
```sh
conda create -n Django_env
pip install Django

cd 바탕화면/
django-admin --version
django-admin startproject web
cd web/
python3 manage.py migrate
python3 manage.py createsuperuser
nano web/settings.py

```

