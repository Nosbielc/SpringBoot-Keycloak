# SpringBoot-Keycloak
Securing Spring Boot APIs with Keycloak

# Docker Keycloak Server
````
 docker pull jboss/keycloak:10.0.1

 docker run -p 8181:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin jboss/keycloak:10.0.1
