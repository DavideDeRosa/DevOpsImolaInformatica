FROM eclipse-temurin:17
RUN mkdir -p /opt/conf
COPY imolasportiva.jar /opt/app/imolasportiva.jar
COPY application.properties /opt/conf/application.properties
EXPOSE 8080
CMD ["java", "-Dopenjdk.app.properties.dir=/opt/conf", "-jar", "/opt/app/imolasportiva.jar"]