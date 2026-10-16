# Java 17 runtime
FROM eclipse-temurin:17-jre

# Port de l'application
EXPOSE 2222

# Dossier de travail
WORKDIR /app

# Copier le fichier JAR
COPY target/devOpsDemo-0.0.1-SNAPSHOT.jar app.jar

# Lancer l'application
CMD ["java", "-jar", "app.jar"]
