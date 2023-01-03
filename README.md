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
# Mysql 8.0

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



# php
```sh
sudo apt update
sudo apt-get install php


sudo apt install phpmyadmin


```
