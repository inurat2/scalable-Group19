FROM openjdk:11.0.2-jre-slim
COPY target/catalog-0.0.1-SNAPSHOT.jar .
CMD /usr/bin/java -Xmx400m -Xms400m -jar catalog-0.0.1-SNAPSHOT.jar
EXPOSE 8080
