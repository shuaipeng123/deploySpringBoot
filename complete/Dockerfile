FROM ibmjava:8-sfj
LABEL maintainer="IBM Java Engineering at IBM Cloud"

COPY target/gs-rest-service-0.1.0.jar /app.jar

ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar" ]
