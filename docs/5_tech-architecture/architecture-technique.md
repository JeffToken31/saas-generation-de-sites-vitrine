# Architecture technique

## 1. Rôle du document

Ce document devra décrire les choix techniques concrets permettant de construire le MVP de manière propre et évolutive.

---

## 2. Cible actuelle

- backend : NestJS
- frontend : Next.js
- base de données : PostgreSQL
- ORM : Prisma
- déploiement : Docker
- architecture : séparation claire domaine / application / infrastructure

---

## 3. Principes directeurs

- simplicité du MVP avant sophistication
- architecture propre mais pragmatique
- séparation des responsabilités
- extensibilité maîtrisée
- éviter la sur-architecture

---

## 4. Questions à préciser ensuite

- mono-repo ou séparation front / back
- stratégie de preview
- stratégie de publication multi-sites
- gestion des domaines
- observabilité minimale nécessaire en V1
