FROM java:8
VOLUME /tmp

EXPOSE 8090

add docker-helloworld-0.0.1-SNAPSHOT.jar app.jar

RUN sh -c 'touch /app.jar'
#ENV JAVA_OPTS=""
#ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar" ]
ENTRYPOINT ["java", "-jar","/app.jar"]
