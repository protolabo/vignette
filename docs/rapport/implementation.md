# Implementation

Dans un premier lieu, veuillez trouver [ici](https://github.com/Titiplex/vignette) le lien du dépôt Github du projet.

Pour la documentation de l'API, veuillez trouver [ici](https://titiplex.github.io/vignette/) le lien de la
documentation.

## Backend

Le backend a été réalisé en Java.
La raison de ce choix est mon affinité avec ce language.
Les dépendances / frameworks utilisés sont :

- Spring Boot
- Spring Data JPA
- Lombok

## Frontend

Le frontend était originellement fait en fxml (avec thymeleaf), mais a ensuite été passé en Vue.js.
Vue.js permet de faire des applications web plus structurées, dynamiques et performantes.
Le front étant dissocié du back, il doit interagir avec le back via une API.
Cette interaction est faite via REST; puisque en JavaScript il est aisé de fetch REST et de récupérer des JSON.