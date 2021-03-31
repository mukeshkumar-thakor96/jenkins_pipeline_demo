FROM tomcat:latest
MAINTAINER Mukesh Thakor

ADD wildfly-spring-boot-sample-1.0.0.war /usr/local/tomcat/webapps/

# Expose the ports we're interested in
EXPOSE 8082

# Set the default command to run on boot
# This will boot WildFly in the standalone mode and bind to all interface
CMD [“catalina.sh”, “run”]
