FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD=jc31d2qyy7h9jv5jn1u9uosjksxzaizw
ENV MYSQL_DATABASE=dd

ADD ./docker/mysql/init.sql /docker-entrypoint-initdb.d

RUN chown -R mysql:mysql /docker-entrypoint-initdb.d/
