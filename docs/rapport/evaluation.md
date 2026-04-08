# Évaluation & Tests

## Tests

Afin de s'assurer du bon fonctionnement du backend du projet, un certain nombre de tests on été mis en place.
Cela a été réalisé avec la dépendance JUnit ainsi que la librairie Mockito.

Mockito nous permet de simuler des objets, des services ou stockage et de les tester.


Les services du projet sont directements dépendants de mon développement (contrairement à, par exemple, les repositories
qui se reposent sur un framework puissant).
Les endpoints peuvent aussi être testés, en utilisant par exemple Mockito et MVC afin de simuler les interactions avec
des db ou avec les endpoints.
Les tests nous permettent de s'assurer que le code fonctionne correctement, en signalant des erreurs lors du build si
notre code ne suit pas le comportement souhaité.

## Retours

Lors d'une réunion de travail sur le départ imminent de mes trois collègues au Guatemala, j'ai pu prendre leurs retours
sur l'
application web.

Voici les différents sujets qui ont été abordés comme devant être modifiés :

- Il faudrait expliciter l'utilisation de l'application \[ Fenêtre modale, onboarding, etc \]
- Ajouter le système de templates pour les storyboards, éventuellement sous un format similaire
  à [Totem Field Storyboards](https://totemfieldstoryboards.org).
- Ajouter un système de tags pour la recherche de templates et de storyboards, qui permettront de déterminer le type de
  projet et de filtrer les recherches.
- Un bouton "Enregistrer" sur l'image comme le bouton "Play" serait pratique.
- Eventuellement refaire une autre vague de refonte front pour décharger le visuel et éviter les scroll-down trop longs.
- Repenser le concept de débats/discussions, car ce dernier peut s'avérer, je cite, "dangereux" pour les langues
  sous-documentées.
- Pourvoir visualiser les storyboards comme des BD, où on doit pouvoir "tourner" la page. Actuellement, niveau audio par
  exemple, on ne peut faire next qu'au niveau des audios individuels et non au niveau des vignettes.
- Pouvoir changer la langue de l'application pour être plus inclusive.

Globalement, les retours sont positifs. De fait, on m'a même demandé s'il était possible d'intégrer des fetchs de
données depuis l'API Vignettes vers une application de recherche que je développe présentement pour eux.

De façon plus complexe, une requête a également été de pouvoir upload des vidéos en plus des images.
Toutefois, un tel système s'avèrera complexe, surtout pour ce qui est gestion parallèle d'audios, de marquage, etc.
Cette option s'envisagera à une étape ultérieure du projet, quand ce dernier sera plus complet.