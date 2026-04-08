# Stack et choix techniques

## 1. Stack cible

- **Frontend** : Next.js
- **Backend** : NestJS
- **Base de données** : PostgreSQL
- **ORM** : Prisma
- **Déploiement** : Docker
- **Architecture** : hexagonale / ports & adapters côté backend

---

## 2. Pourquoi cette stack semble cohérente

### Next.js

- adapté à la génération de sites et aux enjeux SEO
- bon candidat pour gérer le rendu des sites vitrines
- bonne base pour une interface admin légère si besoin

### NestJS

- cohérent avec une volonté de structuration backend forte
- adapté à une logique métier claire et extensible
- bon support pour une architecture par cas d’usage et par modules métier

### PostgreSQL + Prisma

- stack robuste et productive pour un MVP
- bonne lisibilité du schéma et des relations
- compatible avec une évolution progressive

### Docker

- cohérent pour standardiser les environnements
- utile pour garder une base de déploiement propre dès le départ

---

## 3. Point d’attention

Le choix technique doit rester au service du MVP.

Le projet ne doit pas chercher à démontrer toute sa sophistication technique trop tôt au détriment de :

- la rapidité de livraison
- la lisibilité produit
- la soutenabilité opérationnelle
