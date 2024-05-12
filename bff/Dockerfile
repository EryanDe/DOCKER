# Utilisation de l'image Docker Java 21 (JDK)
FROM mdsol/java21-jdk

# Création du répertoire /app dans le conteneur
WORKDIR /app

#comment 


# Copie des fichiers du répertoire bff/target dans le conteneur
COPY ./target/* /app/


# Commande pour démarrer votre application Java
CMD ["java", "-jar", "/app/bff-0.0.1-SNAPSHOT.jar"]