# CréaMénage — installation sur iPad

CréaMénage est une application web installable (PWA) : elle se lance depuis une icône sur l’écran d’accueil de l’iPad, en plein écran, sans App Store.

## Publication gratuite avec GitHub Pages (Windows)

1. Créez un compte sur GitHub, puis ouvrez la page `https://github.com/new`.
2. Nommez le dépôt `crea-menage`, choisissez **Public**, puis cliquez sur **Create repository**.
3. Sur la page du dépôt, cliquez sur **uploading an existing file**.
4. Décompressez le ZIP CréaMénage sur votre PC. Glissez **le contenu du dossier** dans la zone d’envoi : `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` et le dossier `icons`.
5. Cliquez sur **Commit changes**.
6. Ouvrez **Settings > Pages**. Dans **Build and deployment**, choisissez **Deploy from a branch**, puis `main` et `/ (root)`. Enregistrez.
7. GitHub affichera ensuite l’adresse de l’application, généralement `https://VOTRE-PSEUDO.github.io/crea-menage/`.

## Installation sur l’iPad

1. Ouvrez l’adresse GitHub Pages dans **Safari**.
2. Touchez le bouton **Partager** (carré avec flèche vers le haut).
3. Choisissez **Sur l’écran d’accueil** puis **Ajouter**.
4. Lancez CréaMénage depuis sa nouvelle icône.

Ouvrez une première fois le Pokédex avec Internet afin que les images consultées puissent être conservées en cache. Les tâches, XP, captures, réglages et journées sont sauvegardés dans Safari sur cet iPad.

## Sauvegarder la progression

Dans **Réglages**, utilisez **Exporter** pour enregistrer un fichier JSON. Le bouton **Restaurer** permet de récupérer ce fichier sur un autre appareil ou après une réinstallation.

## Mise à jour ultérieure

Remplacez les fichiers du dépôt GitHub par ceux d’une nouvelle version. L’application installée récupérera la mise à jour lors d’une prochaine ouverture avec Internet.

## Usage des Pokémon

Cette version emploie des noms et images Pokémon via PokéAPI pour un usage familial privé. Elle n’est ni officielle ni affiliée à Nintendo, Game Freak, Creatures ou The Pokémon Company. Ne la commercialisez pas et ne la diffusez pas publiquement comme un produit officiel.
