---
title: Suivi du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Suivi de projet

[//]: # (> :bulb: Cette page documente l’évolution du projet dans le temps.)

[//]: # (> Elle sert à rendre visibles les décisions, ajustements et apprentissages.)

[//]: # (> Les entrées peuvent être hebdomadaires ou bi-hebdomadaires.  )

[//]: # (> N'oubliez pas d’effacer ou de mettre en commentaires les notes &#40;`>`&#41; avant la remise finale.)

---

## Mois de Janvier

### Objectifs de la période

- Clarifier la problématique
- Explorer les solutions et travaux existantes
- Clarifier les objectifs du projet et la solution envisagée

### Travail réalisé

!!! abstract "Avancement"

- [x] Analyse des travaux existantes
- [x] Analyse des besoins que le projet pourrait combler

## Mois de Février

### Objectifs de la période

- Développer le squelette, peu susceptible de changer par la suite
- Planifier la gestion des audios
- Développer une interface minimaliste et fonctionnelle

### Travail réalisé

!!! abstract "Avancements"

- [x] Structure de BDD
- [x] Squelette du Backend Java
- [X] Interface minimaliste
- [X] Squelette de gestion des audios

### Décisions et ajustements

[//]: # (> À compléter uniquement si des choix structurants ont été faits)

[//]: # (> ou si l’orientation du projet a évolué.)

[//]: # ()
!!! info "Décisions"

    - Abandon de l'approche MVC ou le serveur web est aussi géré par Java dans le même module

    - On remplace par une API REST + un front "pure web"

### Difficultés rencontrées

!!! warning "Difficultés"

    - Peu d'expérience avec REST -> nécessité d'apprendre
    
    - Aucune expérience d'utilisation exclusive de JS pour une gestion web

[//]: # (    - Problème de configuration du plugin Mermaid)

[//]: # (        - Confusion entre `mkdocs-mermaid2-plugin` &#40;pip&#41;)

[//]: # (          et `mermaid2` &#40;nom du plugin&#41;)

[//]: # (        - Résolu après nettoyage et configuration correcte dans `mkdocs.yml`)

## Mois de Mars

### Objectifs de la période

- Rendre le front end plus propre
- Ajout des marqueurs sur les images
- améliorer l'UX
- Créer une doc API

### Travail réalisé

!!! abstract "Avancements"

- [X] Squelette front en Vue
- [X] Marqueurs sur les vignettes, qui s'allument quand l'audio en question est en train de jouer
- [X] Refonte css pour un meilleur visuel
- [X] Refonte de certaines pages pour une meilleure navigation, visualisation et UX
- [X] Création d'une doc API pour répertorier les endpoints, faite avec Swagger et OpenApi, publier sur github pages.
- [X] Préparation de la mise en production avec :
    - passage de fichiers stockés en DB à fichiers stockées localement avec méta infos en DB
    - propriétés d'applications différentes pour prod et dev, avec possibilité d'utiliser une DB externe comme Supabase
      en prod.

### Décisions et ajustements

!!! info "Décisions"

    - Abandon de l'approche html + css + js, pour une approche vue qui est plus propre, prise en charge par un framework puissant. Cette approche nous évite de répéter des structures html et permet une approche web dynamique.
    - Le squelette du front a été passé en Vue.js. Cela permet d'éviter de répéter les structures html, de générer les templates, de générer le contenu html dynamiquement.

### Difficultés rencontrées

!!! warning "Difficultés"

    - Aucune Expérience avec Vue.js
    - Capacités faibles en design, ce qui rend compliqué la tâche de faire du CSS

## Mois d'Avril

### Objectifs de la période

- Faire tester l'application web auprès de collègues linguistes.
- Faire une première mise en production pour une éventuelle utilisation lors d'un séjour au Guatemala par mes collègues.
- Faire une interface d'administration minimal.
- Mettre en place un système de discussion avec permissions locales et globales (admins).

### Travail réalisé

!!! abstract "Avancements"

### Décisions et ajustements

!!! info "Décisions"

### Difficultés rencontrées

!!! warning "Difficultés"