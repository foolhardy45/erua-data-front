# ERUA DATA — Frontend Angular

Application web de visualisation et d'exploration d'un graphe de connaissances reliant artistes, œuvres et mouvements artistiques.

## Aperçu

ERUA DATA permet aux chercheurs en histoire de l'art d'explorer les relations entre artistes et œuvres à travers un graphe interactif.

Le principe : un artiste pratiquant le cubisme est relié à d'autres artistes du même mouvement. En suivant ces liens, on peut découvrir des connexions artistiques, des influences croisées et des parcours stylistiques entre différentes époques et courants.

C'est un graphe de connaissances — similaire dans le concept à Neo4j — mais spécialisé pour le domaine artistique.

### Fonctionnalités

- Visualisation interactive du graphe de relations entre artistes et œuvres
- Navigation par liens : artiste → mouvement → autres artistes
- Recherche d'artistes et d'œuvres
- Création et édition de liens entre les entités (artistes, œuvres, mouvements)

## Stack technique

| Technologie | Usage |
|-------------|-------|
| Angular | Framework frontend |
| TypeScript | Langage |
| REST API | Communication avec le backend |

## Installation
```bash
npm install
ng serve
```

Application accessible sur `http://localhost:4200`.

## Structure du projet
```text
src/
├── app/
│   ├── components/    # Composants réutilisables (graphe, cartes, recherche)
│   ├── pages/         # Pages principales
│   ├── services/      # Services API
│   └── models/        # Interfaces TypeScript
├── environments/
└── main.ts
```

---

## Contexte & contribution

Projet réalisé en équipe dans le cadre de la SAÉ S4 — BUT2 Informatique, IUT de Montreuil.

**Mon rôle :**
- Développement complet du frontend Angular
- Conception de l'interface de visualisation du graphe
- Intégration des services API pour la récupération et la manipulation des données

### Repo lié

- [erua-data-back](https://github.com/tayrell/erua-data-back) — Backend API
