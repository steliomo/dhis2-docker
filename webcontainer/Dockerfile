FROM tomcat:8-jre8-alpine

ADD setenv.sh /usr/local/tomcat/bin/setenv.sh
ADD localtime /etc/localtime
ADD dhis.conf /home/dhis/config/dhis.conf

VOLUME /opt/dhis/data