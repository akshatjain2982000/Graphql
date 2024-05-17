FROM openjdk:17-oracle

EXPOSE 8761

ADD target/service-registry-0.0.1-SNAPSHOT.jar service-registry.jar

ENTRYPOINT ["java","-jar","graphql.jar"]
