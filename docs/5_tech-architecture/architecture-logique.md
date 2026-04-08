# Architecture logique

## 1. Rôle du document

Ce document doit décrire la logique générale du système sans entrer trop tôt dans les détails d’implémentation.

---

## 2. Blocs fonctionnels pressentis

- collecte des informations artisan
- gestion des projets
- moteur de génération / composition de site
- gestion des previews
- gestion de validation
- publication
- gestion domaine / hébergement
- interface d’administration minimale
- gestion du cycle de vie et des statuts

---

## 3. Questions à traiter ensuite

- séparation exacte entre génération, preview et publication
- niveau de multi-tenant nécessaire en V1
- frontière entre logique métier et logique de rendu
- responsabilités exactes de l’admin minimal
