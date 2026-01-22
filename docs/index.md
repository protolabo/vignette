---
title: Vue d'ensemble du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Vue d'ensemble du projet

!!! info "Informations générales"
**Session**: Hiver 2026  
**Auteur(s)**: Titouan Johanny    
**Thème(s)**: Langue, HCI, Développement web, Génie logiciel  
**Superviseur(s)**: Louis-Edouard Lafontant  
**Collaborateur(s):** <!-- Nom de(s) collaborateur(s) et partenaire(s)` -->

## Description du projet

[//]: # (> :bulb: N'oubliez pas d'effacer ou mettre en commentaires les notes &#40;`>`&#41; en début de section)
Creation d'un site web permettant de créer des scenarios à partir de vignettes et d'enregistrer les conversations audios
correspondantes.

### Contexte

[//]: # (> Présentez le contexte général dans lequel s’inscrit votre projet &#40;social, organisationnel, technologique, éducatif, environnemental, etc.&#41;.)
Actuellement, les langues écrites et utilisées dans la vie publique ne représente qu'une infime minorité des langues
parlées, qui se comptent en milliers.
Un pays ne possède qu'une à trois langue officielle la plupart du temps, ce qui ne nous donne que moins de 500 langues
potentiellement protégées.
Ces langues sont issues la plupart du temps d'une tradition écrite, politique voire nationale ou d'auxiliaire de
communication (français, anglais, russe, mandarin, etc).
Les autres langues ne sont ainsi pas protégées et pour beaucoup en danger dû au manque d'écriture/littérature, leur
emploi dans un contexte uniquement familier et, parfois, une répression sociale ou étatique.

### Problématique

[//]: # (> Décrivez le problème central ou la question de recherche que votre projet cherche à adresser, pourquoi s'y intéresser et les faiblesses des solutions actuelles. )

[//]: # (> Le problème doit pouvoir être compris indépendamment de la solution envisagée.)

Un problème survient souvent. Les langues sous-dotées, sous-représentées et en danger sont très souvent :

- à tradition orale uniquement ou principalement
- parlées par des individus peu ou pas éduqués scolairement dans lesdites langues (il est donc difficile d'écrire d'
  autant plus que ce contexte est souvent très littéraire)
- sont parlées par des communautés restreintes (Maasais, Pirahã, Iakoutes, etc)

Il est alors difficile de récupérer des données (pour la recherche où pour bâtir un environnement de vie dans lesdites
langues), d'étudier ces langues et encore plus de les préserver.

De plus, lorsqu'on cherche à obtenir des données en faisant des traductions, nous sommes exposés à deux biais
importants:

- celui d'impliquer des caractéristiques culturelles qui n'appartiennent pas aux locuteurs concernés (ex. les Pirahã
  n'ont aucun concept de Dieu et étaient donc perplexes quand Everett leur demandait comment appeler cela)
- celui de ne pas favoriser un contexte naturel qui permet d'avoir une performance spontanée et linguistiquement
  pertinente.

### Proposition et objectifs

[//]: # (> Présentez votre proposition de projet et les objectifs visés. Expliquez en quoi votre approche répond à la problématique identifiée. )

[//]: # (> Assurez-vous d'avoir, dans la mesure du possible, des objectifs mesurables, raisonnnables dans le temps et non redondants entre eux.)
Ce projet s'inscrit ainsi dans une volonté de conservation et développement des langues sous-dotées, peu représentées ou
à tradition principalement orale.

Nous cherchons donc à donner accès à une technologie permettant aux locuteurs d'archiver, conserver leur langue et,
éventuellement, de s'en servir dans un contexte éducatif pour enseigner.
Egalement, à long terme ce site web pourrait disposer d'une base de données assez importante, permettant ainsi plus
facilement la recherche et description des langues concernées, et ce sans contrainte de déplacement (aller sur le
terrain) ou de question orthographiques auprès des locuteurs, tout en restant naturel.

Ce projet propose ainsi un site web, accessible au plus grand nombre sans contrainte de téléchargement, peu ou prou de
contrainte de hardware.
Ce site permettra de créer des scenarios, décrits par des vignettes (petites images représentatives, au nombre de 1 à
6).
Le scénario et les vignettes pourront ensuite être associés avec des enregistrements audio.
Ainsi, il sera évité de faire des traductions implicites ou explicites lorsqu'on enregistre des audios en langue native,
évitant les biais.
De plus, ce type d'outil permet une centralisation des données, permettant de partager les scénarios et les idées au
plus grand nombre, utiliser un outil d'éducation, etc.

### Méthodologie

[//]: # (> Expliquez comment vous comptez aborder le projet : démarche générale, grandes étapes prévues, itérations, types de validations envisagées.)
Dans un premier temps, nous allons étudier les solutions existantes ou travaux existants sur le sujet.
Puis, nous allons bâtir le squelette du projet, le backend et la base de données.
Ensuite, nous allons étudier et rajouter des features supplémentaires, éventuellement.
Suivra le développement du frontend, à la fois pour avoir un site agréable mais aussi intuitif et avec des
fonctionnalités intéressantes et pratiques.
Enfin, nous allons développer l'environnement de tests afin de vérifier le bon fonctionnement de l'application, ainsi
que l'évaluation de sa pertinence.

### Validation et Évaluation

[//]: # (> Indiquez comment vous évaluerez que votre solution répond aux objectifs du projet &#40;ex. scénarios d’usage, tests, retours utilisateurs, indicateurs qualitatifs ou quantitatifs&#41;.)
L'application en elle-même sera évaluée par un environnement de test de qualité logicielle (JUnit, Pytest, etc).

La solution sera évaluée et validée (ou non) par des testeurs. Ils ne seront pas nécessairement locuteurs d'une langue
peu dotée "rare" (il me faut les trouver). En revanche, il est possible de quand même tester l'application en contexte,
par
exemple en français québécois qui n'est pas ou peu écrit.

Je compte également la présenter à mes collègues linguistes, qui pourront éventuellement juger de la pertinence de la
solution grâce à leur expérience du terrain. Ils pourront également proposer des fonctionnalités pratiques quant à
l'utilisation de l'application dans un contexte éducatif ainsi que de recherche et développement.

## Équipe

[//]: # (> Présentez les membres de l’équipe et le rôle principal de chacun dans le projet.)
Titouan Johanny : étudiant en échange international en informatique, passionné de linguistique et travaillant au
département de linguistique sur le Chuj, une langue Maya du Guatemala.

## Échéancier

!!! info
Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Activités              | Début   | Fin     | Livrable               | Statut      |
|------------------------|---------|---------|------------------------|-------------|
| Ouverture de projet    | 12 jan. | 12 jan. | Proposition de projet  | ✅ Terminé   |
| Études préliminaires   | 12 jan. | 23 jan. | Document d'analyse     | 🔄 En cours |
| Présentation + Rapport | 17 avr. | 30 avr. | Présentation + Rapport | ⏳ À venir   |
