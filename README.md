# remote_mysql

GRANT ALL ON *.* TO root@'%' IDENTIFIED BY 'shopdev123';
GRANT ALL PRIVILEGES ON * . * TO  'root'@'%' IDENTIFIED BY  'shopdev123' WITH GRANT OPTION MAX_QUERIES_PER_HOUR 0 MAX_CONNECTIONS_PER_HOUR 0 MAX_UPDATES_PER_HOUR 0 MAX_USER_CONNECTIONS 0 ;


[mysqld]
user            = mysql
pid-file        = /var/run/mysqld/mysqld.pid
socket          = /var/run/mysqld/mysqld.sock
port            = 3306
basedir         = /usr
datadir         = /var/lib/mysql
tmpdir          = /tmp
language        = /usr/share/mysql/english
bind-address    = 35.238.25.53 
