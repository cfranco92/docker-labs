FROM openjdk:17.0.2-jdk-oracle
VOLUME /tmp
EXPOSE 9093
COPY bank-users-0.0.1-SNAPSHOT.jar /bank-users-0.0.1-SNAPSHOT.jar
ENTRYPOINT [ "java","-jar","bank-users-0.0.1-SNAPSHOT.jar" ]
