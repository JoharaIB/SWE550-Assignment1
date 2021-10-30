FROM mysql
MAINTAINER root@root.com

ENV MYSQL_ROOT_PASSWORD root
ADD employee.sql /docker-entrypoint-initdb.d

EXPOSE 3306