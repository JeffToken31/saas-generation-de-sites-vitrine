# README PROJET — SaaS génération de sites pour artisans

## 1. Rôle de ce document

Ce document est le point d’entrée principal de la documentation projet.

Il sert à :

- centraliser la structure documentaire
- clarifier l’état d’avancement du projet
- éviter les doublons et les réflexions dispersées
- distinguer ce qui est déjà décidé, ce qui reste à trancher et ce qui est encore à explorer
- donner un ordre logique de lecture et de travail

Ce README n’a pas pour rôle de détailler tout le projet.

Il sert avant tout de **colonne vertébrale documentaire**.

---

## 2. Rappel synthétique du projet

Le projet vise à concevoir un produit SaaS permettant de générer rapidement des sites vitrines pour artisans, avec un parcours simple, guidé et accessible.

### Objectif business

Proposer une solution simple et crédible à des artisans locaux ayant peu ou pas de présence en ligne, avec un modèle économique viable reposant sur une mise en place cadrée et un abonnement.

### Objectif produit / technique

Construire un produit propre, structuré et évolutif, reposant sur une architecture solide, capable de démarrer comme MVP pragmatique puis d’évoluer vers un SaaS plus complet.

---

## 3. État actuel du projet

À ce stade :

- l’opportunité marché a déjà été partiellement documentée
- la cible et le problème principal sont globalement identifiés
- une première vision produit existe
- un premier périmètre MVP a été esquissé
- plusieurs hypothèses de pricing et de monétisation ont été étudiées
- plusieurs décisions restent encore ouvertes
- la structure documentaire a été refondue pour clarifier le projet

Le projet est encore en phase de **cadrage produit et stratégique**.

Il n’est pas encore dans une phase de spécification technique exhaustive.

---

## 4. Principes de structuration documentaire

La documentation est organisée selon un principe simple :

- un dossier = un angle de réflexion principal
- un document = une question principale
- éviter qu’un même sujet soit traité à plusieurs endroits sans raison
- distinguer clairement :
  - la vision
  - le MVP
  - l’offre
  - le business model
  - le modèle métier
  - l’architecture technique
  - les hypothèses à valider

---

## 5. Architecture documentaire

```text
/documentation
  README_PROJET.md

  /01_vision-strategie
    vision-produit.md
    probleme-cible-marche.md
    positionnement-promesse-valeur.md
    positionnement-entreprise.md

  /02_offre-mvp
    mvp-perimetre.md
    offre-mvp.md
    decisions-ouvertes-mvp.md

  /03_business-model
    pricing-et-concurrence.md
    hypotheses-economiques.md
    modele-de-commercialisation.md

  /04_produit-metier
    modele-metier.md
    parcours-utilisateur.md
    regles-de-gestion.md

  /05_tech-architecture
    architecture-logique.md
    architecture-technique.md
    stack-et-choix-techniques.md

  /06_validation-roadmap
    hypotheses-a-tester.md
    questions-ouvertes.md
    roadmap.md
    journal-decisions.md
---

## 6. Rôle des dossiers

### 01_vision-strategie

Ce dossier contient les fondations du projet :

pourquoi le projet existe
pour qui il existe
quel problème il cherche à résoudre
quelle promesse il porte
comment le projet doit être perçu sur le marché
quel positionnement adopter, à la fois produit et entreprise

### 02_offre-mvp

Ce dossier cadre la première offre réellement testable :

ce que le MVP inclut
ce qu’il exclut
ce qui est volontairement reporté
ce que l’offre promet concrètement
ce qui reste à arbitrer avant figer le périmètre

### 03_business-model

Ce dossier traite de la soutenabilité économique du projet :

étude de prix
repères de concurrence
scénarios de monétisation
logique d’acquisition et de commercialisation
hypothèses de rentabilité et de support

### 04_produit-metier

Ce dossier formalise le projet comme système métier :

entités
parcours utilisateur
statuts
cycle de vie d’un projet
règles de gestion
logique opérationnelle du service

### 05_tech-architecture

Ce dossier contient les choix de structuration technique :

architecture logique
architecture applicative
stack
contraintes non fonctionnelles
principes de construction du MVP

### 06_validation-roadmap

Ce dossier sert au pilotage du cadrage :

hypothèses à tester
questions ouvertes
feuille de route
journal des décisions

---

## 7. Ordre conseillé de lecture et de travail

Pour éviter de réfléchir dans le désordre, l’ordre conseillé est :

vision produit
problème, cible et marché
positionnement produit
positionnement entreprise
périmètre MVP
offre MVP
pricing, concurrence et commercialisation
modèle métier
architecture logique
architecture technique
hypothèses à tester
roadmap

## 8. Décisions déjà relativement actées

À ce stade, les éléments suivants semblent relativement stabilisés :

la cible principale est celle des artisans locaux
le besoin principal concerne la visibilité, la crédibilité et la simplicité
la promesse centrale n’est pas de vendre de la technique, mais une présence en ligne simple et rassurante
le MVP doit rester volontairement limité
la logique produit doit être plus proche d’un service cadré que d’un développement sur mesure
la mise en confiance avant paiement semble être un levier fort
le projet doit éviter la sur-complexification trop tôt

## 9. Principaux sujets encore ouverts

Les sujets suivants restent à cadrer plus précisément :

le positionnement exact de la structure : freelance, studio, structure spécialisée, solution opérée, autre
le niveau réel d’accompagnement humain
le périmètre exact de l’offre MVP
la place éventuelle d’un module de devis
la stratégie domaine / hébergement
le moment exact du paiement
le niveau de personnalisation du site
le nombre d’allers-retours inclus
la stratégie d’acquisition initiale
le niveau de support acceptable
les hypothèses économiques réalistes
la modélisation métier détaillée

## 10. Règle de travail pour la suite

Avant de créer un nouveau document ou d’ajouter une nouvelle réflexion, vérifier systématiquement :

est-ce que ce sujet existe déjà quelque part ?
à quel dossier appartient-il réellement ?
parle-t-on de vision, de produit, d’offre, de business ou de technique ?
s’agit-il d’une décision, d’une hypothèse ou d’une question ouverte ?
faut-il créer un document ou simplement enrichir un document déjà existant ?

## 11. Prochaine étape recommandée

La prochaine étape consiste à :

consolider le dossier 01_vision-strategie
clarifier le positionnement de l’entreprise
redistribuer proprement les documents déjà rédigés dans la nouvelle structure
transformer les contenus redondants en documents plus spécialisés
préparer ensuite le dossier 04_produit-metier, qui deviendra central pour la suite du projet