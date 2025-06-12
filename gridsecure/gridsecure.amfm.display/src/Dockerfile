FROM alpine:3.18

WORKDIR /opt/tibco
RUN mkdir -p /opt/tibco/config

COPY main.sh /opt/tibco/
COPY dev-app-docker.properties /opt/tibco/config/

CMD ["sh", "/opt/tibco/main.sh"]
