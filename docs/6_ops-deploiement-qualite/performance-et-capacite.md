# Performance et capacité

## 1. Objectif
Évaluer la capacité probable du système à héberger et servir plusieurs sites vitrines sans dégradation majeure.

## 2. Hypothèses d’usage
- nombre de sites hébergés
- trafic moyen par site
- pics simultanés
- poids moyen des pages et médias
- fréquence de génération / régénération

## 3. Variables techniques critiques
- rendu statique / SSR / ISR
- mutualisation du frontend
- stratégie CDN
- stockage des médias
- architecture base de données
- isolation par tenant

## 4. Premiers seuils à estimer
- 10 sites
- 50 sites
- 100 sites
- 500 sites
- 1 000 sites

## 5. Métriques à suivre
- temps de réponse
- temps de build / génération
- usage CPU / RAM
- charge DB
- bande passante
- taux d’erreur

## 6. Risques
- trop de logique dynamique
- médias trop lourds
- génération trop coûteuse
- admin couplé au runtime public
- gestion domaine / SSL qui devient lourde

## 7. Stratégie MVP recommandée
- viser simplicité et robustesse avant scalabilité avancée
- choisir une architecture qui tient facilement les premiers paliers
- mesurer avant d’optimiser