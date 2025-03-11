# Guide de Contribution au Wiki PokéLegend 📝

Bienvenue ! Ce guide vous accompagnera pas à pas dans la contribution au wiki du projet PokéLegend sur GitHub.

## 📋 Pré-requis

- Créez un compte GitHub : [Inscription GitHub](https://github.com/join).
- Installez Git sur votre ordinateur : [Télécharger Git](https://git-scm.com/downloads).
- Choisissez un éditeur simple et convivial comme [Visual Studio Code](https://code.visualstudio.com/).

## ⚙️ Installer et configurer Git

Après l'installation, ouvrez votre terminal et configurez votre nom et email (ceux utilisés pour GitHub) :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre-email@example.com"
```

## 🚀 Faire une contribution

### 1. Forker le Repository

- Rendez-vous sur [wiki-pokelegend](https://github.com/Rivrs-OSS/wiki-pokelegend)
- Cliquez sur le bouton **Fork** en haut à droite pour créer une copie du repository sur votre compte.

### 2. Cloner votre Fork sur votre ordinateur

Copiez le lien de votre fork puis dans votre terminal :

```bash
git clone https://github.com/VOTRE-NOM-UTILISATEUR/wiki-pokelegend.git
cd wiki-pokelegend
```

### 3. Créer une nouvelle branche

Créer une branche par sujet traité pour bien organiser vos contributions :

```bash
git checkout -b nom-de-votre-branche
```

Exemple : `git checkout -b ajout-guide-capture`

### 4. Modifier le Wiki

- Utilisez Visual Studio Code pour éditer les fichiers markdown (`.md`).
- Vous pouvez également créer de nouveaux fichiers, par exemple `comment-capturer-pokemon.md`.

Exemple de structure markdown simple :

```markdown
# Titre principal

## Sous-titre

Votre contenu ici...

- Liste à puces
- Second point

[Un lien utile](http://example.com)
```

### 5. Ajouter vos modifications à Git

Dans votre terminal, ajoutez et validez vos changements :

```bash
git add .
git commit -m "Ajout du guide sur la capture des Pokémon"
```

### 6. Envoyer votre contribution

Envoyez vos modifications sur GitHub :

```bash
git push origin nom-de-votre-branche
```

### 7. Ouvrir une Pull Request (PR)

- Retournez sur votre fork du projet GitHub.
- Cliquez sur **Compare & pull request**.
- Décrivez votre contribution clairement puis validez en cliquant sur **Create pull request**.

## 💡 Bonnes pratiques et conseils

- Restez clair et concis dans vos explications.
- Vérifiez l'orthographe et la grammaire.
- Structurez bien vos pages markdown.
- Utilisez les prévisualisations markdown de Visual Studio Code (Ctrl + Shift + V) avant de soumettre.

## 🛠️ En cas de problème

N'hésitez pas à créer une [issue](https://github.com/Rivrs-OSS/wiki-pokelegend/issues) sur GitHub pour demander de l'aide ou poser une question.

Merci pour votre contribution ! ✨

