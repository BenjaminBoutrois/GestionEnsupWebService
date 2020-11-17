# jpaGestionEnsup

Webservice Restful contenant le dao du projet GestionEnsup

## Prérequis

- JDK 8
- Maven 3.6.3
- Apache Tomcat 9 configuré sur le port 8080

## Installation

1. Cloner le dépôt
2. A la racine du projet, ouvrir un invite de commande et taper l'instruction `mvn clean package` pour compiler le projet
3. Une fois compilé, copier le fichier `gestionWebService\web\target\gestionWebService-0.0.1-SNAPSHOT.war` dans le dossier **webapps** du serveur Tomcat
4. Lancer le serveur Tomcat pour déployer le projet sur le serveur
5. Ouvrir un navigateur et entrer `http://127.0.0.1:8080/gestionWebService-0.0.1-SNAPSHOT` dans la barre d'URL pour accéder à l'application