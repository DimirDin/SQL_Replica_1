FROM mysql:8.0
COPY slave.cnf /etc/mysql/conf.d/my.cnf
COPY slave.sql /docker-entrypoint-initdb.d/
