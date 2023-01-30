+++
title = "Mon workflow en markdown"
date = 2023-01-30T22:46:28+01:00
menu = "main"
+++

> Le markdown est un langage de balisage crée en 2004, il a pour but d'être une syntaxe facile à lire et à écrire. Personellement je l'utilise pour écrire mes cours, prendre des notes ou bien même pour faire les pages de mon portfolio.

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

> Pour le markdown j'utilise comme éditeur de texte [VSCodium](https://vscodium.com/) qui est une alternative à VSCode en supprimant tout les trackeurs de Microsoft. Il est même possible de configurer VSCodium pour qu'il accéde à la marketplace des extensions de Visual Studio Code.

![image](/vscodium.png)

### Mes extensions

> Pour ce qui est des extensions j'en utilise 3 qui me permettent de gagner du temps, d'avoir un fichier markdown très lisible et organisé.

- [Markdown All In One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

- [Markdwon Lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

#### Markdown All In One

- Ajouter des shortcuts dans VSCodium (mettre en gras, mettre en italique)
- Créer et mettre à jour le sommaire
- Redimensionner les tableaux

#### Markdown Lint

- Afficher les erreurs de syntaxes

#### Markdown Preview Enhanced

- Afficher une preview du fichier markdown (ctrl k + ctrl v)
- Insérer un tableaux dans le fichier

### Fichier de configuration

> Afin de configurer des actions et des paramétres dans son workflow, il faut ajouter un fichier dans son dossier de travail (.vscode/settings.json).

```json
{
    "[markdown]": {
        "editor.defaultFormatter": "yzhang.markdown-all-in-one"
    },
    "editor.formatOnSave": true
}
```

> Ici, ce fichier me permet de formatter mon fichier avec l'extensions markdown all in one à chaque fois que je sauvegarde. De nombreux autres paramètres sont disponible, tout depend du besoin de chacun.
