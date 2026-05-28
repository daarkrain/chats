# 🎲 Galerie Aléatoire

Un site minimaliste qui affiche une image aléatoire à chaque actualisation.

## Structure

```
random-gallery/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── images.js   ← à modifier
│   └── app.js
└── images/         ← tes photos ici
    ├── photo1.jpg
    ├── photo2.png
    └── ...
```

## Comment ajouter des images

1. **Dépose** tes images dans le dossier `images/`
2. **Ouvre** `js/images.js` et ajoute le nom de chaque fichier dans le tableau :

```js
const IMAGES = [
  "photo1.jpg",
  "vacances.png",
  "mon-chat.webp",
  // ...
];
```

3. **Commit & push** sur GitHub — c'est tout !

## Publier sur GitHub Pages

1. Crée un dépôt sur GitHub
2. Push ce dossier
3. Dans **Settings → Pages**, choisis la branche `main` et le dossier `/` (root)
4. Ton site sera disponible sur `https://ton-pseudo.github.io/nom-du-repo`

## Raccourcis

| Action | Contrôle |
|--------|----------|
| Image suivante | `Espace` ou `→` |
| Image suivante | Swipe gauche/droite (mobile) |
| Image suivante | Bouton "Nouvelle image" |

## Formats supportés

`.jpg` `.jpeg` `.png` `.gif` `.webp` `.avif` `.svg`
