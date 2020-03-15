# Curso de Mysql

## Instalacion

```bash
sudo yum install -y https://dev.mysql.com/get/mysql80-community-release-el7-3.noarch.rpm
sudo yum install -y mysql-community-server
sudo systemctl start mysqld
#ver clave temporal root
sudo grep 'temporary password' /var/log/mysqld.log
sudo mysql_secure_installation
#ver config en /etc/my.cnf
bind-address=127.0.0.1
```
