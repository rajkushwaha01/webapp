FROM tomcat:8.0.20-jre8 
COPY ./target/*.war /usr/local/tomcat/webapps/myweb.war
COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
EXPOSE 8080
