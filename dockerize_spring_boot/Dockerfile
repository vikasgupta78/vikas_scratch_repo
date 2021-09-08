FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} vikas.jar
ENTRYPOINT ["sh", "-c", "java ${JAVA_OPTS} -jar /vikas.jar ${0} ${@}"]