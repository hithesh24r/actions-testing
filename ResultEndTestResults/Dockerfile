FROM tomcat:9.0

RUN apt-get update && \
    apt-get upgrade -y

COPY ./web/ /usr/local/tomcat/webapps/ROOT/

EXPOSE 8080
CMD ["catalina.sh", "run"]
