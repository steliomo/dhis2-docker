FROM tomcat:8.5.83-jdk11-corretto-al2

ADD setenv.sh /usr/local/tomcat/bin/setenv.sh
ADD localtime /etc/localtime
ADD dhis.conf /home/dhis/config/dhis.conf
ADD server.xml /usr/local/tomcat/conf/server.xml 

VOLUME /opt/dhis/data