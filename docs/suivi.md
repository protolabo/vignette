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
- [_] Interface minimaliste
- [_] Squelette de gestion des audios

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
