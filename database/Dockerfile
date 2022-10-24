FROM postgis/postgis:13-3.3

LABEL maintainer="steliomo@gmail.com"

ADD localtime /etc/localtime
ADD postgresql.conf /var/lib/postgresql/data/postgresql.conf

VOLUME /var/lib/postgresql/data

EXPOSE 5432