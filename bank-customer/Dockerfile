FROM openjdk:17.0.2-jdk-oracle
VOLUME /tmp
EXPOSE 9092
COPY bank-customer-0.0.1-SNAPSHOT.jar /bank-customer-0.0.1-SNAPSHOT.jar
ENTRYPOINT [ "java","-jar","bank-customer-0.0.1-SNAPSHOT.jar" ]
