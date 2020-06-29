FROM tomcat:8.5.56-jdk8-openjdk



ADD ./docker/app/App-test.war /usr/local/tomcat/webapps/App-test.war

EXPOSE 8080

#CMD ["sh", "/srv/tomcat/bin/catalina.sh", "run" ]

ADD ./docker/app/Config.properties /usr/local/tomcat/ROOT/Config.properties
