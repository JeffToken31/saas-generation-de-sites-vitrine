# Backlog documentaire

## 1. Rôle du document

Ce document sert à garder visibles les sujets importants sans surcharger l’arborescence active avec trop de fichiers vides.

Il permet de :

- ne pas oublier les sujets futurs
- garder une vision complète du produit et du système
- différer proprement certains documents
- savoir quand un sujet devient réellement nécessaire

Ce document est un réservoir de documentation future.

---

## 2. Règle d’utilisation

Un sujet reste dans ce backlog tant qu’au moins une de ces conditions est vraie :

- il n’impacte pas directement les décisions de la phase actuelle
- il ne bloque pas les prochaines étapes de conception ou de développement
- il dépend d’arbitrages encore non réalisés
- il serait prématuré de le détailler maintenant

Quand un sujet devient concret, il sort du backlog et devient un vrai document.

---

## 3. Sujets documentaires prévus plus tard

| Sujet | Pourquoi c’est utile | Quand l’activer | Dossier cible |
|---|---|---|---|
| strategie-support-client.md | formaliser la relation SAV détaillée | quand le support réel commence à être cadré finement | 06_ops-deploiement-qualite |
| processus-de-mise-en-ligne.md | détailler chaque étape de publication | quand la stratégie preview/publication est stabilisée | 06_ops-deploiement-qualite |
| processus-de-modifications-post-livraison.md | distinguer maintenance, ajustement et hors périmètre | quand l’offre post-livraison est clarifiée | 06_ops-deploiement-qualite |
| runbook-incidents.md | documenter les réponses opérationnelles | quand l’infra cible existe vraiment | 06_ops-deploiement-qualite |
| checklist-lancement-site.md | sécuriser les mises en ligne | quand le premier process réel de publication est défini | 06_ops-deploiement-qualite |
| checklist-onboarding-client.md | standardiser l’entrée d’un nouveau client | quand le questionnaire et le parcours sont stabilisés | 04_produit-metier |
| matrice-risques-dependances.md | visualiser les risques liés aux tiers | quand les services externes sont identifiés | 08_validation-roadmap |
| budget-outils-et-couts-recurrents.md | suivre les coûts réels de fonctionnement | quand la liste des dépendances est suffisamment claire | 06_ops-deploiement-qualite |
| kpi-techniques.md | suivre la santé technique du système | quand l’observabilité et l’infra sont définies | 06_ops-deploiement-qualite |
| charte-editoriale.md | harmoniser le ton et le niveau des contenus | quand la stratégie contenu/template prend forme | 04_produit-metier |
| strategie-analytics-client.md | cadrer de futures stats visibles côté client | quand un dashboard client devient crédible | 03_business-model ou 06_ops |
| strategie-avis-clients.md | gérer l’usage et l’affichage des avis | quand ce levier entre dans l’offre | 03_business-model ou 04_produit-metier |
| strategie-ia-generation.md | encadrer l’usage éventuel de l’IA | quand l’IA entre réellement dans la génération | 05_tech-architecture |
| plan-de-migration-vers-saas-complet.md | préparer l’évolution produit à plus grande échelle | quand le MVP fonctionne et se vend | 08_validation-roadmap |
| benchmark-solutions-techniques.md | comparer les options techniques avancées | quand plusieurs voies techniques sont encore crédibles | 05_tech-architecture |
| strategie-partenariats-prescripteurs.md | formaliser les partenariats d’acquisition | quand le canal direct est validé ou saturé | 03_business-model |

---

## 4. Critères de sortie du backlog

Un sujet doit sortir du backlog quand :

- il bloque une décision actuelle
- il influe directement sur le développement à venir
- il impacte le modèle économique ou juridique
- il devient nécessaire à la cohérence de l’offre
- il devient nécessaire à l’exploitation réelle

---

## 5. Sujets à surveiller particulièrement

Les sujets suivants sont en backlog, mais peuvent remonter rapidement en priorité :

- budget-outils-et-couts-recurrents.md
- checklist-onboarding-client.md
- charte-editoriale.md
- processus-de-mise-en-ligne.md
- kpi-techniques.md

---

## 6. Règle de maintenance

Lorsqu’un document est créé depuis ce backlog :

1. supprimer ou marquer l’entrée comme activée
2. ajouter le document dans `index-avancement.md`
3. préciser sa priorité et son statut
4. vérifier s’il crée de nouveaux besoins documentaires