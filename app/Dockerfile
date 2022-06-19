FROM tomcat:8-jre11
RUN rm -rf /usr/local/tomcatwebapps/*
COPY target/vprofile-v2.war /usr/local/tomcatwebapps/ROOT.war


EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat
VOLUME /usr/local/tomcat/webapps