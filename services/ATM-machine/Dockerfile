FROM eclipse-temurin:17-jre
EXPOSE 8080
RUN mkdir /app
COPY ./ATM.jar /app/ATM.jar
ENTRYPOINT ["java","-jar", "/app/ATM.jar", "-Xmx4G", "-Xms256M"]
