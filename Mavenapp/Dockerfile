FROM adoptopenjdk:11-jre-hotspot
WORKDIR /Mavenapp
COPY target/Mavenapp.jar ./
EXPOSE 8080
CMD ["java", "-jar", "Mavenapp.jar"]
