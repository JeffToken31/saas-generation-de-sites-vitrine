# Modèle métier

## 1. Rôle du document

Ce document a vocation à formaliser les entités principales du produit et leurs relations logiques.

À ce stade, il s’agit encore d’un pré-cadrage métier, pas d’un modèle de données final.

---

## 2. Entités principales pressenties

### Client

Porteur de l’activité artisanale ou représentant de la structure cliente.

### Projet

Objet central du système.

Représente une demande de présence en ligne en cours de construction, de validation ou de publication.

### Données métier / contenu

Informations servant à générer le site :

- identité de l’activité
- métier
- zone d’intervention
- description
- services
- arguments de confiance
- visuels
- coordonnées

### Preview / maquette

Version préliminaire du site utilisée pour montrer un résultat avant validation.

### Site publié

Version finale mise en ligne et accessible publiquement.

### Domaine

Nom de domaine associé au site, qu’il soit inclus, géré ou délégué.

### Abonnement

Composant récurrent lié à l’hébergement, la maintenance simple et au maintien du service.

### Statut

État d’avancement du projet.

États pressentis :

- draft
- pending validation
- validated
- published
- paused
- archived

### Demande de modification

Élément permettant de tracer les ajustements demandés avant ou après publication.

### Contact / lead entrant

Message reçu depuis le formulaire du site publié.

---

## 3. Questions à clarifier ensuite

- différence exacte entre projet, preview et site publié
- statut exact avant paiement et après paiement
- niveau de découplage entre contenu, design et publication
- gestion d’un domaine avant validation
- place éventuelle d’un abonnement avant la publication
- nombre et statut des demandes de modification

---

## 4. Prochaine étape recommandée

Dans une prochaine version, préciser :

- relations entre entités
- cycle de vie détaillé du projet
- règles métier associées à chaque statut
- événements métier importants
