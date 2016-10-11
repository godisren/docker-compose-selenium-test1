FROM mariadb

ENV MYSQL_ROOT_PASSWORD hyweb

#ADD files/db.sql /usr/local/db.sql
#直接將初始化script放到/docker-entrypoint-initdb.d路徑下，即會初始化DB
ADD files/db.sql /docker-entrypoint-initdb.d/schema.sql


