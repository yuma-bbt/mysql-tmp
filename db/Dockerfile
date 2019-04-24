FROM mysql:5.7
COPY ./mysql.conf.d /etc/mysql/mysql.conf.d

COPY init/* /docker-entrypoint-initdb.d/

CMD ["mysqld"]

