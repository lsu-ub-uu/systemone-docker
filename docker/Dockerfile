ARG CORA_DOCKER_VERSION
FROM cora-docker-tomcat:${CORA_DOCKER_VERSION}

COPY /systemone*.war /usr/local/tomcat/webapps/systemone.war
COPY /systemone.xml /usr/local/tomcat/conf/Catalina/localhost/systemone.xml 