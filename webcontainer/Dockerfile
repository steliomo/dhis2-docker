FROM tomcat:8-jre8-alpine

ADD setenv.sh /usr/local/tomcat/bin/setenv.sh
ADD localtime /etc/localtime
ADD dhis.conf /home/dhis/config/dhis.conf
ADD server.xml /usr/local/tomcat/conf/server.xml 

VOLUME /opt/dhis/data