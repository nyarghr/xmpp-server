FROM mysql:8.0.20

ADD ./schema.sql /docker-entrypoint-initdb.d/schema.sql
COPY ./ejabberd.cnf /etc/mysql/conf.d/ejabberd.cnf
