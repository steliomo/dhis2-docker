FROM postgis/postgis:10-3.0

LABEL maintainer="steliomo@gmail.com"

ADD localtime /etc/localtime
ADD postgresql.conf /etc/postgresql/postgresql.conf

VOLUME /opt/dhis/data

EXPOSE 5432