# Blog Technique Personnel

Bienvenue sur mon blog technique où je partage mes réflexions sur l'IA, le développement logiciel et les technologies émergentes.

## Structure du Projet

```
.
├── articles/               # Dossiers d'articles (un par article)
│   └── YYYY-MM-titre/     # Format du dossier d'article
│       ├── index.html     # Contenu de l'article
│       └── assets/        # Images/ressources spécifiques
├── assets/                # Ressources globales
│   ├── css/              # Feuilles de style
│   ├── js/               # Fichiers JavaScript
│   └── images/           # Images globales
└── index.html            # Page d'accueil
```

## Comment ajouter un nouvel article

1. Créez un nouveau dossier dans `articles/` avec le format `YYYY-MM-titre`
2. Ajoutez un fichier `index.html` avec le contenu de votre article
3. Mettez à jour la page d'accueil (`index.html`) avec un lien vers votre nouvel article

## Développement local

Pour visualiser le blog localement, vous pouvez utiliser le serveur HTTP intégré à Python :

```bash
# Python 3
python3 -m http.server 8000
```

Puis ouvrez http://localhost:8000 dans votre navigateur.

## Déploiement

Ce blog est conçu pour être hébergé sur GitHub Pages. Il suffit de pousser le code dans la branche `main` de votre dépôt GitHub et d'activer GitHub Pages dans les paramètres du dépôt.

## Licence

Le contenu de ce blog est sous licence [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
