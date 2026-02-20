# 📚 Séquence SNT – Les données structurées et leur traitement
## Guide professeur – Vue d'ensemble

---

## Organisation de la séquence (5 × 1h30)

| Séance | Titre | Notions du programme couvertes | Outils |
|--------|-------|-------------------------------|--------|
| 1 | Données, descripteurs et formats | Données, descripteurs, collection, CSV, métadonnées | Python + exploration fichiers |
| 2 | Open Data : des données pour tous | Données personnelles, Open Data, types de données | Python + data.gouv.fr |
| 3 | Trier, filtrer, calculer | Opérations de recherche, tri, filtre, calcul | Python + LibreOffice Calc |
| 4 | Croiser deux tables et visualiser | Croisement de tables, visualisation | Python (matplotlib) |
| 5 | Cloud, stockage et impact environnemental | Cloud, supports de stockage, consommation énergétique | Python |

---

## Couverture du programme officiel

### Contenus et capacités attendues

| Contenu | Capacité | Séance |
|---------|----------|--------|
| Données | Définir une donnée personnelle | S2 |
| Données | Identifier les principaux formats et représentations | S1, S2 |
| Données structurées | Identifier les descripteurs d'un objet | S1 |
| Données structurées | Distinguer valeur et descripteur | S1 |
| Données structurées | Utiliser un site de données ouvertes | S2 |
| Traitement | Recherche, filtre, tri, calcul sur une ou plusieurs tables | S3, S4 |
| Métadonnées | Retrouver les métadonnées d'un fichier personnel | S1 |
| Cloud | Utiliser un support de stockage dans le nuage | S5 |
| Cloud | Identifier les causes de la consommation énergétique | S5 |

**Toutes les capacités du programme sont couvertes.**

---

## Prérequis élèves

- Bases Python : variables, boucles `for`, conditions `if`, listes
- Utilisation basique de LibreOffice Calc (séance 3)
- Accès à Internet (séance 2)

---

## Notes pédagogiques par séance

### Séance 1 – Données, descripteurs et formats
**Objectif principal** : poser le vocabulaire de base  
**Point d'attention** : bien distinguer *descripteur* (nom de colonne) et *valeur* (contenu d'une cellule). C'est une confusion fréquente.  
**Différenciation** : l'exercice 4 (film le plus long) peut être proposé aux élèves avancés.

### Séance 2 – Open Data
**Objectif principal** : connecter les notions à des données réelles  
**Point d'attention** : les conversions de types (`int()`, `float()`) sont souvent oubliées. Insister dessus.  
**Prolongement** : encourager les élèves à chercher leurs propres jeux de données sur data.gouv.fr.

### Séance 3 – Tri, filtre, calcul
**Objectif principal** : maîtriser les 3 opérations fondamentales  
**Point d'attention** : la syntaxe `lambda` pour le tri peut surprendre. On peut la remplacer par une fonction définie avec `def` si nécessaire.  
**Activité tableur** : prévoir 10-15 min pour la partie LibreOffice Calc. L'objectif est de montrer que les deux outils font la même chose différemment, pas de maîtriser le tableur.

### Séance 4 – Croisement de tables
**Objectif principal** : comprendre l'intérêt de la normalisation des données  
**Point d'attention** : la notion de "clé étrangère" n'est pas au programme, mais le principe de liaison par identifiant doit être bien compris.  
**Matplotlib** : si matplotlib n'est pas installé, utiliser `pip install matplotlib` ou proposer l'activité de visualisation dans LibreOffice Calc à la place.

### Séance 5 – Cloud et impact environnemental
**Objectif principal** : donner du sens et ouvrir sur les enjeux sociétaux  
**Point d'attention** : les chiffres d'empreinte carbone sont des ordres de grandeur. Insister sur le fait qu'ils varient selon les sources et les méthodes de calcul.  
**Débat** : prévoir au moins 15 min pour la discussion. Cette séance doit permettre aux élèves de formuler un avis éclairé.

---

## Évaluation possible

On peut proposer une évaluation pratique sur machine avec :
- Un nouveau fichier CSV fourni par le professeur (ex : résultats sportifs, données climatiques...)
- Des questions de filtrage, tri et calcul à réaliser en Python
- Une question ouverte sur les enjeux (Open Data, vie privée, environnement)

---

## Ressources complémentaires

- [data.gouv.fr](https://data.gouv.fr) – données ouvertes françaises
- [pixees.fr](https://pixees.fr) – ressources pédagogiques SNT
- [documentation Python csv](https://docs.python.org/fr/3/library/csv.html)
- [ADEME – guide numérique responsable](https://www.ademe.fr)
