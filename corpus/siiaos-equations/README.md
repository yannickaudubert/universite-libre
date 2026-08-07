# Corpus visuel SIIAOS / ARAGORN

Migration initiale des **60 premières fiches** du corpus.

Chaque fiche possède en parallèle :

- `fiche.png` : visuel historique ou crop fidèle de la planche source ;
- `note.md` : contenu textuel individuel, diffable dans Git ;
- `metadata.yaml` : identifiant, statut, provenance et relations.

## Structure

```text
corpus/siiaos-equations/
├── README.md
├── registry/
│   ├── corpus.yaml
│   ├── corpus.json
│   └── index.md
├── templates/
│   ├── note-patron.md
│   └── charte-visuelle.md
└── fiches/
    ├── 001-.../
    │   ├── fiche.png
    │   ├── note.md
    │   └── metadata.yaml
    └── ... jusqu’à 060
```

## Important

Les fiches 21 à 30 existaient à l’origine sous forme d’une planche unique de dix cartes. Elles ont été découpées sans modifier leur contenu afin de retrouver une organisation « une image + une note » par entrée.

Les équations du corpus n’ont pas toutes le même statut. Certaines sont des modèles conceptuels, méthodologiques ou symboliques. Les notes conservent ce statut pour éviter de les présenter comme des lois scientifiques établies.
