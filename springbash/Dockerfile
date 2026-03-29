# Image Java 17
FROM eclipse-temurin:17-jdk-jammy

# Répertoire de travail
WORKDIR /opt/app

# Copier le fichier jar
COPY target/springdocker-0.0.1-SNAPSHOT.jar app.jar

# Port utilisé par Spring Boot
EXPOSE 8080

# Lancement de l'application
CMD ["java", "-jar", "app.jar"]