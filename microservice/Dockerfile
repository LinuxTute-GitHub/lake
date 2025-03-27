# Use an official Tomcat image as the base image
FROM tomcat:9.0-jdk11-openjdk

# Copy the WAR file into the Tomcat webapps directory
COPY myapp.war /usr/local/tomcat/webapps/

# Expose the port Tomcat runs on (default 8080)
EXPOSE 8080

# Run Tomcat when the container starts
CMD ["catalina.sh", "run"]

