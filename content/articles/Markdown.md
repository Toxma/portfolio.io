+++
title = "Mon workflow en markdown"
date = 2023-01-30
menu = "main"
+++
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white) ![VSCodium](https://img.shields.io/badge/vscodium-2F80ED.svg?style=for-the-badge&logo=vscodium&logoColor=white)

> Le markdown est un langage de balisage créé en 2004, il a pour but d'être une syntaxe facile à lire et à écrire. Personnellement je l'utilise pour écrire mes cours, prendre des notes ou bien même pour faire les pages de mon portfolio.

<!--more-->
---

- [Éditeur de texte](#éditeur-de-texte)
  - [Mes extensions](#mes-extensions)
    - [Markdown All In One](#markdown-all-in-one)
    - [Markdown Lint](#markdown-lint)
    - [Markdown Preview Enhanced](#markdown-preview-enhanced)
  - [Fichier de configuration](#fichier-de-configuration)

---

## Éditeur de texte

> Comme éditeur de texte autant pour de la programmation, que pour de la prise de notes, j'utilise comme éditeur de texte [VSCodium](https://vscodium.com/). C'est une alternative à VSCode de chez Microsoft sauf que tous les trackers sont supprimés et le code source est totalement disponible. Il est même possible de configurer VSCodium pour qu'il accède à la marketplace des extensions de Visual Studio Code. Pour ceci, il suffit d'ajouter ces 4 lignes de code dans le fichier product.json de votre éditeur.

```json

    "extensionsGallery": {
    "serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
    "cacheUrl": "https://vscode.blob.core.windows.net/gallery/index",
    "itemUrl": "https://marketplace.visualstudio.com/items"
    },
 
```

### Mes extensions

> Pour ce qui est des extensions j'en utilise 3 qui me permettent de gagner du temps, d'avoir un fichier markdown très lisible et organisé.

#### Markdown All In One

- [Doc](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- Ajouter des shortcuts dans VSCodium (mettre en gras, mettre en italique)
- Créer et mettre à jour le sommaire
- Redimensionner les tableaux

#### Markdown Lint

- [Doc](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- Afficher les erreurs de syntaxes

#### Markdown Preview Enhanced

- [Doc](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- Afficher une preview du fichier markdown (ctrl k + ctrl v)
- Insérer un tableaux dans le fichier

### Fichier de configuration

> Afin de configurer des actions et des paramètres dans son workflow, il est possible d'ajouter un fichier dans son dossier de travail (.vscode/settings.json). Ici, ce code en json me permet de formater mon fichier avec l'extensions markdown all in one à chaque fois que je sauvegarde. De nombreux autres paramètres sont disponibles, tout dépend du besoin de chacun.

```json

    {
        "[markdown]": {
            "editor.defaultFormatter": "yzhang.markdown-all-in-one"
        },
        "editor.formatOnSave": true
    }
 
```
