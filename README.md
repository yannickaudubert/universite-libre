# Université libre

Ce dépôt est la racine d'une **université libre**, d'un **wiki personnel structuré** et d'un futur commun de connaissances.

Il commence avec les 60 premières fiches du corpus SIIAOS, mais son périmètre est volontairement plus large. Il doit pouvoir accueillir des concepts, méthodes, équations, cours, ateliers, sources, territoires, projets, outils, personnes, expériences et productions réutilisables.

## Principes

- **Git comme mémoire canonique** : toute évolution importante doit être versionnée et traçable.
- **Markdown et YAML en premier** : les contenus restent lisibles par un humain, un éditeur, Obsidian, un moteur RAG ou un agent.
- **Local-first** : le dépôt doit rester exploitable sans dépendance structurelle à un service distant.
- **Source avant affirmation** : distinguer observation, source, donnée dérivée, estimation, hypothèse, modèle conceptuel et résultat validé.
- **Une connaissance peut avoir plusieurs formes** : note, fiche visuelle, fiche détaillée, méthode, cours, atelier, outil ou commun.
- **Réutilisation progressive** : les productions doivent pouvoir passer du wiki personnel à l'enseignement puis, après revue, à un commun partageable.
- **Pas de faux statut scientifique** : les modèles conceptuels, symboliques ou méthodologiques sont explicitement identifiés comme tels.

## Carte du dépôt

```text
universite-libre/
├── README.md
├── wiki/               # mémoire personnelle reliée
├── universite/         # parcours, cours, ateliers, évaluations
├── corpus/             # collections structurées de fiches et médias
├── governance/         # règles de publication, provenance et maturation
├── sources/            # conventions et inventaires de sources
├── templates/          # patrons réutilisables
└── assets/             # ressources communes
```

## Premier corpus

Le premier fonds est le corpus **SIIAOS · Équations et modèles**, constitué de 60 fiches individuelles avec image, note Markdown et métadonnées YAML.

- [Accéder au corpus SIIAOS](corpus/siiaos-equations/README.md)
- [Voir le registre des 60 fiches](corpus/siiaos-equations/registry/index.md)
- [Entrer par le wiki](wiki/index.md)
- [Entrer par l'université](universite/README.md)

## Cycle de maturation

Une contribution peut suivre le chemin suivant :

`Trace → Fragment → Indice → Hypothèse → Concept → Relation → Méthode → Skill → Agent → Livrable → Commun`

Toutes les étapes ne sont pas obligatoires. Le dépôt doit surtout préserver la provenance, les transformations et le statut de chaque objet.

## Publication

Le dépôt est conçu pour permettre plusieurs niveaux : privé, travail, partage restreint, publication publique et commun. La licence publique finale reste à définir au niveau de la gouvernance avant ouverture générale.
