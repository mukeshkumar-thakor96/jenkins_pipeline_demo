FROM tomcat:8.0-alpine
MAINTAINER Mukesh Thakor

COPY wildfly-spring-boot-sample-1.0.0.war /usr/local/tomcat/webapps/

# Expose the ports we're interested in
EXPOSE 8081

# Set the default command to run on boot
# This will boot WildFly in the standalone mode and bind to all interface
CMD [“catalina.bat”, “run”]
