# Je-suis-toi

<img width="1414" height="2000" alt="Je suis toi 2" src="https://github.com/user-attachments/assets/7633546d-14fa-40a5-9e08-95bc0e04ba11" />

## Le projet

**Je suis toi** est un jeu d’enquête interactif en temps réel. Le joueur incarne un enquêteur dont il choisit le nom et construit lui-même ses raisonnements à partir de témoignages, documents, preuves, analyses et contradictions.

Le temps de l’enquête suit le temps réel. Les personnages continuent à vivre et à travailler lorsque le joueur quitte le jeu.

## Documentation

- [Document de conception du jeu](docs/conception-jeu.md)
- [Bible de l’affaire 01 — Alexander](docs/enquetes/01-alexander/README.md)

## Arborescence

```
Je-suis-toi/
│
├── README.md
│
├── docs/
│   ├── conception-jeu.md
│   │
│   └── enquetes/
│       └── 01-alexander/
│           ├── README.md
│           ├── personnages/
│           │   ├── entourage-du-flic/
│           │   └── entourage-de-la-victime/
│           ├── indices/
│           │   └── README.md
│           ├── lieux/
│           │   └── README.md
│           ├── elements/
│           │   └── README.md
│           ├── point-01.md
│           ├── point-02.md
│           ├── ...
│           └── point-29.md
│
└── src/
    └── ...
```

## Affaire 01

La première enquête est centrée sur Alexander Beaumont, homme d’affaires américain retrouvé mort à Poitiers alors qu’un autre homme continue publiquement à vivre sous son identité.

La documentation détaillée de l’affaire est organisée en un fichier Markdown par point. Les personnages possèdent en parallèle leurs propres fiches, séparées du déroulement de l’enquête, afin de conserver une référence complète et cohérente sans mélanger la bible narrative et le code du jeu.
