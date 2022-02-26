FROM openjdk:17.0.2-jdk-oracle
VOLUME /tmp
EXPOSE 9091
COPY bank-balance-0.0.1-SNAPSHOT.jar /bank-balance-0.0.1-SNAPSHOT.jar
ENTRYPOINT [ "java","-jar","bank-balance-0.0.1-SNAPSHOT.jar" ]
