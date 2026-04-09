# Index d’avancement documentaire

## 1. Rôle du document

Ce document sert à piloter l’avancement de la documentation projet.

Il permet de :

- visualiser rapidement l’état des documents
- savoir quels fichiers sont prioritaires
- distinguer les documents actifs, préparés et futurs
- garder une cohérence entre cadrage, conception et développement
- éviter d’oublier un sujet important au moment où il devient nécessaire

Ce document ne remplace pas le README projet.

Le README structure la documentation.
L’index d’avancement suit sa progression réelle.

---

## 2. Légende des statuts

- **référence** : document déjà structurant et exploitable
- **à consolider** : document existant mais encore incomplet ou partiellement flou
- **à créer maintenant** : document nécessaire pour les prochaines étapes
- **à créer bientôt** : document utile à court terme, mais non bloquant immédiatement
- **backlog** : sujet identifié, à traiter plus tard
- **en pause** : document volontairement reporté

---

## 3. Légende des priorités

- **P1** : nécessaire pour cadrer la suite sans angle mort
- **P2** : utile rapidement pour éviter des retours en arrière
- **P3** : utile plus tard, non urgent
- **P4** : optionnel ou lointain

---

## 4. Phase actuelle du projet

**Phase en cours** : cadrage stratégique, produit et pré-conception.

Objectifs immédiats :

- stabiliser la vision et le positionnement
- figer le périmètre MVP
- consolider le modèle métier
- préparer les décisions qui impactent directement la conception et le développement

---

## 5. Suivi des documents actifs

| Dossier | Document | Rôle principal | Statut | Priorité | Bloque le dev ? | Prochaine action |
|---|---|---|---|---:|---|---|
| 01_vision-strategie | vision-produit.md | définir la finalité produit | référence | P1 | oui | relire et ajuster si besoin |
| 01_vision-strategie | probleme-cible-marche.md | cadrer cible, besoin, marché | référence | P1 | oui | conserver comme base |
| 01_vision-strategie | positionnement-promesse-valeur.md | clarifier la promesse centrale | référence | P1 | oui | consolider le wording |
| 01_vision-strategie | positionnement-entreprise.md | définir la posture de la structure | à consolider | P1 | oui | travailler maintenant |
| 02_offre-mvp | mvp-perimetre.md | définir le in/out scope | référence | P1 | oui | figer progressivement |
| 02_offre-mvp | offre-mvp.md | formaliser l’offre testable | référence | P1 | oui | préciser les inclus/exclus |
| 02_offre-mvp | decisions-ouvertes-mvp.md | centraliser les arbitrages restants | référence | P1 | oui | convertir en décisions |
| 03_business-model | pricing-et-concurrence.md | ancrer la réflexion prix | référence | P1 | non | garder comme repère |
| 03_business-model | hypotheses-economiques.md | poser les hypothèses de viabilité | à consolider | P1 | oui | enrichir avec coûts |
| 03_business-model | modele-de-commercialisation.md | décrire la mécanique de vente | référence | P1 | oui | préciser le parcours |
| 03_business-model | modele-de-facturation.md | cadrer facturation, abonnement, résiliation | à créer maintenant | P1 | oui | créer en priorité |
| 03_business-model | strategie-acquisition.md | définir les premiers canaux d’acquisition | à créer maintenant | P1 | non | créer rapidement |
| 04_produit-metier | modele-metier.md | formaliser les entités et relations | à consolider | P1 | oui | approfondir |
| 04_produit-metier | parcours-utilisateur.md | décrire le flow utilisateur | référence | P1 | oui | préciser les variantes |
| 04_produit-metier | regles-de-gestion.md | formaliser les règles métier | à consolider | P1 | oui | détailler les cas |
| 04_produit-metier | cycle-de-vie-projet.md | décrire les statuts et transitions | à créer maintenant | P1 | oui | créer vite |
| 04_produit-metier | user-stories.md | traduire la vision en besoins exploitables | à créer maintenant | P1 | oui | créer vite |
| 04_produit-metier | questionnaire-de-collecte.md | définir les données à demander | à créer maintenant | P1 | oui | créer vite |
| 04_produit-metier | criteres-acceptation.md | définir le done produit | à créer bientôt | P2 | non | créer après user stories |
| 04_produit-metier | strategie-contenu.md | cadrer les manques de contenu client | à créer bientôt | P2 | non | créer après questionnaire |
| 04_produit-metier | template-systeme-sections.md | formaliser la grammaire du site | à créer bientôt | P2 | oui | créer avant implémentation front |
| 05_tech-architecture | architecture-logique.md | décrire les blocs fonctionnels | référence | P1 | oui | enrichir après modèle métier |
| 05_tech-architecture | architecture-technique.md | cadrer la construction technique | à consolider | P1 | oui | enrichir |
| 05_tech-architecture | stack-et-choix-techniques.md | justifier la stack | référence | P1 | non | garder comme socle |
| 05_tech-architecture | dependances-et-services-externes.md | lister les briques tierces | à créer maintenant | P1 | oui | créer vite |
| 05_tech-architecture | strategie-authentification.md | définir qui se connecte et comment | à créer maintenant | P1 | oui | créer vite |
| 05_tech-architecture | strategie-autorisations-rbac.md | définir les permissions | à créer maintenant | P1 | oui | créer vite |
| 05_tech-architecture | strategie-preview-publication.md | cadrer preview, validation, publication | à créer maintenant | P1 | oui | créer vite |
| 05_tech-architecture | strategie-multi-tenant.md | cadrer l’isolation V1 | à créer maintenant | P1 | oui | créer vite |
| 05_tech-architecture | strategie-validation-et-sanitization.md | sécuriser validation et rendu | à créer bientôt | P2 | oui | créer avant build réel |
| 05_tech-architecture | diagrammes/* | formaliser la conception | à créer bientôt | P2 | non | après consolidation métier/tech |
| 06_ops-deploiement-qualite | performance-et-capacite.md | cadrer tenue en charge et seuils | à consolider | P2 | non | enrichir progressivement |
| 06_ops-deploiement-qualite | support-et-exploitation.md | définir le support réel | à créer maintenant | P1 | oui | créer vite |
| 06_ops-deploiement-qualite | gestion-domaines-hebergement.md | cadrer domaine, hébergement, transfert | à créer maintenant | P1 | oui | créer vite |
| 06_ops-deploiement-qualite | securite-applicative.md | cadrer les protections app | à créer maintenant | P1 | oui | créer vite |
| 06_ops-deploiement-qualite | securite-reseau-et-infra.md | cadrer la sécurité infra | à créer bientôt | P2 | non | créer après l’infra cible |
| 06_ops-deploiement-qualite | observabilite.md | définir logs, alertes, métriques | à créer bientôt | P2 | non | créer après architecture |
| 06_ops-deploiement-qualite | strategie-tests-et-recette.md | cadrer la validation qualité | à créer maintenant | P1 | oui | créer vite |
| 06_ops-deploiement-qualite | infrastructure-deploiement.md | décrire le déploiement cible | à créer bientôt | P2 | non | créer après choix infra |
| 06_ops-deploiement-qualite | budget-outils-et-couts-recurrents.md | suivre le coût des briques externes | à créer bientôt | P2 | non | créer après dépendances |
| 07_juridique-conformite | rgpd.md | cadrer données personnelles et traitement | à créer maintenant | P1 | oui | créer vite |
| 07_juridique-conformite | cgv-et-contrat-type.md | cadrer relation contractuelle | à créer bientôt | P2 | oui | créer avant commercialisation réelle |
| 07_juridique-conformite | propriete-intellectuelle-et-contenus.md | cadrer propriété du site et du contenu | à créer bientôt | P2 | oui | créer avant vente réelle |
| 07_juridique-conformite | mentions-legales-et-politique-confidentialite.md | obligations légales visibles | à créer bientôt | P2 | oui | créer avant mise en ligne publique |
| 07_juridique-conformite | reversibilite-sortie-client.md | cadrer la sortie client | à créer bientôt | P2 | non | créer avant modèle final |
| 08_validation-roadmap | hypotheses-a-tester.md | centraliser les hypothèses | référence | P1 | non | garder actif |
| 08_validation-roadmap | questions-ouvertes.md | centraliser les sujets non tranchés | référence | P1 | non | garder actif |
| 08_validation-roadmap | roadmap.md | piloter les grandes phases | référence | P1 | non | mettre à jour après chaque étape clé |
| 08_validation-roadmap | journal-decisions.md | tracer les décisions | référence | P1 | oui | enrichir régulièrement |
| 08_validation-roadmap | registre-des-risques.md | centraliser les risques projet | à créer maintenant | P1 | oui | créer vite |
| 08_validation-roadmap | kpi-produit-business.md | suivre la santé du modèle | à créer bientôt | P2 | non | créer après offre plus stable |
| 08_validation-roadmap | plan-de-validation-terrain.md | organiser les tests réels | à créer bientôt | P2 | non | créer après positionnement/offre |

---

## 6. Documents à traiter dans l’ordre recommandé

### Bloc 1 — à traiter immédiatement
1. positionnement-entreprise.md
2. modele-de-facturation.md
3. user-stories.md
4. questionnaire-de-collecte.md
5. cycle-de-vie-projet.md
6. dependances-et-services-externes.md
7. strategie-authentification.md
8. strategie-autorisations-rbac.md
9. strategie-preview-publication.md
10. strategie-multi-tenant.md
11. support-et-exploitation.md
12. securite-applicative.md
13. strategie-tests-et-recette.md
14. rgpd.md
15. registre-des-risques.md

### Bloc 2 — à traiter ensuite
1. hypotheses-economiques.md
2. regles-de-gestion.md
3. modele-metier.md
4. template-systeme-sections.md
5. strategie-contenu.md
6. gestion-domaines-hebergement.md
7. observabilite.md
8. budget-outils-et-couts-recurrents.md
9. kpi-produit-business.md
10. plan-de-validation-terrain.md

### Bloc 3 — à traiter plus tard
Tous les sujets du backlog documentaire.

---

## 7. Règle de mise à jour

À chaque fois qu’un document est créé ou travaillé :

1. mettre à jour son statut
2. réévaluer sa priorité
3. vérifier s’il débloque ou non d’autres documents
4. ajouter les décisions importantes dans `journal-decisions.md`
5. retirer du backlog ce qui est devenu actif

---

## 8. Définition de réussite

L’arborescence est considérée comme saine si :

- chaque document a un rôle clair
- les documents actifs correspondent à la phase actuelle
- les sujets futurs sont visibles sans encombrer la structure
- les décisions sont tracées
- les angles morts avant développement diminuent progressivement