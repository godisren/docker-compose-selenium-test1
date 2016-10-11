FROM tomcat:8.0

# 安裝mariadb(-y表示互動皆回覆y)
#RUN apt-get update && apt-get install -y mariadb-client

# mariadb lib
ADD files/mariadb-java-client-1.1.7.jar /usr/local/tomcat/lib/

# db connection config
ADD files/WebTest.xml /usr/local/tomcat/conf/Catalina/localhost/

# deploy war
ADD files/WebTest.war /usr/local/tomcat/webapps/


