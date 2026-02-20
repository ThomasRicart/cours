# 📚 Séquence SNT – Les réseaux sociaux
## Guide professeur – Vue d'ensemble

---

## Organisation de la séquence (5 × 1h30)

| Séance | Titre | Notions du programme couvertes | Outils |
|--------|-------|-------------------------------|--------|
| 1 | Identité numérique et panorama | Identité, e-réputation, identification, authentification, modèle économique, CGU | Navigateur, recherche web |
| 2 | Les graphes | Rayon, diamètre, centre, petit monde, expérience de Milgram | Python + papier (débranché) |
| 3 | Algorithmes de recommandation | Recommandation, bulle de filtre, bonding/bridging, fake news | Python |
| 4 | Cyberviolence | Formes de cyberviolence, art. 222-33-2-2, ressources | Navigateur, réflexion |
| 5 | Projet de synthèse | Toutes les notions | Python (matplotlib) |

---

## Couverture du programme officiel

| Contenu programme | Capacité attendue | Séance |
|-------------------|-------------------|--------|
| Identité numérique, e-réputation, identification, authentification | Connaître les principaux concepts | S1 |
| Réseaux sociaux existants | Distinguer selon caractéristiques + ordre de grandeur | S1 |
| Réseaux sociaux existants | Paramétrer confidentialité | S1 |
| Modèle économique | Identifier les sources de revenus | S1 |
| Rayon, diamètre, centre d'un graphe | Déterminer sur graphes simples | S2 |
| Notion de « petit monde » / Milgram | Décrire comment l'info est conditionnée par ses amis | S2, S3 |
| Cyberviolence | Connaître art. 222-33-2-2 | S4 |
| Cyberviolence | Connaître formes et ressources | S4 |

**Toutes les capacités du programme sont couvertes.**

---

## Notes pédagogiques par séance

### Séance 1 – Identité numérique
**Point d'attention :** ne pas demander aux élèves de partager leurs vraies informations personnelles. Travailler systématiquement avec des personnages fictifs.  
**Activité CGU :** prévoir que les CGU sont souvent très longues. Proposer un extrait sélectionné au préalable, ou cibler des questions précises.  
**Différenciation :** l'exercice sur le RGPD et les mineurs peut être approfondi avec les élèves avancés.

### Séance 2 – Les graphes
**Mode débranché conseillé** pour la première partie : faire dessiner les graphes à la main avant de passer à Python. La manipulation physique aide à la compréhension.  
**Point d'attention :** le calcul de la matrice des distances peut être long à faire à la main. Limiter à 6-7 sommets maximum en activité manuelle.  
**Outil externe :** [graphonline.ru](https://graphonline.ru/en/) permet de visualiser des graphes interactivement dans le navigateur (sans installation).

### Séance 3 – Recommandation et bulles
**Point d'attention :** la notion de bulle de filtre peut toucher à des sujets politiques. Rester neutre et privilégier l'analyse du mécanisme algorithmique plutôt que des exemples politiques spécifiques.  
**Lien avec l'actualité :** des exemples récents de fake news ou de désinformation peuvent être apportés par l'enseignant (éviter de demander aux élèves d'en trouver eux-mêmes pour limiter la propagation).

### Séance 4 – Cyberviolence
**Point d'attention :** séance sensible. Prévenir à l'avance les élèves du sujet. Avoir connaissance du protocole de l'établissement si un élève révèle une situation de cyberviolence vécue.  
**Ressource à afficher en classe :** le numéro 3018 peut être affiché au tableau pendant toute la séance.  
**Prolongement :** visiter nonauharcelement.education.gouv.fr en classe entière.

### Séance 5 – Synthèse
**Cette séance fonctionne bien en binôme.** Les discussions entre élèves enrichissent l'analyse.  
**La mission 5 (bilan critique)** peut être rendue comme évaluation écrite ou support de discussion orale.  
**Évaluation possible :** noter la qualité de l'analyse dans le rapport (mission 5) : pertinence des arguments, mobilisation des notions vues, recul critique.

---

## Évaluation possible

**Type :** évaluation pratique sur machine + questions écrites.

**Support :** fournir un nouveau jeu de données (nouveau réseau fictif) et demander :
1. Calcul du degré de chaque sommet (graphe)
2. Calcul du diamètre
3. Recommandations d'amis pour un utilisateur donné
4. Question ouverte sur modèle économique / cyberviolence

---

## Ressources complémentaires

- [nonauharcelement.education.gouv.fr](https://nonauharcelement.education.gouv.fr)
- [graphonline.ru/en/](https://graphonline.ru/en/) – outil de visualisation de graphes
- [data.gouv.fr](https://data.gouv.fr) – pour explorer des données réelles sur les réseaux sociaux
- [pixees.fr](https://pixees.fr) – ressources pédagogiques SNT
- Documentation Python `collections.Counter` et `collections.deque`
